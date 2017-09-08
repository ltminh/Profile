<template>
  <nav class="main-navbar">

        <div class="main-navbar-header">
            <div class="container d-flex justify-content-between align-items-center">
                <!-- Navbar Brand -->
                <a href="#" class="navbar-brand">
                    <img src="/static/theme/img/logo.png" alt="..." width="35">
                </a>

                <!-- Open Menu Btn -->
                <button id="navbar-open">
                        <span></span>
                        <span></span>
                        <span></span>
                        <span></span>
                    </button>
            </div>
        </div>

        <!-- Navbar Menu Holder -->
        <div class="navbar-outer">
            <div class="navbar-inner d-flex justify-content-center align-items-center">
                <a id="close-btn" href="#">
                    <img src="/static/theme/img/close.svg" alt="close" class="img-fluid">
                </a>

                <!-- Navbar Menu -->
                <ul class="navbar-menu list-unstyled text-center">
                    <li>
                        <a href="#hero">Home</a>
                    </li>
                    <li>
                        <a href="#about">About</a>
                    </li>
                    <li>
                        <a href="#services">Services</a>
                    </li>
                    <li>
                        <a href="#resume">Resume</a>
                    </li>
                    <li>
                        <a href="#portfolio">Portfolio</a>
                    </li>
                    <li>
                        <a href="#contact">Contact</a>
                    </li>
                </ul>
            </div>

        </div>
    </nav>
</template>

<script>
  export default {
    name: 'Navbar'
  }
</script>
