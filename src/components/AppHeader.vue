 
 <script>
 export default {
   props: {
     links: {
       type: Array,
       required: true
     }
   }
 }
 </script>

<template lang="">
    
    <div class="top-header">
        <div class="container">
            <div class="row">
                <div class="col-12 text-light d-flex justify-content-between align-items-center">
                    <span><i class="fas fa-clock"></i> Open Hours: Mon - Sat - 9:00 - 18:00</span>
                    <span class="ms-3">
                        <i class="fas fa-phone"></i> +1 (305) 1234-5678 
                        <i class="fas fa-envelope"></i> hello@example.com
                        <i class="fab fa-facebook-f ms-3"></i>
                        <i class="fab fa-twitter ms-3"></i>
                        <i class="fab fa-linkedin-in ms-3"></i>
                    </span>
                </div>
            </div>
        </div>
    </div>

    
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
        <img src="../assets/logo.png" alt="NexGen Logo" class="logo img-fluid">
          <div class="collapse navbar-collapse">
            <ul class="navbar-nav ms-auto">
              <li v-for="(link, index) in links" :key="index" class="nav-item">
                <a :class="['nav-link', { 'btn btn-primary': link.isButton }]" :href="link.href">{{ link.text }}</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>

    
    <div class="bottom-header position-relative">
        <div class="overlay"></div>
        <div class="container text-center">
            <img src="../assets/bg-parallax.png" alt="Team Image" class="img-fluid centered-image">
            <div class="content">
                <h1 class="display-4">Ready <span class="text-highlight">Team</span></h1>
                <p>No matter what your company needs, we will be ready to assist you in the best possible way.</p>
                <button class="btn btn-primary me-2 mb-2">Get in Touch</button>
                <button class="btn btn-outline-primary mb-2">Read More</button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.top-header {
    background-color: #0D1B2A;
    padding: 1rem;
}

.top-header i {
    color: #ffffff;
    font-size: 1.2rem; 
}

.navbar {
    padding: 0.5rem 1rem;
    z-index: 10;
    position: relative;
}

.logo {
    width: 100px;
    height: auto;
}

.navbar-brand {
    font-weight: bold;
    color: #058283;
}

.navbar-nav .nav-link {
    margin-right: 1rem;
    color: #0D1B2A;
    font-weight: 500;
}

.navbar-nav .btn-primary {
    background-color: #058283;
    border: none;
    padding: 0.5rem 1rem;
    font-weight: bold;
}

.bottom-header {
    padding: 4rem 0;
    background-color: #f8f9fa; 
    position: relative;
    z-index: 1;
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(255, 255, 255, 0.5);
    z-index: 2;
}

.centered-image {
    max-width: 80%;
    height: auto;
    margin: 0 auto;
    z-index: 3;
    position: relative;
}

.content {
    z-index: 4;
    position: relative;
    margin-top: -150px; 
}

.text-highlight {
    background-color: #e2e3e799;
    color: #058283;
    padding: 0 0.5rem;
}

.bottom-header h1 {
    font-weight: bold;
    margin-bottom: 1rem;
}

.bottom-header p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
}

.bottom-header .btn-primary {
    background-color: #058283;
    border: none;
}

.bottom-header .btn-outline-primary {
    border-color: #00B7C2;
    color: #00B7C2;
}
</style>




