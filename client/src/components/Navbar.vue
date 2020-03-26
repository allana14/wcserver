<template>
<nav class="navbar navbar-icon-top navbar-expand-lg navbar-dark bg-dark">
  <a class="navbar-brand" href="#"><i>NEWS</i></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/">
         Home
        </router-link>
        </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/gallery">
         Gallery
        </router-link>
          </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/News">
         News
        </router-link>
          </a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
</template>

<style> 
a.navbar-brand{
  font-family:Impact Regular;
}
</style>