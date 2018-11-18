---
layout: single
title: Software
permalink: /software/
author_profile: true
type: pages
scope:
    path: ""
    type: pages
toc: true
toc_label: "Software"
header:
mathjax: true
---

After many years of writing code for the HAWC Observatory, I am just getting
started in the open-source community. I am quickly finding ways to re-purpose
my coding experience into useful projects.

See my [GitHub profile](http://github.com/dfiorino) for further details.

## Maintainer

### AUDL-Pull
A super user-friendly Python project for extraction of sports data (ultimate
frisbee) and tutorials for data exploration using Pandas.
- [GitHub](https://github.com/dfiorino/audl-pull) repo
- Documentation forthcoming.


<head>
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <script>L_PREFER_CANVAS=false; L_NO_TOUCH=false; L_DISABLE_3D=false;</script>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.2.0/dist/leaflet.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.2.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawgit.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
    <style>#map_d742c6b177bd45b08a78fc9bde6c4415 {
        position: relative;
        width: 100.0%;
        height: 100.0%;
        left: 0.0%;
        top: 0.0%;
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet-minimap/3.6.1/Control.MiniMap.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet-minimap/3.6.1/Control.MiniMap.css"/>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/leaflet.markercluster.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/leaflet.markercluster/1.1.0/MarkerCluster.Default.css"/>
    <script src="https://unpkg.com/leaflet.featuregroup.subgroup@1.0.2/dist/leaflet.featuregroup.subgroup.js"></script>
</head>
<body>    
    
    <div class="folium-map" id="map_d742c6b177bd45b08a78fc9bde6c4415" ></div>
</body>
<script>    
    
    
        var bounds = null;
    

    var map_d742c6b177bd45b08a78fc9bde6c4415 = L.map(
        'map_d742c6b177bd45b08a78fc9bde6c4415', {
        center: [0, 0],
        zoom: 2,
        maxBounds: bounds,
        layers: [],
        worldCopyJump: false,
        crs: L.CRS.EPSG3857,
        zoomControl: true,
        });

    
    
    var tile_layer_b3f29343ea1e4f5d923b0402473595fc = L.tileLayer(
        'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
        {
        "attribution": null,
        "detectRetina": false,
        "maxNativeZoom": 18,
        "maxZoom": 18,
        "minZoom": 0,
        "noWrap": false,
        "subdomains": "abc"
}).addTo(map_d742c6b177bd45b08a78fc9bde6c4415);
    
        var tile_layer_470def6d48db45bd9f4d09f74335d1cd = L.tileLayer(
        'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
        {
        "attribution": null,
        "detectRetina": false,
        "maxNativeZoom": 18,
        "maxZoom": 18,
        "minZoom": 0,
        "noWrap": false,
        "subdomains": "abc"
} );
        var mini_map_b62ec94561cd4393b0bfe31974b5a544 = new L.Control.MiniMap( tile_layer_470def6d48db45bd9f4d09f74335d1cd,
         {
  "autoToggleDisplay": false,
  "centerFixed": false,
  "collapsedHeight": 25,
  "collapsedWidth": 25,
  "height": 150,
  "minimized": false,
  "position": "bottomright",
  "toggleDisplay": false,
  "width": 150,
  "zoomAnimation": false,
  "zoomLevelFixed": null,
  "zoomLevelOffset": -5
});
        map_d742c6b177bd45b08a78fc9bde6c4415.addControl(mini_map_b62ec94561cd4393b0bfe31974b5a544);
        
    
            var marker_cluster_1d501bfb0da8464c899d057fb65b2d73 = L.markerClusterGroup({});
            map_d742c6b177bd45b08a78fc9bde6c4415.addLayer(marker_cluster_1d501bfb0da8464c899d057fb65b2d73);
            
    
            var feature_group_sub_group_fa330bf2e1d44895bab4a90cbfec4d62 = L.featureGroup.subGroup(marker_cluster_1d501bfb0da8464c899d057fb65b2d73);
            feature_group_sub_group_fa330bf2e1d44895bab4a90cbfec4d62.addTo(map_d742c6b177bd45b08a78fc9bde6c4415);
            
    
            var circle_marker_2ad046c591834372a350f60bbd04822f = L.circleMarker(
                [40.6943, -73.9249],
                {
  "bubblingMouseEvents": true,
  "color": "red",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_fa330bf2e1d44895bab4a90cbfec4d62);
            
    
            var circle_marker_116f65d8304f4877b7875bca5f871fdc = L.circleMarker(
                [32.8312, -117.1225],
                {
  "bubblingMouseEvents": true,
  "color": "red",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_fa330bf2e1d44895bab4a90cbfec4d62);
            
    
            var circle_marker_01894d6de3674e0d8471da7c1932f696 = L.circleMarker(
                [42.3834, -83.1024],
                {
  "bubblingMouseEvents": true,
  "color": "red",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_fa330bf2e1d44895bab4a90cbfec4d62);
            
    
            var circle_marker_80998c7eec40417da7011b4d20b207c5 = L.circleMarker(
                [44.9635, -93.2679],
                {
  "bubblingMouseEvents": true,
  "color": "red",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_fa330bf2e1d44895bab4a90cbfec4d62);
            
    
            var circle_marker_da992f0216eb45b9a619adb3ed6f2516 = L.circleMarker(
                [41.8373, -87.6861],
                {
  "bubblingMouseEvents": true,
  "color": "red",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_fa330bf2e1d44895bab4a90cbfec4d62);
            
    
            var feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479 = L.featureGroup.subGroup(marker_cluster_1d501bfb0da8464c899d057fb65b2d73);
            feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479.addTo(map_d742c6b177bd45b08a78fc9bde6c4415);
            
    
            var circle_marker_cf4e82f38bea461bab3c1b5b0e0e963c = L.circleMarker(
                [-22.925, -43.225],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_9f5af67a98fb4e509af0c80df0772e29 = L.circleMarker(
                [-41.15, -71.3],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_8d7961a4cd964d8caa1247517d4abd97 = L.circleMarker(
                [20.6771, -105.245],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_f146c5da5a1d411db4808fa932ac885d = L.circleMarker(
                [16.75, -93.15],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_d02b33e407454a36ad8bb4bda105d8b3 = L.circleMarker(
                [19.4424, -99.131],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_e022ceba733f4719bbcdb3717a1a5eed = L.circleMarker(
                [20.1704, -98.73],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_9558f365552b4da8b29e26e45ba34017 = L.circleMarker(
                [19.32, -98.23],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_8375e78e56e7441a9027735ee67e47fd = L.circleMarker(
                [18.85, -97.13],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_5c835d68843a4179b51dfc209327b5ee = L.circleMarker(
                [52.08, 4.27],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_439dc92ccebb48e8bd54246da73a9625 = L.circleMarker(
                [48.8667, 2.3333],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_7383d372c2ee4703b9523eae9e9195d0 = L.circleMarker(
                [45.737, 7.315],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_96ddc0c277144211a5c4ca5b6f0f5bf3 = L.circleMarker(
                [40.7774, -111.9301],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_af108377d2ab454ca9fe8b7ab2bfba55 = L.circleMarker(
                [42.7483, -84.4834],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_ddde673e7c5d44dc88875654cbcaa20d = L.circleMarker(
                [39.7621, -104.8759],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_7bf17ae1fa43473d8260ccfb95d675b8 = L.circleMarker(
                [38.9964, -76.9337],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_b06f48b49dfc4a469fce9c6ab8c2d6e9 = L.circleMarker(
                [43.0809, -89.3921],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_245231adc1eb4794a4da6a363f58be1f = L.circleMarker(
                [47.1122, -88.5696],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_8fea03fe48544a8baf2cf05d45066867 = L.circleMarker(
                [19.05, -98.2],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_d64583581ef94dd4ad8aa3701648ca11 = L.circleMarker(
                [32.0282, -81.1784],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_2a78df17a3f24b42a981984d4276c8ab = L.circleMarker(
                [35.6619, -105.9818],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_580881cdb22641a6b53acae62aaf9da3 = L.circleMarker(
                [39.3051, -76.6144],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_09967da9f2c34b7c84e69dc6012304c3 = L.circleMarker(
                [40.791, -77.8568],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_add304ef4b7042f5a1a7c7297da5b12b = L.circleMarker(
                [43.1681, -77.6162],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_787d4d215cd4474187a18fc057c2bb6d = L.circleMarker(
                [38.9705, -76.5047],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_354414d6e2744f4db4d208bdda777a10 = L.circleMarker(
                [38.9047, -77.0163],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_14d6951a8a81463e921a0f453784e9c8 = L.circleMarker(
                [18.9211, -99.24],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_18fc54c525bf4c90993a5f49091085fe = L.circleMarker(
                [40.5487, -105.0656],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var circle_marker_a4d25a824a724abdb5b8ba33ba362e18 = L.circleMarker(
                [33.7627, -84.4231],
                {
  "bubblingMouseEvents": true,
  "color": "blue",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479);
            
    
            var feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4 = L.featureGroup.subGroup(marker_cluster_1d501bfb0da8464c899d057fb65b2d73);
            feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4.addTo(map_d742c6b177bd45b08a78fc9bde6c4415);
            
    
            var circle_marker_4bb32103399c47e9b5304354a3c25f72 = L.circleMarker(
                [41.896, 12.4833],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_81866fd782a74440ad9cc8bdd366cc74 = L.circleMarker(
                [45.47, 9.205],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_3f057c4a03c84300b1838547dfb4ef34 = L.circleMarker(
                [43.78, 11.25],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_e9cad576b457441da0a59de0a69d707f = L.circleMarker(
                [37.9833, 23.7333],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_96cc06c3b8304624998030064bcbb7eb = L.circleMarker(
                [42.6609, 18.0914],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_560aaf0357a24dbf9a590ebb78947018 = L.circleMarker(
                [45.8, 16.0],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_96870aafe2494932bf26ffb3c13f558a = L.circleMarker(
                [43.5204, 16.47],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_03cccdf016e34fbabd04dd2bb909ea86 = L.circleMarker(
                [45.336988, 14.306201],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_5c048b489b6149a98cc33e5ae0b02323 = L.circleMarker(
                [43.175385, 16.436683],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_6b1c28d62f4442be827f5962d67d2a76 = L.circleMarker(
                [41.3833, 2.1834],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_06388286e5914e8ba9d7c8eb4c92cdc6 = L.circleMarker(
                [39.7621, -104.8759],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_c7446681b18441d4b5032eee5a4e09b3 = L.circleMarker(
                [28.4801, -81.3448],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_272fcf6631e6414485dbdc0074918ba6 = L.circleMarker(
                [30.0687, -89.9288],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_7ee6467965084fb1b79db2dc664a6ba2 = L.circleMarker(
                [45.5372, -122.65],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_a83d6e4653334481b33b2171ca586b8d = L.circleMarker(
                [47.6217, -122.3238],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_98276e9462be473c884cf2342d75d18f = L.circleMarker(
                [34.114, -118.4068],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_73692ed1035645169ab6d3c4bd49f3d4 = L.circleMarker(
                [37.7561, -122.4429],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_c64fc7daf4284233b67ae4c386520ec8 = L.circleMarker(
                [32.8312, -117.1225],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_20ecbfd265824b81b828c7ceec31783e = L.circleMarker(
                [14.7158, -17.4731],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var circle_marker_1c9b2f60a06a4d289739f4db1e8415e3 = L.circleMarker(
                [15.6559, -13.2554],
                {
  "bubblingMouseEvents": true,
  "color": "green",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "green",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 6,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4);
            
    
            var feature_group_sub_group_87a264a4f8e447feb0859b6090ef2518 = L.featureGroup.subGroup(marker_cluster_1d501bfb0da8464c899d057fb65b2d73);
            feature_group_sub_group_87a264a4f8e447feb0859b6090ef2518.addTo(map_d742c6b177bd45b08a78fc9bde6c4415);
            
    
            var feature_group_sub_group_0e52e2f44da94420b37c9754dd60d718 = L.featureGroup.subGroup(marker_cluster_1d501bfb0da8464c899d057fb65b2d73);
            feature_group_sub_group_0e52e2f44da94420b37c9754dd60d718.addTo(map_d742c6b177bd45b08a78fc9bde6c4415);
            
    
            var layer_control_a980d7195291415d898aa6794b2355f1 = {
                base_layers : { "openstreetmap" : tile_layer_b3f29343ea1e4f5d923b0402473595fc, },
                overlays : { "SDoH" : feature_group_sub_group_fa330bf2e1d44895bab4a90cbfec4d62,"Physics" : feature_group_sub_group_7a5e1876478a40ea85bc4cbc7c690479,"Travel" : feature_group_sub_group_13b23754c4774e16a77f60242ad18fd4,"Lived" : feature_group_sub_group_87a264a4f8e447feb0859b6090ef2518,"Worked" : feature_group_sub_group_0e52e2f44da94420b37c9754dd60d718, }
                };
            L.control.layers(
                layer_control_a980d7195291415d898aa6794b2355f1.base_layers,
                layer_control_a980d7195291415d898aa6794b2355f1.overlays,
                {position: 'topright',
                 collapsed: true,
                 autoZIndex: true
                }).addTo(map_d742c6b177bd45b08a78fc9bde6c4415);
</script> 
