<template>
    <div>
        <b>{{msg}}</b>
        <aku></aku>
        </div>
</template>
<script>
import Aku from './Aku.vue'
export default {
    components: {
        'aku':Aku
    },
    data() {
        return {
            msg:'Selamat Gabung'
        }
    }
}
</script>
<style></style>