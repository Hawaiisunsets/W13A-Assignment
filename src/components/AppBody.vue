<template>
    <div>
        <h3>This is where the Body goes</h3>
        <BodyHonda/>
        <BodyNissan/>
        <BodyToyota/>
    </div>
</template>

<script>
import BodyHonda from "@/components/BodyHonda.vue";
import BodyNissan from "@/components/BodyNissan.vue";
import BodyToyota from "@/components/BodyToyota.vue";
    export default {
        name: "AppBody",
        components: {
            BodyHonda,
            BodyNissan,
            BodyToyota
        }
    }
</script>

<style scoped>
h3{
    color: blue;
}

</style>