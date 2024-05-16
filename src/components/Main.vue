<script setup>
    import buttonm from './Butemit.vue'

const childmsg = ref('tidak ada pesan')

import { ref } from 'vue';
function ubahTeks(msg) {
    childmsg.value = msg
    alert('ALERT : ' + msg)
}
</script>
<template>
    <div class="wrappermain">
        <div class="sec a1">
            <div class="b">
                <div class="isi">
                    <h3>Rumah Sakit Mitra Keluarga Group</h3>
                    <img src="../assets/hospital-building.png" class="gambar" alt="">
                    <buttonm @response="ubahTeks" />
                </div>
            </div>
        </div>
        <div class="sec a2">
            <div class="b">
                <div class="isi">
                    <h3>Siloam Hospitals Group</h3>
                    <img src="../assets/hospital-building.png" class="gambar" alt="">
                    <buttonm @response="ubahTeks" />
                </div>
            </div>
        </div>
        <div class="sec a3">
            <div class="b">
                <div class="isi">
                    <h3>Rumah Sakit Dr. Oen Surakarta</h3>
                    <img src="../assets/hospital-building.png" class="gambar" alt="">
                    <buttonm @response="ubahTeks" />
                </div>
            </div>
        </div>
        <div class="sec a4">
            <div class="b">
                <div class="isi">
                    <h3>Bali International Medical Centre Hospital</h3>
                    <img src="../assets/hospital-building.png" class="gambar" alt="">
                    <buttonm @response="ubahTeks" />
                </div>
            </div>
        </div>
        <div class="sec a5">
            <div class="b">
                <div class="isi">
                    <h3>Rumah Sakit Bunda Jakarta</h3>
                    <img src="../assets/hospital-building.png" class="gambar" alt="">
                    <buttonm @response="ubahTeks" />
                </div>
            </div>
        </div>
    </div>
</template>
<style>
.wrappermain {

  height: 100%;
  display: flex;
  justify-content: space-around;
}
.sec {
 width: 300px;
 color: aliceblue;
 background: rgba(0, 0, 0, 0.6);
 backdrop-filter: blur(5px);
 border-radius: 20px;
  align-items: center;
  padding-top: 40px;
}
.isi{
    height: 100%;
    display: flex;
    align-items: center;
    text-align: center;
    flex-direction: column;
    justify-content: space-between;
    padding-bottom: 100px;
}
.gambar{
    height: 40%;
}
button{
    scale: 2.5;
}
.b{
    height: 100%;
}

</style>
