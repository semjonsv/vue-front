<template>
  <footer class="bg-light">
    <b-row>
      <b-col>
        © 2020 Name |
        <a href="#" class="danger"><b-icon-envelope></b-icon-envelope> any questions?</a>
      </b-col>
    </b-row>
  </footer>
</template>

<style scoped lang="scss">
  //scss file with variables
  $custom_danger : #fb3333;
  $custom_danger_hover : #fb2218;

  div {
    font-size: 15px;
  }
  a {
    color: $custom_danger;
  }
  a:hover {
    color: $custom_danger_hover;
    text-decoration: none;
  }
</style>