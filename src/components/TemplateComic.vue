<template>
  <div class="TemplateComic">
    <img :src="comic.thumb" :alt="comic.series"> 
    <h3>{{ comic.series }}</h3>   
  </div>
</template>

<script>
export default {
    name: 'TemplateComic',
    props: {
        comic: Object
    }
}
</script>

<style lang="scss">
    .TemplateComic {
        width: calc(100% / 6 - 40px);
        margin: 25px 20px;
        cursor: pointer;

        img {
            width: 100%;
            height: 176px;
            display: block;
            object-fit: cover;
            object-position: top;
        }

        h3{
            margin-top: 20px;
            color: #fff;
        }
    }

</style>