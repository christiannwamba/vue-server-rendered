
<template>
    <section>
      <div class="container h-100">
            <div class="row h-100 justify-content-center align-items-center">
              <div>
                <p>Fictional e-commerce store  </p>
                <p><em>Home of bespoke and modern wears</em></p>
              </div>  
            </div>
          </div>
    </section>
  </template>
  <script>
  import AppLogo from "~/components/AppLogo.vue";
  export default {
    components: {
      AppLogo
    }
  };
  </script>
  <style>
  .container {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }
  </style>