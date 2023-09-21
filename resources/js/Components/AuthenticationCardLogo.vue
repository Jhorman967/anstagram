<script setup>
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <Link :href="'/'">
        <img class="w-60" :src="image" alt="Logo anstagram">
    </Link>
</template>

<script>
    import image from '../../images/anstagram.jpeg'

    export default {
        data(){
            return{
                image:image
            }
        }
    }
</script>


