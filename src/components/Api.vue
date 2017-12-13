<template>
  <div>
    <b-container fluid>
      <b-row>
        <b-col cols="2" class="fixed-top bg-light h-100 mt-5 pt-5">
          <h6>
            Documentation
          </h6>
          <div>
            Requests
          </div>
          <div>
            Responses
          </div>
        </b-col>
        <b-col cols="5" class="ml-auto mt-5 pt-5 pb-4 bg-dark">
        </b-col>
        <b-col cols="5" class="bg-light mt-5 pt-5 pb-4">
          <prism language="javascript" class="bg-light">
            let monkey = (a, b) => {
              return a + b;
            }
          </prism>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>

  import 'prismjs';
  import 'prismjs/themes/prism.css';
  import Prism from 'vue-prism-component';

  export default {
    name: 'Api',
    components: {
      Prism
    }
  };
</script>

<style scoped>
</style>
