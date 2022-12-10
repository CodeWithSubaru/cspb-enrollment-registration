<template>
    <NavBar>
        <router-link to="/login">Login</router-link>
    </NavBar>
    <router-view></router-view>
</template>

<script>
import NavBar from "@/components/NavBar.vue";

export default {
    components: { NavBar },
};
</script>
