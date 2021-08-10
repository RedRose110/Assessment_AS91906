<script>
  let name = ''
  let form = ''
  let check = ''
  let answer = ''

</script>

<label>
  Name: 
  <input bind:value={name}>
  Class: 
  <input bind:value={form}>
</label>

<h1>Welcome {name} from class {form} to the Marvel quiz</h1>

<p>
  What is Black Widow's real name?
</p>

<label>
	<input type=radio bind:group={answer} value ={true}>
	"Natasha Romanoff"
  <input type=radio bind:group={answer} value ={0}>
	"Marina Duyunova"
  <input type=radio bind:group={answer} value ={2}>
	"Gregovich Kuznetsov"
  <button on:click = {Check} id="check1">
	check
</label>
