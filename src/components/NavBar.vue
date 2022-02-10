<template>

    <nav class="navbar is-white">
        <div class="container">
            <div class="navbar-brand">
                <a class="navbar-item brand-text" href="../index.html">
                Guido Santella Component Portfolio
                </a>
                <div class="navbar-burger burger" data-target="navMenu">
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
            </div>
            
            <div id="navMenu" class="navbar-menu">
                <div class="navbar-start">
                    
                    <RouterLink to="/" class="navbar-item">Home</RouterLink>
                    <RouterLink to="/about" class="navbar-item">About</RouterLink>
                    
                </div>

            </div>
        </div>
    </nav>

</template>