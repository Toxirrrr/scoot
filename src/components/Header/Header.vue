<script setup>

import './Header.scss'

</script>

<template>
    
    <header class="header">
        
        <div class="container">
            
            <div class="header__wrapper">
                
                <div class="header__left-wrapper">
                    
                    <router-link to="/">
                        <img src="/public/img/header__logo.svg" alt="header logo" width="108" height="29">
                    </router-link>
                    
                    <nav class="header__nav">
                        <ul class="header__nav-list">
                            <li class="header__nav-item">
                                <router-link class="header__nav-item-link" to="/">About</router-link>
                            </li>
                            <li class="header__nav-item">
                                <router-link class="header__nav-item-link" to="/">Location</router-link>
                            </li>
                            <li class="header__nav-item">
                                <router-link class="header__nav-item-link" to="/">Careers</router-link>
                            </li>
                        </ul>
                    </nav>
                </div>
                
                <button class="header__btn">Get Scootin</button>
            </div>
            
        </div>
        
    </header>
    
</template>