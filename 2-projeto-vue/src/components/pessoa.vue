<template>
    <div>
        <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
        <info/>
    </div>
</template>

<script>
import info from './info.vue'
    export default {
        // eslint-disable-next-line vue/multi-word-component-names
        name: 'pessoa',
        components: {
            info
        },
        
        data() {
            return {
                nome: 'Renan'
            }
        }
    }
</script>