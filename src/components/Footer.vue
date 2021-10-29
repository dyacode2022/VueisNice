<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
</script>

<template>
    <div id="footer">
        <div id="footerCopyright">2021 DIA.</div>
        <div id="footerCont">github.com/dya-code</div>
    </div>
    
</template>

<style>
#footer {
    display: flex;
}

#footerCopyright {
    font-size: 20px;
    color: rgb(145, 145, 145);
    position: relative;
    left:20%;
    bottom: 80px;
    width: 100px;
}

#footerCont {
    font-size: 17px;
    color: rgb(145, 145, 145);
    position: relative;
    left: 65%;
    bottom: 80px;
    width: 200px;
}
</style>
