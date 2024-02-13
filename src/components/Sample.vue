<template>
    <div>
        <h1>
            {{sampleMessage}}
        </h1>
    </div>
</template>
<script>
export default {
    name: 'SampleVue',
    props:{
        sampleMessage: String,
    }
}
</script>