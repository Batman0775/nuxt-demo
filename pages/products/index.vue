<template>
    <div>
        <section class="py-5">
            <div class="container">
                <div class="row g-3">
                    <div class="col-md-3" v-for="(product , index) in 50" :key="index">
                        <productCard></productCard>
                    </div>
                </div>
            </div>
        </section>
    </div>
    </template>
    <script setup>
        const {data} = await useFetch("https://api.escuelajs.co/api/v1/products");
        console.warn(data);
    </script>
    
    <style  scoped>
   
    </style>