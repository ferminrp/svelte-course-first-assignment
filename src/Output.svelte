
<script>
    export let courseGoal;
</script>

<h1 class:red="{courseGoal.includes('!')}"> {courseGoal}</h1>

<style>

  .red {
    color: red;
  }

</style>