<script lang="ts">
  export let question: string = "there is no question";
  let userInput: string = "slap some text here";
</script>

<!-- prevent default -->
<form>
  <p>{question}</p>
  <input type="text" bind:value={userInput} />
  <button type="submit">submit</button>
</form>
