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
	 
	 Kalau pingin ngeliat/ngeprint sesuatu di console browser bisa dengan cara
	 console.log()
	*/

	console.log(first_name, last_name);

	// Console dengan cara object
	console.log({ first_name, last_name });

	/**
	 * Larangan Dalam menulis variabel
	 *
	 * Beberapa larangan dalam menulis variabel diantaranya
	 * - Tidak boleh menggunakan karakter !@#$%^*()
	 * - Tidak boleh menggunakan method/variabel yang sudah digunakan JS, (new, const, class, let, dll)
	 * - Kalau bisa jangan mengawali penamaan dengan huruf kapital (A,B,C) karena menandakan class
	 *
	 * - Penamaan variabel hanya dapat diisi dengan nomor (123), letters(abc), underscores(_),
	 *    dan tanda dollar ($)
	 * - Pemberian nama dengan huruf kapital semua, merupakan cara untuk memberi nama variabel yang nilainya
	 *    tidak berubah
	 */

	const age_user = 23; // OK!
	const PI = 3.1415;

	// const let = 32 (Error: let is reserved / let sudah dipakai)
	// const address&zipcode = '321'

	/**
	 * TIPS:
	 * Untuk mengatasi penamaan variabel yang sudah dipakai kita bisa menambahkan dollar underscores (_)
	 * Di depan variabel yang sudah digunakan oleh javascript
	 */

	let _new = 'Halo Semuanya, Kenalkan';

	/**
	 * TIPS LAGI
	 * - Penamaan variabel haruslah deskriptif, agar mudah diingat dan langsung diketahui fungsinya
	 * -
	 */
	// const job1 = 'Barista' (kurang deskriptif)
	// const job2 = 'Programmer' (kurang deskriptif)

	const my_first_job = 'Programmer'; // Jelas dan deskriptif
	const my_current_job = 'Barista'; // Jelas dan deskriptif
</script>

<!-- Tampilkan variabel di HTML -->
<section class="flex flex-col items-start gap-4">
	<h5 class="text-2xl font-semibold">{_new}</h5>
	<div class="text-left">
		<p>Nama: {first_name + ' ' + last_name}</p>
		<p>Umur: {age_user}</p>
		<p>PI: {PI}</p>
		<p>Pekerjaan Awal: {my_first_job}</p>
		<p>Pekerjaan Sekarang: {my_current_job}</p>
	</div>
</section>
