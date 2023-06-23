<template>
    <div>
        <section class="py-5">
            <div class="container">
                <div class="row g-3">
                    <div class="col-md-3" v-for="(p, index) in data.data._rawValue" :key="index">
                        <nuxt-link :to="`/products/${p.id}`">
                        <productCard :product="p"/>

                        </nuxt-link>
                    </div>
                </div>
            </div>
        </section>
    </div>
    </template>
    <script setup>
        const data = await useFetch("https://api.escuelajs.co/api/v1/products");
        console.warn(data.data._rawValue);
    </script>
    
    <style  scoped>
   
    </style>