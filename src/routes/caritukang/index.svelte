<script>
    import DataTukang from './../../components/tukangCard.svelte'

    function cariTukang(){
            let x = document.getElementById("daftartukang").value;
            if(x == " "){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("mBanyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Bangorejo"){
                document.getElementById("Bangorejo").style.display = "block";
                document.getElementById("mBanyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Banyuwangi"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("mBanyuwangi").style.display = "block";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Cluring"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "block";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Gambiran"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "block";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Genteng"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "block";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Giri"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "block";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Glagah"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "block";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Glenmore"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "block";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Kabat"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "block";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Kalibaru"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "block";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Kalipuro"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "block";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Licin"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "block";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Muncar"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "block";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Pesanggaran"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "block";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Purwoharjo"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "block";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Rogojampi"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "block";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Sempu"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "block";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Siliragung"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "block";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Singojuruh"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "block";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Songgon"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "block";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Srono"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "block";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Tegaldlimo"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "block";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Tegalsari"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "block";
                document.getElementById("Wongsorejo").style.display = "none";
            }
            else if(x == "Wongsorejo"){
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "block";
            }
            else{
                document.getElementById("Bangorejo").style.display = "none";
                document.getElementById("Banyuwangi").style.display = "none";
                document.getElementById("Cluring").style.display = "none";
                document.getElementById("Gambiran").style.display = "none";
                document.getElementById("Genteng").style.display = "none";
                document.getElementById("Giri").style.display = "none";
                document.getElementById("Glagah").style.display = "none";
                document.getElementById("Glenmore").style.display = "none";
                document.getElementById("Kabat").style.display = "none";
                document.getElementById("Kalibaru").style.display = "none";
                document.getElementById("Kalipuro").style.display = "none";
                document.getElementById("Licin").style.display = "none";
                document.getElementById("Muncar").style.display = "none";
                document.getElementById("Pesanggaran").style.display = "none";
                document.getElementById("Purwoharjo").style.display = "none";
                document.getElementById("Rogojampi").style.display = "none";
                document.getElementById("Sempu").style.display = "none";
                document.getElementById("Siliragung").style.display = "none";
                document.getElementById("Singojuruh").style.display = "none";
                document.getElementById("Songgon").style.display = "none";
                document.getElementById("Srono").style.display = "none";
                document.getElementById("Tegaldlimo").style.display = "none";
                document.getElementById("Tegalsari").style.display = "none";
                document.getElementById("Wongsorejo").style.display = "none";
            }
        }
</script>

<style>

</style>

<section class="section colored" id="pricing-plans">
	<div class="container">
        <br>
        <br>
		<div class="row">
			<div class="col-lg-12">
				<div class="center-heading">
					<h2 class="section-title">Cari <strong>TUKANG BANGUNAN</strong></h2>
				</div>
			</div>
			<div class="offset-lg-3 col-lg-6">
				<div class="center-text">
					<p>Silahkan memilih lokasi anda saat ini atau yang terdekat dengan lokasi pembangunan anda saat ini.</p>
				</div>
            </div>            
        </div>
        <div class="row">
            <div class="col-lg-12">
                <form action="forms/contact.php" method="post" role="form" class="php-email-form" data-aos="fade-up">
                    <div class="form-group">
                        <!-- svelte-ignore a11y-no-onchange -->
                        <select class="form-control" data-rule="minlen:4" id="daftartukang" data-msg="Please enter at least 4 chars" on:change={cariTukang}>
                            <option value=" ">~pilih wilayah kecamatan~</option>
                            <option value="Bangorejo">Kecamatan Bangorejo</option>
                            <option value="Banyuwangi">Kecamatan Banyuwangi</option>
                            <option value="Cluring">Kecamatan Cluring</option>
                            <option value="Gambiran">Kecamatan Gambiran</option>
                            <option value="Genteng">Kecamatan Genteng</option>
                            <option value="Giri">Kecamatan Giri</option>
                            <option value="Glagah">Kecamatan Glagah</option>
                            <option value="Glenmore">Kecamatan Glenmore</option>
                            <option value="Kabat">Kecamatan Kabat</option>
                            <option value="Kalibaru">Kecamatan Kalibaru</option>
                            <option value="Kalipuro">Kecamatan Kalipuro</option>
                            <option value="Licin">Kecamatan Licin</option>
                            <option value="Muncar">Kecamatan Muncar</option>
                            <option value="Pesanggaran">Kecamatan Pesanggaran</option>
                            <option value="Purwoharjo">Kecamatan Purwoharjo</option>
                            <option value="Rogojampi">Kecamatan Rogojampi</option>
                            <option value="Sempu">Kecamatan Sempu</option>
                            <option value="Siliragung">Kecamatan Siliragung</option>
                            <option value="Singojuruh">Kecamatan Singojuruh</option>
                            <option value="Songgon">Kecamatan Songgon</option>
                            <option value="Srono">Kecamatan Srono</option>
                            <option value="Tegaldlimo">Kecamatan Tegaldlimo</option>
                            <option value="Tegalsari">Kecamatan Tegalsari</option>
                            <option value="Wongsorejo">Kecamatan Wongsorejo</option>
                        </select>
                    </div>
                </form>
            </div>
        </div>
		<div class="row">
            <p id="mBanyuwangi" style="display: none;">
                dzvdvdvs
            </p>
			<DataTukang />
		</div>
	</div>
</section>