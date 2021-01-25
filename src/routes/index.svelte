<script>
	import Konten from '../components/Card.svelte'
	import Artikel from './artikel/index.svelte';
</script>

<style>
	.judul{
		color: rgb(185, 19, 19);
	}
</style>

<svelte:head>
    <title>Marikang</title>
</svelte:head>

<div class="welcome-area" id="welcome">
	<div class="header-text">
		<div class="container">
			<div class="row">
				<div class="offset-xl-3 col-xl-6 offset-lg-2 col-lg-8 col-md-12 col-sm-12">
					<h1>Mari Membangun<br>Bersama <strong class="judul">MARIKANG</strong></h1>
				</div>
			</div>
		</div>
	</div>
</div>

<center>
	<section class="section home-feature">
		<div class="container"> 
			<div class="row">
				<div class="col-lg-12">
					<div class="row">
						<Konten />
					</div>
				</div>
			</div>
		</div>
	</section>
</center>

<section class="section padding-top-70 padding-bottom-0" id="features">
	<div class="container">
		<div class="row">
			<div class="col-lg-5 col-md-12 col-sm-12 align-self-center" data-scroll-reveal="enter left move 30px over 0.6s after 0.4s">
				<img src="assets/images/left-image.png" class="rounded img-fluid d-block mx-auto" alt="App">
			</div>
			<div class="col-lg-1"></div>
			<div class="col-lg-6 col-md-12 col-sm-12 align-self-center mobile-top-fix">
				<div class="left-heading">
					<h2 class="section-title">Layanan <strong class="judul">MARIKANG</strong></h2>
				</div>
				<div class="left-text">
					<div class="row">
                        <div class="col-md-10 icon-box" data-aos="fade-up">
                            <h4>Perbaikan</h4>
                            <p>Memberikan layanan dengan menyesuaikan kebutuhan perbaikan tertentu pada bangunan berskala kecil. Perbaikan yang dapat diselesaikan dalam satu hari atau singkat</p>
                        </div>
                        <div class="col-md-10 icon-box" data-aos="fade-up" data-aos-delay="100">
                            <h4>Renovasi & Bangun</h4>
                            <p>Memberikan layanan dengan menyesuaikan kebutuhan pembangunan skala besar yang dikerjakan. Renovasi dan Bangun diselesaikan dalam kurung waktu jangka panjang</p>
                        </div>
                        <div class="col-md-10 icon-box" data-aos="fade-up" data-aos-delay="200">
                            <h4>Survei Lokasi & Konsultasi</h4>
                            <p>Survei Lokasi & Konsultasi ini merupakan layanan yang kami berikan guna mengetahui situasi lokasi dan memperhitungkan berapa banyak biaya yang harus dikeluarkan Client</p>
                        </div>
                    </div>
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col-lg-12">
				<div class="hr"></div>
			</div>
		</div>
	</div>
</section>

<section class="section padding-bottom-100">
	<div class="container">
		<div class="row">
			<div class="col-lg-6 col-md-12 col-sm-12 align-self-center mobile-bottom-fix">
				<div class="left-heading">
					<h2 class="section-title">Cara Kerja <strong class="judul">MARIKANG</strong></h2>
				</div>
				<div class="left-text">
					<ul>
						<li><i ></i> Pilih tukang sesuai pekerjaan.</li>
						<li><i ></i> Tekan tombol WA setelah menentukan tukang yang sesuai.</li>
						<li><i ></i> Akan masuk ke WA admin Marikang (muncul template chat seperti Nama, Alamat, Pekerjaan) yang harus di isi oleh customer.</li>
						<li><i ></i> Lalu Tim Marikang akan menanyakan kapan kunjungan atau survei lokasi.</li>
						<li><i ></i> Dilokasi Tim akan mengecek berapa bahan dan biaya yang harus di bayarkan oleh customer.</li>
						<li><i ></i> Ketika sudah Deal, Tim akan mengerjakan sesuai kesepakatan bersama.</li>
					</ul>
				</div>
			</div>
			<div class="col-lg-1"></div>
			<div class="col-lg-5 col-md-12 col-sm-12 align-self-center mobile-bottom-fix-big" data-scroll-reveal="enter right move 30px over 0.6s after 0.4s">
				<img src="assets/images/right-image.png" class="rounded img-fluid d-block mx-auto" alt="App">
			</div>
		</div>
	</div>
</section>

<section class="section" id="blog">
	<div class="container">
		<Artikel />
	</div>
</section>
