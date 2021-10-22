<template>
<div class="bg-dark w-full h-full">
    <span class="text-xl sm:text-base xl:text-lg sm:absolute sm:top-4 sm:left-14 xl:left-28 flex justify-center mt-2 sm:mt-0 text-blue-400 font-medium">ToriFeed</span>
    <ul class="sm:absolute sm:top-4 right-14 xl:right-28 flex gap-6 justify-evenly mt-2 sm:mt-0 mb-2 sm:mb-0">
        <li class="opacity-90 hover:opacity-100 hover:underline hover:text-blue-300">Feutures</li>
        <li class="opacity-90 hover:opacity-100 hover:underline hover:text-blue-300">Who Am I?</li>
        <li class="opacity-90 hover:opacity-100 hover:underline hover:text-blue-3`00">Contact</li>
    </ul> 
    <div class="sm:mx-5 mb-14 sm:mt-16 h-auto max-w-full flex justify-center content-center items-center text-center gap-12 xl:gap-24 bg-blue-100 sm:rounded-2xl shadow-md">
        
            <div class="flex-col gap-10  my-10 mx-4">
                <h1 class="text-3xl xl:text-4xl sm:text-left mb-4 xl:mb-8 font-semibold max-w-sm">Make your Twitter experience better with me</h1>
                <p class="opacity-90 sm:text-left xl:text-lg max-w-sm">If you want to have early access suscribe now: </p>
            </div>
            <div class="hidden sm:inline my-10 mx-4 max-w-xl w-auto">
                <img class="w-64 h-64" src="../static/icons8-twitter.svg"/>
            </div>
    </div>
    <div class="text-center">
        <h2 class="text-2xl sm:text-3xl font-medium">Feutures</h2>
        <div class="flex flex-col sm:flex-row items-center gap-5 justify-center mt-5 sm:m-5">
            <div class="w-56 sm:w-80 xl:w-96 flex flex-col text-center justify-center items-center gap-3 sm:gap-5 xl:gap-8  py-5 px-3 sm:py-5 xl:py-8 bg-blue-100 border-b-4 border-yellow-200 hover:border-yellow-100 rounded-2xl shadow-xl hover:shadow-sm">
            <img src="../static/stats-svgrepo-com.svg" class="w-10 h-10"/>
            <h3 v-bind="h3" class="text-lg sm:text-xl xl:text-2xl">Growth and see</h3>
            <p v-bind="p" class="h-20">Get organize stats and inteligent comparisons to know more about your growth</p>
            </div>
            <div class="w-56 sm:w-80 xl:w-96 flex flex-col text-center justify-center items-center gap-3 sm:gap-5 xl:gap-8  py-5 px-3 sm:py-5 xl:py-8 bg-blue-100 border-b-4 border-yellow-200 hover:border-yellow-100 rounded-2xl shadow-xl hover:shadow-sm">
            <img src="../static/calendar-svgrepo-com.svg" class="w-10 h-10"/>
            <h3 v-bind="h3" class="text-lg sm:text-xl xl:text-2xl">Schedule better</h3>
            <p v-bind="p" class="h-20">I going to create a new way to schedule tweets using slots and multi editorial calendars</p>
            </div>
            <div class="w-56 sm:w-80 xl:w-96 flex flex-col text-center justify-center items-center gap-3 sm:gap-5 xl:gap-8  py-5 px-3 sm:py-5 xl:py-8 bg-blue-100 border-b-4 border-yellow-200 hover:border-yellow-100 rounded-2xl shadow-xl hover:shadow-sm">
            <img src="../static/easel-art-svgrepo-com.svg" class="w-10 h-10"/>
            <h3 v-bind="h3" class="text-lg sm:text-xl xl:text-2xl">Something with NFT´s</h3>
            <p v-bind="p" class="h-20">That is unexpected yet but in a future I will go to do something with that</p>
            </div>
        </div>
    </div> 
    <div>
    </div>
    <div class="text-center mt-14">
        <h2 class="text-2xl sm:text-3xl font-medium mb-5">Who Am I?</h2>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-5 sm:gap-14 sm:mx-28 xl:mx-56">
            <img class="w-32 sm:w-40 h-32 sm:h-40 order-2 rounded-full border border-blue-200 shadow-md" src="../static/kevincoto.jpg"/>
            <p class="order-1 text-lg">I'm a junior web developer that want to create some side-projects and work with clever and interesting people around the world. I want to work with you, <a class="text-blue-400 underline">let's to connect</a></p>
        </div>
        </div>
</div>
</template>
<script>
export default {
 
}
</script>
<style>
#app{
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
</style>
