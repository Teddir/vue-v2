<template>
  <div>
    <!-- Image and text -->
    <nav class="navbar navbar-light bg-primary">
      <div class="div" style="display:flex;width:100%; margin-left:30px">
        <a class="navbar-brand" href="#">
          <img
            src="../assets/logo.svg"
            width="100%"
            height="30"
            class="d-inline-block align-top"
            alt=""
          />
        </a>
        <form class="form-inline" style="display:flex;width:100%;margin-left:12px">
          <input
            class="form-control "
            type="search"
            placeholder="Search"
            aria-label="Search"
          />
        </form>
      <div style="width:8%; justify-content:center;display:flex;align-items:center;margin-right:30px">
        <font-awesome-icon :icon="['fas', 'ellipsis-v']" style="margin-right:12px;color:white;width:24"/>
        <font-awesome-icon :icon="['fas', 'cart-plus']" style="color:white;width:24"/>
      </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
