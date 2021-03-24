<template>
  <div>
    <NavBar />
    <div class="row mx-0">
      <div class="col-12 col-md-6 order-2 order-md-1 px-4 px-md-0 py-2">
        <img src="./assets/vector.png" alt="Vector" width="100%">
      </div>
      <div class="col-12 col-md-6 order-1 order-md-2">
      <Form/>
      </div>
    </div>
    <Footer/>
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import Form from "./components/Form";
import Footer from "./components/Footer";
export default {
  components: { NavBar, Form , Footer },
};
</script>
