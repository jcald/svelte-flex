<script>
  export let color = "lime";
</script>

<style>
  div {
    border: 2px dotted #333;
    height: 60px;
    width: 60px;
  }
  .lime {
    background: lime;
  }
  .blue {
    background: #00aacc;
    height: 80px;
  }
  .red {
    background: #ff6666;
  }
</style>

<div class={color}>
  {color}
</div>