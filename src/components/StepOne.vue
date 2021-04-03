<template>
  <div class="mt-16 bg-gray-100">
    <div class="px-40">
      <div class="text-center">
        <p class="text-darkblue text-2xl font-bold mb-3">APA ITU KARTU PRAKERJA?</p>
        <hr class="step-hr" />
      </div>
      <div class="text-center mt-8">
        <p>Kartu Prakerja adalah program <b>pengembangan kompetensi berupa bantuan biaya</b> <br />yang ditujukan untuk pencari kerja, pekerja ter-PHK atau pekerja yang membutuhkan peningkatan kompetensi.</p>
      </div>
      <div class="text-center mt-8">
        <button class="border border-darkblue rounded-md px-4 py-1 text-darkblue">Baca lebih lanjut</button>
      </div>
    </div>
    <div class="step-content mt-16 h-full">
      <div class="py-8 text-center">
        <p class="text-darkblue text-2xl font-bold mb-3 mt-4">7 TAHAP PROGRAM KARTU PRAKERJA</p>
        <hr class="step-hr" />
      </div>
      <div class="center item-center text-center">
        <div class="step-video">
          <img src="https://www.prakerja.go.id/images/7-tahap-kartu-prakerja.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'StepOne',
  setup(){
    var isVideo = true
    var counter = 11

    return { isVideo, counter, showImage, tambah }
    function showImage() {
      // isVideo = true
      console.log(counter)
    }

    function tambah(){
      counter= counter+1
    }
  }
}
</script>

<style scoped>
.step-hr {
  border: 1px solid #ffd629;
  width: 100px;
  margin: auto;
}

.step-content {
  background: url("https://www.prakerja.go.id/images/7-steps-background.png");
  background-size: cover;
  position: relative;
  background-position-x: left;
  background-repeat: no-repeat;
  background-color: #e9f2fe;
  min-height: 120px;
}

.step-video {
  width: 540px;
  /* background: cadetblue; */
  margin: auto;
  background: url('https://www.prakerja.go.id/images/7-tahap-kartu-prakerja.png');
  cursor: pointer;
}
</style>