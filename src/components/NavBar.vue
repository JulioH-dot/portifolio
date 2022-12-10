<template>
    <div>
      <nav class="navbar navbar-expand-lg navbar-custom fixed-top" >
        <div class="container ">
          <a class="navbar-brand text-white" href="#">Julio Henrique</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav ms-auto mb-2 mb-lg-0">
              <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
              <a class="nav-link text-white" href="#">Sobre</a>
              <a class="nav-link text-white" href="#">Projetos</a>
              <a class="nav-link text-white" href="#">Contato</a>
            </div>
          </div>
        </div>
      </nav>
    </div>
</template>

<script>

export default {
  name: 'NavBar',
  
}
</script>

<style scoped>
 .navbar-custom{
  background:   #23232e;
 }
 
 .navbar-custom .navbar-toggler-icon{
 background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 32 32' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255,255,255, 1)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 8h24M4 16h24M4 24h24'/%3E%3C/svg%3E");
}

.navbar-nav a{
    font-size: 15px ;
    text-transform: uppercase;
    font-weight: 700;
}

</style>