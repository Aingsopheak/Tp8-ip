<script>
    import {RouterLink} from 'vue-router'
</script>

<template>
    <div class="register">
    <div class="even-column">
        <div class="left-side">
            <img src="../assets/images/vue.png">
            <div class="text-container">
                <h1>Welcome</h1>
                <h4>Autentication App</h4>
    <div>
        <RouterLink to="/login">Login</RouterLink>
        <RouterLink to="/register">Register</RouterLink>
    </div>
</div>
            </div>
        </div>
    </div>
</template>
