<template>
  <div>
    <nav class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Rescue Paws</a>
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarText"
          aria-controls="navbarText"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarText">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Features</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Pricing</a>
            </li>
          </ul>
          <span class="navbar-text"> Accounts </span>
        </div>
      </div>
    </nav>
  </div>
  <router-view />
</template>

<script>
import * as mdb from "mdb-ui-kit";

export default {
  mdb,
};
</script>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";

li {
  font-size: 22px !important;

  a {
    font-weight: bold;

    &.router-link-exact-active {
      color: #124be9;
    }
  }
}

.page-link {
  font-size: 26px !important;
  padding-top: 30px;
}
@media (max-width: 650px) {
  .page-link {
    font-size: 22px !important;
    padding-top: 24px !important;
  }
}
</style>
