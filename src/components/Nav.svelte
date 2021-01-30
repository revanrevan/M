<script>
	export let segment;

	let show = false
	const toggle = () =>{
		show = !show;
	}
</script>

<style>
	
</style>

<header class="header-area header-sticky">
	<div class="container">
		<div class="row">
			<div class="col-12">
				<nav class="main-nav">
					<a href=" " class="logo">
						<img src="/assets/images/logo.png" class="logoo" alt="Marikang"/>
					</a>
					<ul class="nav" style='display : {show ? "block" : "none"}'>
						<li><a aria-current="{segment === undefined ? 'page' : undefined}" href="/">Home</a></li>
						<li><a aria-current="{segment === 'caritoko' ? 'page' : undefined}" href="caritoko">Cari Toko Bangunan</a></li>
						<li><a aria-current="{segment === 'caritukang' ? 'page' : undefined}" href="caritukang">Cari Tukang</a></li>
						<li><a aria-current="{segment === 'artikel' ? 'page' : undefined}" href="artikel">Artikel</a></li>
					</ul>
					<a href=' ' class='menu-trigger {show ? "active" : ""}' on:click={toggle}>
						<span>Menu</span>
					</a>
				</nav>
			</div>
		</div>
	</div>
</header>
