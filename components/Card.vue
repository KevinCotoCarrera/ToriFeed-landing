<template>
<div class="w-56 sm:w-80 xl:w-96 flex flex-col text-center justify-center items-center gap-3 sm:gap-5 xl:gap-8  py-5 px-3 sm:py-5 xl:py-8 bg-blue-100 border-b-4 border-yellow-200 hover:border-yellow-100 rounded-2xl shadow-xl hover:shadow-sm">
    <img :src="require(`img`)" class="w-10 h-10"/>
    <h3 v-bind="h3" class="text-lg sm:text-xl xl:text-2xl">{{h3}}</h3>
    <p v-bind="p" class="h-20">{{p}}</p>
</div>
</template>
<script>
export default {
    props:{
        p: String,
        h3: String,
        img: String,
    }
}
</script>
