<script>
    let tukangBangunan = [
        {domisiliTukang: 'Kabat', linkTukang:'caritukang/detailtukang1', fotoTukang:'assets/images/Tukang1.jpeg', namaTukang:'Abd. Hakim', keahlianTukang:'Cat Dinding, Pasang Atap, Pasang Kramik'},
        {domisiliTukang: 'Kabat', linkTukang:'caritukang/detailtukang2', fotoTukang:'assets/images/IMG-20201024-WA0022.jpg', namaTukang:'Busairi', keahlianTukang:'Kepala Tukang'},
        {domisiliTukang: 'Kabat', linkTukang:'caritukang/detailtukang3', fotoTukang:'assets/images/IMG-20201024-WA0023.jpg', namaTukang:'Eko Wahyudi', keahlianTukang:'Cat dan Las'}
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
  width: 100%;
}

</style>
{#each tukangBangunan as tB}
    <div id="{tB.domisiliTukang}" class="col-lg-4 col-md-6 col-sm-12" style="display: block;" data-scroll-reveal="enter bottom move 50px over 0.6s after 0.4s">
        <div class="pricing-item">
            <div class="pricing-header">
                <center>
                    <div id="frame-ig">
                        <img src="{tB.fotoTukang}" class="align-self-center tko" alt="">
                    </div>
                    <h2 class="pricing-title">{tB.namaTukang}</h2>
                </center>
            </div>
            <div class="pricing-body">
                <ul class="list">
                    <li class="active">Kec. {tB.domisiliTukang}, Kab. Banyuwangi</li>
                    <li class="active">Spesialis : {tB.keahlianTukang}</li>
                </ul>
            </div>
            <div class="pricing-footer">
                <a href="{tB.linkTukang}" class="main-button">Detail Tukang</a>
            </div>
        </div>
    </div>   
{/each}
