<script lang="ts">
	// Napiši funkcijo, ki kot argument sprejme seznam števil in kot rezultat vrne njihov zmnožek.
	// V primeru, da je seznam prazen, naj funkcija vrne 0.

	let seznam: number[] = [4, 5, 1, 489];
	let prazenSeznam: number[] = [];
	function zmnozi(stevila: number[]) {
		let result = 1;
		for (let i = 0; i < stevila.length; i++) {
			const element = stevila[i];
			result = result * element;
		}
		if (stevila.length == 0) {
			return 0;
		} else {
			return result;
		}
	}

	console.log(zmnozi(seznam)); // Test klica funkcije
	console.log(zmnozi(prazenSeznam)); // Test klica funkcije
</script>

<code
	><pre>
	// Napiši funkcijo, ki kot argument sprejme seznam števil in kot rezultat vrne njihov zmnožek.
	// V primeru, da je seznam prazen, naj funkcija vrne 0.
</pre></code
>
<hr />
<p class="text-xl">Test seznam: {zmnozi(seznam)}</p>
<p class="text-xl">Test prazen seznam: {zmnozi(prazenSeznam)}</p>
