<template>
<div>
    <div class="card" style="width: 18rem;">
        <div class="image-box">
            <img :src="product.images[0]" class="card-img-top" alt="...">
        </div>
        <div class="card-body">
            <h5 class="card-title">{{ product.title }}</h5>
            <p class="card-text">{{ product.description }}</p>
            <p class="card-text">Rs.{{ product.price}}</p>
            <p class="card-text">{{ product.updatedAt }}</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
    </div>
</div>
</template>

<script setup>
const props = defineProps({
    product:{}
})
</script>

<style  scoped>
 img {
        filter: grayscale() blur(2px);
        transition: 1s;
    }
    img:hover {
        filter: none;
        transform: scale(2);
    }
    .img-box{
        overflow: hidden;
    }
</style>
