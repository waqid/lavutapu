<template>
    <div>
        <!-- navbar -->
        <nav class="">
            <a href="/" @click.prevent="" class="">Lavutapu</a>
            <ul>
                <li>
                    <router-link class="" :to="{name:'home'}">Home</router-link>
                </li>
                <li>
                    <router-link class="" :to="{name:'about'}">About</router-link>
                </li>
            </ul>
        </nav>
        <!-- content -->
        <div class="container">
            <router-view></router-view>
        </div>
    </div>
</template>