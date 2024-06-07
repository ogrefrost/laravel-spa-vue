<!-- resources/js/components/App.vue -->
<template>
    <div>
        <nav>
            <router-link to="/">Home</router-link>
            <router-link to="/about">About</router-link>
        </nav>
        <router-view></router-view>
    </div>
</template>

<script>
export default {
    name: 'App'
}
</script>

<style scoped>
nav {
    margin-bottom: 10px;
}

router-link {
    margin-right: 10px;
    text-decoration: none;
    color: #42b983;
}

.router-link-active {
    font-weight: bold;
}
</style>
