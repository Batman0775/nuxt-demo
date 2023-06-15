<template>
    <div>
        <section class="py-5">
            <div class="container">
                <div class="row g-3">
                    <div class="col-md-3" v-for="(product , index) in 50" :key="index">
                        <div class="card" style="width: 18rem;">
                            <div class="img-box">
                                <img src="https://cdn.pixabay.com/photo/2019/05/31/01/53/chowmein-4241265_640.jpg" class="card-img-top" alt="...">
                            </div>
                            <div class="card-body">
                                <h5 class="card-title">Chowmein</h5>
                                <p class="card-text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minus deserunt laudantium vero sapiente rerum quos, alias enim ratione nam itaque est, fugit reprehenderit distinctio harum quisquam sunt culpa a aliquam!</p>
                                <a href="https://www.youtube.com/" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
    </template>
    <script setup>
    
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