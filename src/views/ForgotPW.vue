<template>
  <div
    class="vue-tempalte"
    style="
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 3vw;
    "
  >
    <form>
      <h3>Forgot Password</h3>

      <div class="form-group">
        <label>Email address</label>
        <input type="email" class="form-control form-control-lg" />
      </div>

      <button type="submit" class="btn btn-dark btn-lg btn-block">
        Reset password
      </button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>