<script lang="ts">
	// Napiši funkcijo, ki preveri, ali je niz palindrom (se bere enako naprej in nazaj).
	function reverse(s: string) {
		return s.split('').reverse().join('');
	}
	function jePalindrom(niz: string) {
		return reverse(niz) == niz;
	}

	console.log(jePalindrom('kajak')); // Pričakovani rezultat: true
	console.log(jePalindrom('hello')); // Pričakovani rezultat: false
</script>

<code>
	<pre>// Napiši funkcijo, ki preveri, ali je niz palindrom (se bere enako naprej in nazaj).</pre>
</code>
<hr />
<p class="text-xl">ali je 'kajak' palindrom: {jePalindrom('kajak')}</p>
<p class="text-xl">ali je 'ananas' palindrom: {jePalindrom('ananas')}</p>
