<template>
    <header class="main-header flex space-between align-center">
        <logo/>
        <nav class="main-nav">
            <ul class="flex clean-list">
                <li><a href="#">Features</a></li>
                <li><a href="#">Team</a></li>
                <li><a href="#">Sign In</a></li>
            </ul>
        </nav>
    </header>
</template>
<script>
import logo from './logo.vue'
export default {
    components: {
        logo
    }
    
}
</script>