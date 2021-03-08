<script>
  import Flex from "svelte-flex";
  import Box from "./Box.svelte";
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
    margin: 1rem auto;
    min-width: 420px;
    width: 50%;
  }
  hr {
    margin: 1rem auto;
    border: 0;
    border-bottom: 2px dotted #333;
  }
</style>

<main>
  <h1>svelte-flex</h1>
  <p>Play around with some <a href="https://github.com/himynameisdave/svelte-flex" target="_blank">svelte-flex</a> examples.</p>
  <hr />
  <h2>Default:</h2>
	<Flex>
    <Box color="lime" />
    <Box color="blue" />
    <Box color="red" />
	</Flex>
  <hr />
  <h2>direction="column"</h2>
  <Flex direction="column">
    <Box color="lime" />
    <Box color="blue" />
    <Box color="red" />
	</Flex>
  <hr />
  <h2>align="start"</h2>
  <Flex align="stretch">
    <Box color="lime" />
    <Box color="blue" />
    <Box color="red" />
	</Flex>
  <hr />
  <h2>justify="end"</h2>
  <Flex justify="end">
    <Box color="lime" />
    <Box color="blue" />
    <Box color="red" />
	</Flex>
</main>