<template>
    <div class="body">
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
            
            <div class="carousel-inner">
                <div class="carousel-item active bg-1">
                    <div class="carousel-caption">
                        <h5>Primeiro <span class="text-warning">Projeto</span></h5>
                        <p>Lorem ipsum dolor sit amet consectetur adipisic</p>
                        <a href="#" class="bg-warning text-white"> Learn More</a>
                    </div>
                </div>
                <div class="carousel-item bg-2">
                    <div class="carousel-caption">
                        <h5>Primeiro <span class="text-warning">Projeto</span></h5>
                        <p>Lorem ipsum dolor sit amet consectetur adipisic</p>
                        <a href="#" class="bg-warning text-white"> Learn More</a>
                    </div>
                </div>
                <div class="carousel-item bg-3">
                    <div class="carousel-caption ">
                        <h5>Primeiro <span class="text-warning">Projeto</span></h5>
                        <p>Lorem ipsum dolor sit amet consectetur adipisic</p>
                        <a href="#" class="bg-warning text-white"> Learn More</a>
                    </div>
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"><img src="../assets/cidade.jpg" class="d-block w-100 img-fluid"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"> <img src="../assets/code.gif" class="d-block w-100 img-fluid"></button>
                <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"><img src="../assets/cidade2.jpg" class="d-block w-100 img-fluid"></button>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "CarrosselComponent",
};
</script>

<style>
.body{
    font-family: montserrat;
}
.carousel-item{
    height:100vh;
    min-width: 300px;
}
.bg-1{
    background-image: url(../assets/cidade.jpg);
}
.bg-2{
    background-image: url(../assets/code.gif);
}
.bg-3{
    background-image: url(../assets/cidade2.jpg);
}
bg-1, bg-2, bg-3{
    background-size:cover;
}
.carousel-caption{
    bottom:220px;
    z-index:2;
}
.carousel-caption h5{
    text-transform: capitalize;
    font-size: 85px; 
    letter-spacing:2px;
    margin-top: 25px;
}
.carousel-caption p{
    width: 70%;
    margin:auto;
    font-size: 18px;
    line-height: 1.9;
}

.carousel-caption a{
    text-transform: uppercase;
    text-decoration: none;
    padding: 8px 20px;
    display:inline-block;
    color: #fff;
    margin-top: 15px;
    border-radius: 5px;
}
.carousel-inner::before{
    content:'';
    position:absolute;
    width: 100%;
    height: 100%;
    top:0;
    left: 0;
    background: rgba(0,0,0,0,0.6);
    z-index:1;

}
.carousel-indicators{
    bottom:35px;

}
.carousel-indicators button{
    width: 100px !important;
}
</style>
