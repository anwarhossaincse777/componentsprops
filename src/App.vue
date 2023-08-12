<script setup>
import ListComponent from "./components/ListComponent.vue";

const item1={

        title:'The Magnificent Bogra',
        para:'Located in Rajshahi Division, Bogra is one of the oldest and most fascinating towns in Bangladesh',
        distance:'196',
        review:'5',
        image:"https://i.ibb.co/Kr4b0zJ/152013403-10158311889099633-8423107287930246533-5.jpg"
}


</script>

<template>
  <section class="mx-auto ">
    <h1 class="my-10 text-center">Components</h1>
    <div class="flex flex-col space-y-5">
      <ListComponent v-bind="item1"/>
     <ListComponent title="The Magnificent Bogra" image="https://i.ibb.co/Kr4b0zJ/152013403-10158311889099633-8423107287930246533-o.jpg" para="Located in Rajshahi Division, Bogra is one of the oldest and most fascinating towns in Bangladesh" distance="196" :review="5"/>


    </div>

  </section>
</template>

<style scoped>

</style>
