<template>
        <header>
            <div class="container">
                <div class="logo">
                    <NuxtLink to="https://www.arteased.id/" class="textbase">
                        <img src="img/Web Arteased Logo.svg"> 
                    </NuxtLink>
                </div>
                <div class="search">
                    <form id="searchForm">
                        <input type="search" placeholder="Monet..." id="searchInput" onkeyup="search()" autocomplete="off" data-search>
                        <img src="img/Search Icon.svg" type="submit" id="searchBtn">
                    </form>
                </div>
            </div>
            <div class="">
                <NuxtLink to="/article" class="textbase">Article</NuxtLink>
                <Nuxtlink to="/learn" class="textbase">Learn</Nuxtlink>
                <NuxtLink to="/store" class="textbase">Store</NuxtLink>
                <NuxtLink to="/explore" class="textbase">Explore</NuxtLink>
                <NuxtLink to="/events" class="textbase">Events</NuxtLink>
                <NuxtLink to="exploreartist" class="textbase">Artist</NuxtLink>
                <NuxtLink to="/index#section" class="textbase">About Us</NuxtLink>
                <NuxtLink to="/index#section-2" class="textbase">Contact</NuxtLink>
            </div>
        </header>
</template>