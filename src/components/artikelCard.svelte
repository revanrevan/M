<!-- <script>
    import Artikel from "../routes/artikel.svelte";
    
        import { onMount } from "svelte";
    
        let arr_artikel = []
        async function getArtikel(){
            try {
                const data_artikel = await fetch('/rest-api/artikel')
                const resl = await data_artikel.json();
                arr_artikel = resl;
                console.log("oke");
            } catch (err) {
                console.log(err);
            }
        }
    
        onMount(function(){
            getArtikel();
        })
    </script>
    
    <style>
    
    </style>
     -->
    <!-- {#each arr_artikel as art}    
        <div class="col-lg-4 col-md-6 col-sm-12">
            <div class="blog-post-thumb">
                <div class="img">
                    <img src="assets/images/blog-item-01.png" alt="">
                </div>
                <div class="blog-content">
                    <h3>
                        <a href="/artikel/{art.id_artikel}">{art.judul_artikel}</a>
                    </h3>
                    <div class="text">
                    {@html art.isi_artikel}
                    </div>
                    <a href="/artikel/{art.id_artikel}" class="main-button">Read More</a>
                </div>
            </div>
        </div>
    {/each} -->

<script>
    let artikel = [
        {gambarArtikel:'assets/images/blog-item-01.jpg', linkArtikel:'detailArtikel1', judulArtikel:'Tips Membuat Kolam Renang Sendiri', isiArtikel:'Kolam renang bisa menjadi sarana olahraga yang sangat menyenangkan. Memiliki kolam renang pribadi di rumah dapat membantu Kalian mengurangi rasa stres karena membuat suasana di rumah menjadi nyaman dan sejuk. Selain itu, berenang bersama keluarga juga dapat mempererat keharmonisan antar anggota keluarga.'},
        {gambarArtikel:'assets/images/blog-item-02.png', linkArtikel:'detailArtikel2', judulArtikel:'9 Jenis Pipa Air Dan Fungsinya', isiArtikel:'Membangun rumah sendiri adalah impian setiap orang. Maka dari itu, perencanaan pembangunannya juga harus dipikirkan sematang mungkin agar hasilnya baik. Nah salah satu hal yang harus diperhatikan ketika membangun rumah adalah memilih jenis pipa air yang tepat untuk rumah. Ternyata banyak sekali jenis pipa air yang harus dikenali.'},
        {gambarArtikel:'assets/images/unnamed.jpg', linkArtikel:'detailArtikel3', judulArtikel:'PENGERTIAN & JENISJASA KERJA KONSTRUKSI', isiArtikel:'Di era modern saat ini, usaha bidang jasa konstruksi sangat dibutuhkan dalam pembangunan rumah, gedung kantor hingga fasilitas umum yang nantinya pemanfaatan bangunan tersebut menyangkut kepentingan, kebermanfaatan dan keselamatan masyarakat pemakai atau pemanfaat bangunan.'}
    ]
</script>

{#each artikel as art}    
    <div class="col-lg-4 col-md-6 col-sm-12">
        <div class="blog-post-thumb">
            <div class="img">
                <img class="foto" src="{art.gambarArtikel}" alt="">
            </div>
            <div class="blog-content">
                <h3>
                    <a href="/artikel/{art.linkArtikel}">{art.judulArtikel}</a>
                </h3>
                <div class="text">
                {art.isiArtikel}
                </div>
                <a href="/artikel/{art.linkArtikel}" class="main-button">Read More</a>
            </div>
        </div>
    </div>
{/each}
