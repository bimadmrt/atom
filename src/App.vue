<template>
<html>
  <body>
    <div class="my-jumbotron container" id="my-jumbotron">
      <nav class="navbar flex items-center">
        <a href=""><img src="./pictures/yahoo.png" width="250px" height="100px" class="navbar-brand p-6"/></a>
        <input class="shadow appearance-none  rounded w-1/2 h-12 py-2 px-3 text-black leading-tight focus:outline-none "
         id="username" type="text">
         <button class="bg-blue-400 w-32 h-12 py-2 px-3">
           <img src="./pictures/search.png" class="w-6 p-auto m-auto">
         </button>
         <button class="bg-transparent hover:bg-purple-700 text-xs w-20 text-purple-700 font-bold p-2 ml-56 hover:text-white py-2 px-3 border-2 border-purple-700 hover:border-transparent rounded">
          Sign In
         </button>
         <a href=""><img src="./pictures/notification.png" class = "w-10 h-10 p-1 ml-5 p-2"></a>
         <a href=""><img src="./pictures/mail.png" class="w-10 p-1 ml-5 p-2"></a>
         <p class="font-bold p-2" style="color: #4D00AE;">Mail</p>
      </nav>
    </div>
    <div class="my-jumbotron container" id="my-jumbotron">
      <nav class="navbar flex items-center">
        <a href=""><img src="./pictures/mail.png" class="w-10 p-1 ml-5"></a>
        <a href=""><p class="font-bold" style="color: #4D00AE;">Mail</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #4D00AE;">Mail</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #4D00AE;">Berita</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #4D00AE;">Olahraga</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #4D00AE;">Hiburan</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #4D00AE;">Keuangan</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #4D00AE;">Lifestyle</p></a>
        <a href=""><p class="font-bold ml-8" style="color: #4D00AE;">Teknologi</p></a>
      </nav>
    </div>
    <div class="grid grid-rows-3 grid-flow-col gap-4">
      <div class="row-span-3 p-1 mb-1"><img src="./pictures/coronavirus.jpg"></div>
      <div class="row-span-1 col-span-2">
        <p class="font-bold text-blue-500">Berita</p>
        <a href=""><p class="font-bold text-purple-700 hover:text-blue-500">COVID-19 Tembus Angka 5000 Jiwa Positif</p></a>
        <p>Pasien yang positif terinfeksi virus corona (Covid-19) bertambah 297 orang per 15 April 2020. Total yang terinfeksi mencapai 5.136 kasus. Kasus kematian bertambah 10 orang menjadi 469, sedangkan pasien yang sembuh meningkat 20 orang menjadi 446 dibandingkan hari sebelumnya. </p>
      </div>
      <div class="row-span-2 col-span-1 mb-1">
        <div class="bg-orange-100 border-l-4 border-orange-500 text-orange-700 p-4" role="alert">
          <p class="font-bold">Peringatan</p>
          <p>Dilarang Keluar Rumah Selain Untuk Memenuhi Kebutuhan Pokok</p>
        </div>
      </div>
    </div>
  </body>
</html>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
