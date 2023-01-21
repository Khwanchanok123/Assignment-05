<script setup>
import PhotoCard from "./components/PhotoCard.vue";
</script>

<template>
  <header>
    <div class="navbar navbar-dark shadow-sm"  style = "background-color: #673ab7">
      <div class="container d-flex justify-content-between">
        <a class="navbar-brand d-flex align-items-center" href="#"
          ><i class="fa fa-camera"></i><strong>&nbsp; MyAlbum&#128151;</strong></a
        >
      </div>
    </div>
  </header>
  <main role="main">
    <section class="jumbotron text-center" style="background-color: #ede7f6">
      <div class="container" style = "background-color: #ede7f6">
        <h1><font color="#d81b60">My Sweet Photo&#128156;</font></h1>
        <p class="lead text-muted">
          <br /><font color=“#311b92”>Do you like any photo?</font><br />
        </p>
      </div>
    </section>
    <div class="album py-5 " style = "backgroung-color: #d1c4e9">
      <div class="container" style = "backgroung-color: #d1c4e9" >
        <div class="row" style = "backgroung-color: #d1c4e9">
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/320217759_1866039533740814_8502229558561543797_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeF58IVzLcHRwVrcVCSaTxR5ym-J28AdJt3Kb4nbwB0m3Rdnbny_tbfbHdCFTB63VQ02ZdLYIfmeJGDVtSr4mrAi&_nc_ohc=udm-RbMjwOwAX91FYAT&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdQ5FZ0lSwQasBwxBzh0gE7Mala1i6QzBgfFHd8h97u5qg&oe=63F34AC5" style="width: 200px; height 300px"/>
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/307291298_496457855286132_8132872497486712277_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeGhDlpcUE0msTm7_V51RUOG4ulssd8HXCni6Wyx3wdcKalHLNbVZ3_GVzC6_SQhsIy3JFevHqPeMLzJjUxa5DUF&_nc_ohc=qcEfTSFa9vkAX96fBKE&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdRLN6dmZD391G-wA4OuHwb5TRMpFgZdN45RinwsunV69w&oe=63F35E7F" style="width: 200px; height 300px"/>
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/324800189_908149920195586_144862656038527913_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeFNAwrpgrCw1Q67K5124fP0MTjlQ6gyJ7sxOOVDqDInu_fHe76uKxe1mkr_3QM0NzmtC8q5W61YOxUcMdqD7ht-&_nc_ohc=oph8hiX5ivoAX-rAxfT&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdSkq9JJzxYJ6uo2KSFoPSWh8USfbczVs2OitdKHEsAKAA&oe=63F32F5A" style="width: 200px; height 300px" />
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/319764864_2324778364346918_6026144885703964633_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeERTpdwJN7iqukGr5uzzj9-2GVrhaNJBOnYZWuFo0kE6QS1uA2RES4Zw4iDl1Z9CXMHMLW_aAZC767Dq2wjq1iP&_nc_ohc=Jati2I6glxsAX_IUKSR&tn=8Wkn9tY4XoUfN4Hn&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdRBUV5b9iO5c0zzMFWmZ87K4_S6DtLw07-WfGhKgDFM4Q&oe=63F335A4" style="width: 200px; height 300px"/>
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/301013686_1591555684580572_3156797087114535420_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeFyKKaHLGIbIGd-t5OTLr3cGc8HcGG3VOIZzwdwYbdU4uL12N7ICnVjENiiHFEKgv0x_aqtVt-gxZvyeQmy8MFf&_nc_ohc=xyv4q6AyAbIAX_XWj7e&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdRKLewGtgNHzvfvJuAlTvjghZjHjcIvQjcmTUYmrpbi-w&oe=63F353A5" style="width: 200px; height 300px" />
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/318981686_2142798279237315_6973124039928913392_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeFYubDPETccQ_bkW3QXby6l8AmLZOOyx_PwCYtk47LH86EKLI82rYxzIs3j7CXJfEytGY5IylX06w_azyz13uD_&_nc_ohc=e9UCzcNWTgsAX-dDlIG&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdSkJjtVlcX-nhIHosvXqOF6E2TBAlskC1KmRWWHNOrMWg&oe=63F35A12" style="width: 200px; height 300px"/>
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/323546212_714889776894115_5425471307312791513_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeFTCfkH0fEGz8maaK2ySukljc_MJBn4uH-Nz8wkGfi4fyr72uvWlsJfUKGQC5j0oJQtxyORFt78zgBw8uais5Ox&_nc_ohc=slObM5csIrsAX-iJHDn&_nc_oc=AQmtuSfgzzXQHZQ-gDpCENf7OlMPJ9T0lv9DjUzFEWbhIWWj24oOodua3Jf7i7GnY3PWvWgYZoepOZcD83tCtLNe&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdSFqi7g5BIsWRpkzHhnS2t5rEM_lYasFbfxNLMmk6483Q&oe=63F32A5A" style="width: 200px; height 300px"/>
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/318568258_905838870430049_3029368347849289213_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeF6VobZhM5p-jgRL4IJsYdcSlvqrm_yMyJKW-qub_IzIuVO-lrTBKaU0BA8dbiClwPvAgEwc6fQ1Yy5AV8lIsYa&_nc_ohc=f2nHT0Kb9CYAX_plVgp&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdSh2P3lGHI68rUhqILaXeVz15DDeJTvFhFprDmpudcMZQ&oe=63F35C1A" style="width: 200px; height 300px"/>
          <PhotoCard image="https://scontent.fcnx4-1.fna.fbcdn.net/v/t1.15752-9/320050154_710878640658721_8681979617129811003_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=ae9488&_nc_eui2=AeHdu63XwSxYbvnBip6dwxSdsonD67ngXU6yicPrueBdTuN4i02qqQXAKOv_7nxBqz1Q7xhKfOQe03ZfTBYIwakc&_nc_ohc=JBHwOLjmyLMAX_atffT&_nc_ht=scontent.fcnx4-1.fna&oh=03_AdTzN31E7WMphppTQMgTLXxqtf6o8L14cDVTjo1vBErG-Q&oe=63F356A2" style="width: 200px; height 300px"/>
        </div>
      </div>
    </div>
  </main>
  <footer class="text-muted">
    <div class="container">
      <p class="float-right"><a href="#">Back To Top</a></p>
      <p>
        Album example is &copy; Bootstrap, but please download and customize it
        for yourself!
      </p>
    </div>
  </footer>
</template>
<style scoped></style>
