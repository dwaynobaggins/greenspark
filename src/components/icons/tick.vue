<template>
    <svg xmlns="http://www.w3.org/2000/svg" :width="width" :height="height" viewBox="0 0 123 101" :fill="fill" >
    <path class="cls-1" d="M4.67,67.27c-14.45-15.53,7.77-38.7,23.81-24C34.13,48.4,42.32,55.9,48,61L93.69,5.3c15.33-15.86,39.53,7.42,24.4,23.36L61.14,96.29a17,17,0,0,1-12.31,5.31h-.2a16.24,16.24,0,0,1-11-4.26c-9.49-8.8-23.09-21.71-32.91-30v0Z"/></svg>
</template>

<script>
    export default {
        props: {
            width: { type: [Number, String], default: 12 },
            height: { type: [Number, String], default: 12 },
            fill: { type: String, default: "var(--white)" },
        }
    }
</script>