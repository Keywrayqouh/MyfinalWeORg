<template>
  <div class="head">
    <v-layout align-center justify-center>
      <nav class="navbar navbar-expand-lg fixed-top row">
        <router-link tag="li" class="col" class-active="active" to="/" exact>Home</router-link>
        <router-link tag="li" class="col" class-active="active" to="/About" exact>About</router-link>
        <router-link tag="li" class="col" class-active="active" to="/Category" exact>Category</router-link>
        <router-link tag="li" class="col" class-active="active" to="/Login" exact>Login</router-link>
        <router-link tag="li" class="col" class-active="active" to="/Signup" exact>Signup</router-link>
        <div>
          <b-dropdown id="dropdown-buttons" text="Category" class="m-6">
           
            <router-link tag="li" active-class="active" class="dp" to="/BurialCategory">
              <a>Burial</a>
            </router-link>
            <router-link tag="li" active-class="active" class="dp" to="/WeddingCategory">
              <a>Wedding</a>
            </router-link>
             <router-link tag="li" active-class="active" class="dp" to="/BirthdayCategory">
              <a>Birthday</a>
            </router-link>
            <router-link tag="li" active-class="active" class="dp" to="/BaptistCategory">
              <a>Baptist</a>
            </router-link>
          </b-dropdown>
        </div>
        <form class="form-inline">
          <input class="form-control mr-sm-5" type="text" placeholder="Search">
          <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
      </nav>
    </v-layout>
  </div>
</template>

<script>
export default {
  name: "header",
  data() {
    return {};
  }
};
</script>
<style>
nav {
  list-style-type: none;

  padding: 0;
  width: 100%;
  background-color: #f1f1f1;
}
nav li {
  display: block;
  color: #000;
  padding: 10px 20px;
  width: 50%;
  text-decoration: none;
}
nav li:hover,
nav li:active {
  background-color: #555;
  color: white;

  cursor: pointer;
}
.form-control {
  width: 20%;
}
.head {
  width: 100%;
  margin:0;
}
.dp {
  width: 100%;
}
</style>

