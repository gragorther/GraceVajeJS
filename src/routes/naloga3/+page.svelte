<script lang="ts">
	// Napiši funkcijo, ki kot argument sprejme seznam števil in vrne nov seznam, ki vsebuje samo liha števila.
	let stevila: number[] = [10, 15, 20, 25, 30, 35];
	function filtrirajLiha(stevila: number[]) {
		let arr: number[] = stevila.filter((number) => number % 2 !== 0);
		return arr;
	}

	console.log(filtrirajLiha(stevila)); // Pričakovani rezultat: [15, 25, 35]
</script>

<code>
	<pre>// Napiši funkcijo, ki kot argument sprejme seznam števil in vrne nov seznam, ki vsebuje samo liha števila.</pre>
</code>
<hr />
<p class="text-xl">Celoten seznam: 10, 15, 20, 25, 30, 35</p>
<p class="text-xl">Filtriran seznam: {filtrirajLiha(stevila)}</p>
