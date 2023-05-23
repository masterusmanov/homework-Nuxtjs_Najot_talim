<script setup>

</script>

<template>
  <section>
    <div class="container mx-auto">
        <div class="flex mx-auto justify-center mt-10 items-center">
            <div class="w-1/2">
                <h1>Bosh sahifa ->  <nuxt-link to="#" class="text-yellow-800">Kurslar</nuxt-link></h1>
                <h1 class="text-3xl mt-10 font-bold">Barcha o‘quv kurslari</h1>
                <button class="p-4 rounded-full mt-10 bg-yellow-600 text-white hover:bg-gray-400 hover:text-black">Barchasi</button>
                <button class="p-4 rounded-full ml-10 bg-yellow-600 text-white hover:bg-gray-400 hover:text-black">Dasturlash</button>
            </div>
            <div class="w-1/2">
                <input type="text" placeholder="Izlash" class="flex mb-7 ml-[50%] w-[50%] h-[50px] pl-10 rounded-full border ">
                <img src="../../images/search.png" alt="Izlash" class="absolute ml-[37%] mt-[-73px]">
            </div>
        </div>
    </div> 
  </section>
  <section>
        <div class="container mx-auto mt-14">
            <div class="flex p-5 justify-center items-center">
                <div class="w-1/2 bg-gray-200 p-5 pt-10">
                    <nuxt-link to="#" class="p-3 text-xl pl-4 pr-4 bg-gray-400 rounded-full">Dasturlash</nuxt-link>
                    <nuxt-link to="#" class="p-3 text-xl text-yellow-700 ml-5">Davomiylik: 19 soat 24 daqiqa</nuxt-link>
                    <nuxt-link to="#" class="p-3 text-xl text-yellow-700 ml-5">Darslar soni: 126 ta</nuxt-link>
                    <div class="flex justify-center items-center mt-5">
                        <div class="w-1/2">
                            <h1 class="font-bold text-3xl">Dasturlash foundation</h1>
                            <p class="mt-5 text-justify text-xl">Foundation dasturlash kursida C va Python
                                dasturlash tillari va ular orqali dasturlashning
                                mantiq-mohiyati o’rgatiladi. Kurs davomida
                                dasturlashning fundamental tushunchalari,
                                dasturchining ishini yengillashtirib beradigan</p>
                        </div>
                        <div class="w-1/2">
                            <img src="../../images/kompyuter.png" alt="kompyuter" class="w-[90%] ml-10 h-[90%]">
                        </div>
                    </div>
                </div>
                <div class="w-1/2 ml-14 bg-gray-200 p-5 pt-10">
                    <nuxt-link to="#" class="p-3 text-xl pl-4 pr-4 bg-gray-400 rounded-full">Dasturlash</nuxt-link>
                    <nuxt-link to="#" class="p-3 text-xl text-yellow-700 ml-5">Davomiylik: 23 soat 7 daqiqa</nuxt-link>
                    <nuxt-link to="#" class="p-3 text-xl text-yellow-700 ml-5">Darslar soni: 93 ta</nuxt-link>
                    <div class="flex justify-center items-center mt-5">
                        <div class="w-1/2">
                            <h1 class="font-bold text-3xl">.NET mutaxassislik kursi</h1>
                            <p class="mt-5 text-justify text-xl">.NET mutaxassislik kursi yordamida universal
                                C# dasturlash tilida ishlovchi va oʻz faoliyatida
                                .NET platformasi va texnologiyalaridan
                                foydalanuvchi dasturchiga aylaning. C#
                                dasturlash tilining imkoniyatlari va qoʻllash</p>
                        </div>
                        <div class="w-1/2">
                            <img src="../../images/komp.png" alt="kompyuter" class="w-[90%] ml-10 h-[90%]">
                        </div>
                    </div>
                </div>
            </div>
        </div>
  </section>
</template>

<style lang="scss" scoped>
</style>