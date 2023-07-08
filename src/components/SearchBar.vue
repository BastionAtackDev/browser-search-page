<script>

export default {
    methods: {
        Search(){
            window.open("https://duckduckgo.com/?q=" + document.querySelector('input').value, '_self')
        },
    }
};

// this.querySelector("#search").addEventListener('keypress', function (event) {
//     if (event.key === 'Enter') {
//       Search();
//     }
// });
</script>
<template>
    <input type="text" name="searchbar" id="search" @keyup.enter="Search()">
    <button @click="Search()">🍳</button>
</template>
<style>
    input{
    width: 40svw;
    }
</style>