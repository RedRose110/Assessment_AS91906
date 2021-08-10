<script>
  let name = ''
  let form = ''

</script>

<label>
  Name: 
  <input bind:value={name}>
  Class: 
  <input bind:value={form}>
</label>

<h1>Welcome {name} from class </h1>