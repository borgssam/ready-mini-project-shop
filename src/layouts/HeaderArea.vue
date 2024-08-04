<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Soldout</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expaned="false" aria-lable="Toggle naviation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSuppertedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item"><router-link class="nav-link" to="/">홈</router-link></li>
          <li class="nav-item"><router-link class="nav-link" to="/">제품리스트</router-link></li>
          <li class="nav-item"><router-link class="nav-link" to="/detail">제품상세페이지</router-link></li>
          <li class="nav-item"><router-link class="nav-link" to="/sales">제품등록페이지</router-link></li>
        </ul>
        <form class="d-flex">
          <input type="search" class="form-control me-2" placeholder="Search" aria-label="Search">
          <button type="submit" class="btn btn-outline-success">Search</button>
          
        </form>
      </div>

    </div>
    
  </nav>
</template>

<script>
export default {
  name: 'HeaderArea',
};
</script>
