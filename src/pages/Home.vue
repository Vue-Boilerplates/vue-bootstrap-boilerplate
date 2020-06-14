<template>
  <div class="text-center p-0 m-0 container-fluid">
    <Navbar />
    <div class="jumbotron m-0 p-0 p-3 jumbotron-fluid">
      <div class="container">
        <h2 class="display-4">Vue Boilerplates</h2>
        <p class="lead">vue-bootstrap-boilerplate</p>
        <div class="row mb-4 no-gutters justify-content-center">
          <img width="130px" height="auto" src="/img/vue-boilerplates.svg" />
        </div>
        <p class="m-0 p-0">
          Vue + Bootstrap + Lazy loading and code splitting
        </p>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col">
          <div
            class="jumbotron text-left m-0 text-dark bg-white border-white border"
          >
            <h2 class="display-5">Why Vue Boilerplates?</h2>
            <p>
              While mobile-first approach becomes a standard and uncertain
              network conditions are something we should always take into
              consideration, it’s harder and harder to keep your application
              loading fast. Vue Boilerplates was built with vue.js performance
              optimization techniques that make them loading instantly and
              perform smooth 🚀.
            </p>
          </div>
        </div>
        <div class="col">
          <div
            class="jumbotron text-left m-0 text-dark bg-white border-white border"
          >
            <h2 class="display-5">Lets grow together!</h2>
            <p class="lead">Please consider becoming a donor 🙏.</p>
            <p>
              Make a custom one time or recurring contribution to support my
              open source projects
            </p>
            <a
              href="https://opencollective.com/vue-boilerplates"
              rel="noopener"
              target="_blank"
              class="btn btn-success"
            >
              Donate
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.block {
  margin: 3rem 2rem 3rem 2rem;
}
h1,
h2 {
  margin: 0;
}
h3 {
  margin-top: 0.5rem;
}
img {
  margin-bottom: 1rem;
}
.donate-btn {
  display: inline-block;
  font-weight: 400;
  text-align: center;
  vertical-align: middle;
  color: #fff;
  background-color: #1e7e34;
  border-color: #1c7430;
  cursor: pointer;
  user-select: none;
  border: 1px solid transparent;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  text-decoration: none;
}
.donate-btn:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}
</style>
