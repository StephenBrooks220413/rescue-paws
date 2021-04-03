<template>
  <div class="home">
    <!-- text & image carousel -->
    <!-- Carousel wrapper -->
    <div
      id="carouselBasicExample"
      class="carousel slide main carousel-fade"
      data-mdb-ride="carousel"
    >
      <!-- Indicators -->
      <div class="carousel-indicators">
        <button
          type="button"
          data-mdb-target="#carouselBasicExample"
          data-mdb-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-mdb-target="#carouselBasicExample"
          data-mdb-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-mdb-target="#carouselBasicExample"
          data-mdb-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>

      <!-- Inner -->
      <div class="carousel-inner">
        <!-- Single item -->
        <div class="carousel-item text-start text-color active">
          <h1>Serving the Best Customers</h1>
          <h3>
            Offering sitting services, grooming and so much more....
            <br /><br />
            <a
              href="mailto:stephenbrooks714@gmail.com"
              class="btn info-btn btn-outline-text-info btn-lg"
            >
              Learn More
            </a>
          </h3>
        </div>

        <!-- Single item -->
        <div class="carousel-item text-start text-color">
          <h1>Rescue Project</h1>
          <h3>
            Donate to save thousands of animals and bring them home...
            <br /><br />
            <a
              href="mailto:stephenbrooks714@gmail.com"
              class="btn info-btn btn-outline-text-info btn-lg"
            >
              Learn More
            </a>
          </h3>
        </div>

        <!-- Single item -->
        <div class="carousel-item text-start text-color">
          <h1>Volunteers Needed</h1>
          <h3>
            We appreciate our volunteers, and we have mobile volunteer
            available...
            <br /><br />
            <a
              href="mailto:stephenbrooks714@gmail.com"
              class="btn info-btn btn-outline-text-info btn-lg"
            >
              Learn More
            </a>
          </h3>
        </div>
      </div>
      <!-- Inner -->
    </div>
    <!-- end of Carousel wrapper -->
    <div class="media bg-light text-center">
      <div class="container p-4 pb-0">
        <!-- Section: Social media -->
        <section class="mb-4">
          <!-- Facebook -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #3b5998"
            href="#!"
            role="button"
            ><i class="fab fa-facebook-f"></i
          ></a>

          <!-- Twitter -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #55acee"
            href="#!"
            role="button"
            ><i class="fab fa-twitter"></i
          ></a>

          <!-- Google -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #dd4b39"
            href="#!"
            role="button"
            ><i class="fab fa-google"></i
          ></a>

          <!-- Instagram -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #ac2bac"
            href="#!"
            role="button"
            ><i class="fab fa-instagram"></i
          ></a>

          <!-- Linkedin -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #0082ca"
            href="#!"
            role="button"
            ><i class="fab fa-linkedin-in"></i
          ></a>
          <!-- Github -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #333333"
            href="#!"
            role="button"
            ><i class="fab fa-github"></i
          ></a>
        </section>
        <!-- Section: Social media -->
      </div>
    </div>
    <br /><br /><br /><br />
    <!-- content -->
    <div class="container text-center">
      <div class="row">
        <div class="col-md">
          <i class="fas icon fa-cut"></i>
          <br />
          <h1>Grooming</h1>
          <hr />
          <ul class="text-center">
            <li>Shampooing</li>
            <li>Trimming</li>
            <li>Claw Clipping</li>
          </ul>
        </div>
        <div class="col-md">
          <i class="fas icon fa-dog"></i>
          <br />
          <h1>Trained Staff</h1>
          <hr />
          <ul class="text-center">
            <li>Certified</li>
            <li>Over 7 years</li>
            <li>Mobile Teams</li>
          </ul>
        </div>
        <div class="col-md">
          <i class="fas icon fa-headset"></i>
          <br />
          <h1>Support</h1>
          <hr />
          <ul class="text-center">
            <li>24 / 7 Chat</li>
            <li>In-Home</li>
            <li>Follow Up's</li>
          </ul>
        </div>
      </div>
    </div>
    <!-- end of content -->
    <br /><br /><br /><br /><br />
    <!-- content body -->
    <div class="secondary">
      <h1 class="display-4 text-start text-color">Grooming the Pups</h1>
    </div>
    <br /><br /><br /><br /><br />
    <HelloWorld />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>

<style lang="scss" scoped>
@import "../assets/index.scss";

ul {
  list-style: none !important;
}
</style>
