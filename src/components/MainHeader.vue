<template>
  <div class="header">
    <img src="../assets/Airbnb-logo.jpg" alt="airbnb logo" width="120px" height="auto">
    <form>
    <input type="text" placeholder="Search" >
    <button type="submit">Search</button>
    </form>
    <div class="header-right">
      <a href="#">Become a host</a>
      <a href="#">Help</a>
      <a href="#">Sign up</a>
      <a href="#">Log in</a>
      <img src="../assets/social-media-chatting-online-blank-profile-picture-head-and-body-icon-people-standing-icon-grey-background-free-vector.jpg" alt="profile" width="40px" height="auto" id="profile">
    </div>
  </div>
</template>

<script>
export default {
  }
</script>

<style scoped>
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 5px;
  border-bottom: 1px solid lightgrey;
  top:0;
  position: sticky;
  background-color: white;
}


img {
  margin-left: 10px;
}
.header-right {
  float: right;
  margin-right: 10px;
}
.header-right a {
  margin-left: 20px;
  text-decoration: none;
  color: black;
}
#profile {
  border-radius: 50%;
  margin-left: 30px;
}

button {
  text-indent: -999px;
  overflow: hidden;
  width: 40px;
  height: 40px;
  padding: 0;
  margin: 0;
  border: 1px solid transparent;
  border-radius: 50%;
  background: red url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' class='bi bi-search' viewBox='0 0 16 16'%3E%3Cpath d='M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z'%3E%3C/path%3E%3C/svg%3E") no-repeat center;
  cursor: pointer;
  opacity: 0.7;
}

input {
  border: none;
  background: transparent;
  margin: 0;
  padding: 7px 8px;
  font-size: 14px;
  color: inherit;
  border: 1px solid transparent;
  border-radius: inherit;
}

form {
  color: #555;
  display: flex;
  padding: 2px;
  border: 1px solid currentColor;
  border-radius: 50px;
  margin: 10px 0 0px;
}

</style>
