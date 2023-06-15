<template>
<div>
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ms-auto mb-2 mb-lg-0">  
                        <li class="nav-item">
                            <nuxt-link to="/" class="nav-link">Home</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="/about" class="nav-link">About us</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="/service" class="nav-link">Our service</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="/contact" class="nav-link">Contact us</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="/gallery" class="nav-link">Gallery</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <nuxt-link to="/products" class="nav-link">Products</nuxt-link>
                        </li>
                    </ul>
                    
                </div>
            </div>
        </nav>
    </header>
    <main>
        <slot></slot>
    </main>

    <footer>
      <section class="py-5">
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <img src="https://codeit.com.np/images/1642171339codeIT%20logo.png" alt="" width="150px" height="50px">
                    <div>
                    <span>9862130505</span>
                    <span>, 025-525163</span>
                </div>
                <p>info@codeit.com.np</p>
                <p>Prithvi Path,Dharan</p>
                </div>
                <div class="col-md-3">
                <h6>Quick links 
                   <hr>
                </h6>
                <p>About Us</p>
                <p>Contact Us</p>
                <p>Gallery</p>
                <p>Blog</p>
            </div>
            <div class="col-md-3">
                <h6>Bank Account Detail</h6>
                <p>Bank: Nepal Bank Limited</p>
                <p>Account Name: CODE IT</p>
                <p>Ac/No.: 01600106885462000001</p>
                <p>Branch: Dharan</p>
                <div class="container">
                    <img src="https://codeit.com.np/asset/img/fonepay-bg.png" alt="" width="100px" height="50px">
                    <img src="https://codeit.com.np/asset/img/codeit-qr.jpg" alt="" width="100px" height="100px">
                </div>
            </div>
            <div class="col-md-3">
                <h6>
                    Download App
                </h6>
                <p>Download our mobile app.</p>
                <div class="container">
                    <img src="https://codeit.com.np/mobile/appstore.png" alt="">
                    <img src="https://codeit.com.np/mobile/googleplay.png" alt="">
                </div>
            </div>
            </div>
            
        </div>
        
      </section>
    </footer>
</div>
</template>

<script setup>

</script>

<style  scoped>

</style>
