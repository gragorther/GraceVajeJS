<script lang="ts">
	// Napiši funkcijo, ki vrne preveri besedo in vrne slovar z vsemi črkami in število pojavitev.
	function steviloPojavitev(beseda: string) {
		let rezultat: Record<string, number> = {};
		beseda.split('').forEach((element) => {
			if (element in rezultat) {
				rezultat[element] = rezultat[element] + 1;
			} else {
				rezultat[element] = 1;
			}
		});
		return rezultat;
	}

	console.log(steviloPojavitev('banana'));
	// Pričakovani rezultat: { b: 1, a: 3, n: 2 }
</script>

<code
	><pre>
  // Napiši funkcijo, ki vrne preveri besedo in vrne slovar z vsemi črkami in število pojavitev.
</pre></code
>
<hr />
<p class="text-xl">Za testiranje odpri konzolo.</p>
