<template>
  <div class=" header w-100 d-flex justify-content-between align-items-center">

    <div class="ms-4">
      <img class="w-75" src="../assets/image/avada-bakery-logo.png" alt="Bakery Logo">
    </div>

    <div class="headerMenu">
        <nav class="navbar navbar-expand-lg navbar-light">
          <div class="container-fluid">
            
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            
              <ul  class="navbar-nav me-auto mb-2 mb-lg-0">
              
                <li class="nav-item">
                  <a class="nav-link  color" aria-current="page" href="#">HOME</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link color" href="#">SHOP</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#" >ABOUT</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#" aria-disabled="true">GALLERY</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#" aria-disabled="true">LOCATIONS</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#" aria-disabled="true">JOURNAL</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#" aria-disabled="true">CONTACT</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#" aria-disabled="true">MY ACCOUNT</a>
                </li>

                <li class="nav-item">
                  <a class="nav-link" href="#" aria-disabled="true"><i class="fas fa-shopping-cart"></i></a>
                </li>
            
              </ul>

            </div>
          </div>
      </nav>
    </div>

  </div>
</template>

<script>
export default {
    name:"HeaderFix",
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";

.header{
  height:80px;
  // background:#f3e7f1;
  background: $background-header-color;

  .nav-item a{
    // color:#5b2ba2;
    color:$brand-primary-color;
    font-size:.7rem;
  }
}

</style>