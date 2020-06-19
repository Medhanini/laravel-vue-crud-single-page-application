<template>
    <div class="container">
        <div class="text-center" style="margin: 20px 0px 20px 0px;">
            <a href="https://github.com/Medhanini" target="_blank"><img src="https://avatars2.githubusercontent.com/u/42269173?s=400&u=c4e0f0558595a65120e0b3ecaf12f6dca71981f7&v=4"></a><br>
            <span class="text-secondary">Laravel & Vue CRUD Single Page Application (SPA) </span>
        </div>

        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="collapse navbar-collapse">
                <div class="navbar-nav">
                    <router-link to="/" class="nav-item nav-link">Home</router-link>
                    <router-link to="/add" class="nav-item nav-link">Add Book</router-link>
                </div>
            </div>
        </nav>
        <br/>
        <router-view></router-view>
    </div>
</template>

<script>
    export default {}
</script>