<template>
  <div class="subscribe-form">
      <div class="sidebarHeader">
          <header>Subscribe to our blog </header>
          <p> To get the latest and most quality design resources!</p>
      </div>
    <form class="form-inline my-2 my-lg-0">
      <input
        class="form-control mr-sm-2"
        type="email"
        placeholder="@gamil"
      />
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">
        sign up
      </button>
    </form>
    <p class="free-sign-up">Sign Up for Free </p>
  </div>
  
</template>
<script>

export default {
  name: "subscribeForm",
};
</script>
<style lang="scss" scoped>
    .subscribe-form{
        background-color: #f8f6f6;
        padding: 10px;
        margin: 10px 0px;
    }
    .sidebarHeader{
        margin: 5px 2px;
    }
    .sidebarHeader header{
        color: #b93131;
        font-size: 24px;
        font-weight: bold;
    }
    .free-sign-up{
        color: #22b522;
        margin: 10px;
        padding: 5px;
        font-size: 24px;
        font-weight: bold;
        background-color: #e4dedef7;
    }
</style>