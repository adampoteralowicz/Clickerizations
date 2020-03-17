<template>
    <div id="app">
        <h4 class="bg-primary text-black text-center p-2">Clickerizations</h4>
        <div id = "map"></div>
    </div>
</template>
<script>
export default {
    name: 'app'
}

L.mapbox.accessToken = 'pk.eyJ1IjoiYnJlczE5OTAiLCJhIjoiY2s3OTJwZHduMGw3ZDNsbnl5d3gxZ3FiMiJ9.2Q9x3rLq6CR2bqYRYMwlWg';
            var map = L.mapbox.map('map')
                .setView([51.06, 17.02], 6)
                .addLayer(L.mapbox.styleLayer('mapbox://styles/bres1990/ck79347ze06g11ir0och9fmi6'));
</script>