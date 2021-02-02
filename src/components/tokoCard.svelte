<script>
    let TokoBangunan = [
        {domisiliToko: 'Singojuruh', linkToko:'caritoko/detailtoko1', fotoToko:'assets/images/IMG-20201024-WA0020.jpg', namaToko:'Luis Jaya 2', alamatToko:'Dsn. Karangasem, Ds. Alasmalang, Kec. Singojuruh, Kab. Banyuwangi'},
        {domisiliToko: 'Singojuruh', linkToko:'caritoko/detailtoko2', fotoToko:'assets/images/IMG-20201024-WA0017.jpg', namaToko:'Elaa Jaya', alamatToko:'Dsn. Krajan Ds. Padang Kec. Singojuruh'},
        {domisiliToko: 'Banyuwangi', linkToko:'caritoko/detailtoko3', fotoToko:'assets/images/IMG-20201024-WA0013.jpg', namaToko:'CV FIRDAUS', alamatToko:'JL. Gajah Mada No. 16'}
    ]

</script>

<style>
#frame-ig{
  width: 150px;
  height: 150px;
  overflow: hidden;
  position: relative;
}

#frame-ig .tko {
  position: absolute;
  left: 0px;
  top: -10%;
  height: 100%;
}

</style>
{#each TokoBangunan as tB}
    <div id="{tB.domisiliToko}" class="col-lg-4 col-md-6 col-sm-12" style="display: block;" data-scroll-reveal="enter bottom move 50px over 0.6s after 0.4s">
        <div class="pricing-item">
            <div class="pricing-header">
                <center>
                    <div id="frame-ig">
                        <img src="{tB.fotoToko}" class="align-self-center tko" alt="">
                    </div>
                    <h2 class="pricing-title">{tB.namaToko}</h2>
                </center>
            </div>
            <div class="pricing-body">
                <ul class="list">
                    <li class="active">{tB.alamatToko}</li>
                </ul>
            </div>
            <div class="pricing-footer">
                <a href="{tB.linkToko}" class="main-button">Detail Toko</a>
            </div>
        </div>
    </div>   
{/each}
