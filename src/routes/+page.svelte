<script>
	/**
	 * Values & Variabel
	 */

	/**
	 * 
	 Value adalah nilai yang kita ciptakan

	 Variabel adalah tempat kita menyimpan nilai yang kita buat
	 Agar bisa dipakai kembali

	 */

	/**
	 * TIPS:

	 Variabel anggaplah sebagai kardus/wadah

	 Value sebagai jeruk, nangka yang mengisi wadah tsb.
	 */

	let first_name = 'Afochar';
	let last_name = 'Syabnirusmanto';

	/**
	 * TIPS:
	 
	 Kalau pingin lihat di console browser bisa dengan cara
	 console.log()
	*/

	console.log(first_name, last_name);

	// Console dengan cara object
	console.log({ first_name, last_name });
</script>

<!-- Tampilkan variabel di HTML -->
<p>Nama: {first_name + ' ' + last_name}</p>
