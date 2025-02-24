# project6
<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_59bfbb039e60e8b3f1943f352691808d {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
</head>
<body>
    
    
            <div class="folium-map" id="map_59bfbb039e60e8b3f1943f352691808d" ></div>
        
</body>
<script>
    
    
            var map_59bfbb039e60e8b3f1943f352691808d = L.map(
                "map_59bfbb039e60e8b3f1943f352691808d",
                {
                    center: [36.5, 127.5],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 7,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_29d88628db97b607eb0bc0b12f727ea8 = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {
  "minZoom": 0,
  "maxZoom": 19,
  "maxNativeZoom": 19,
  "noWrap": false,
  "attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors",
  "subdomains": "abc",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_29d88628db97b607eb0bc0b12f727ea8.addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var marker_add88f266632adf9bfabd6dcb6e99efd = L.marker(
                [35.2061167413, 126.8122630468],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_b2d8f3af784174406949674a083bb3c1 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_add88f266632adf9bfabd6dcb6e99efd.setIcon(icon_b2d8f3af784174406949674a083bb3c1);
        
    
        var popup_8b4c4850cdfc43791aa90fe9a3559a25 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_471bdbcddfb998025b2b2e033a6c9130 = $(`<div id="html_471bdbcddfb998025b2b2e033a6c9130" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 광산구 오선동 548-5 (하남산단7번로 153)<br>사고발생일자: 2024-10-15 오전 00:00<br>클러스터: 0</div>`)[0];
                popup_8b4c4850cdfc43791aa90fe9a3559a25.setContent(html_471bdbcddfb998025b2b2e033a6c9130);
            
        

        marker_add88f266632adf9bfabd6dcb6e99efd.bindPopup(popup_8b4c4850cdfc43791aa90fe9a3559a25)
        ;

        
    
    
            var marker_69bb6df7e351a83f5d10c594e63d13b1 = L.marker(
                [35.2061118899, 126.8125041724],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_29419d7bc809468ce9c01d6416b8df68 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_69bb6df7e351a83f5d10c594e63d13b1.setIcon(icon_29419d7bc809468ce9c01d6416b8df68);
        
    
        var popup_c029399435d5d0d4a48a95f63a615dec = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_25c0db47fe3e395833cc33e64788f6ee = $(`<div id="html_25c0db47fe3e395833cc33e64788f6ee" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 광산구 오선동 548-5<br>사고발생일자: 2023-05-18 오전 00:00<br>클러스터: 0</div>`)[0];
                popup_c029399435d5d0d4a48a95f63a615dec.setContent(html_25c0db47fe3e395833cc33e64788f6ee);
            
        

        marker_69bb6df7e351a83f5d10c594e63d13b1.bindPopup(popup_c029399435d5d0d4a48a95f63a615dec)
        ;

        
    
    
            var marker_27f401c96573abb5887eeb5bc07f22a2 = L.marker(
                [35.1489021927, 128.9815697173],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_6662cc6ea5ebb4dc91258faf1fbbb9af = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_27f401c96573abb5887eeb5bc07f22a2.setIcon(icon_6662cc6ea5ebb4dc91258faf1fbbb9af);
        
    
        var popup_0979e29196bc066a1b97b6a806f9e092 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ceb17055f21e83e41e828bc60eec62ab = $(`<div id="html_ceb17055f21e83e41e828bc60eec62ab" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 사상구 학장동 226-1(새벽로90)<br>사고발생일자: 2024-09-21 오전 00:00<br>클러스터: 1</div>`)[0];
                popup_0979e29196bc066a1b97b6a806f9e092.setContent(html_ceb17055f21e83e41e828bc60eec62ab);
            
        

        marker_27f401c96573abb5887eeb5bc07f22a2.bindPopup(popup_0979e29196bc066a1b97b6a806f9e092)
        ;

        
    
    
            var marker_2f427e9fe5d0ac0ef6a4958f1988d80e = L.marker(
                [35.1493225074, 128.9815481708],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_bc73ea258a8ea7fc51c752d9d49df815 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_2f427e9fe5d0ac0ef6a4958f1988d80e.setIcon(icon_bc73ea258a8ea7fc51c752d9d49df815);
        
    
        var popup_d2648e437a017bae0e1f7b97af3097bc = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a54c475c2f6fea4906d914d5bc6cb77d = $(`<div id="html_a54c475c2f6fea4906d914d5bc6cb77d" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 사상구 학장동 719-8 (새벽로 89)<br>사고발생일자: 2024-09-21 오전 00:00<br>클러스터: 1</div>`)[0];
                popup_d2648e437a017bae0e1f7b97af3097bc.setContent(html_a54c475c2f6fea4906d914d5bc6cb77d);
            
        

        marker_2f427e9fe5d0ac0ef6a4958f1988d80e.bindPopup(popup_d2648e437a017bae0e1f7b97af3097bc)
        ;

        
    
    
            var marker_aa99be1b233802627687c0b79dfd7f97 = L.marker(
                [37.7239078432, 126.692657364],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_9174663f7a1b836aa645a9040026e6e5 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_aa99be1b233802627687c0b79dfd7f97.setIcon(icon_9174663f7a1b836aa645a9040026e6e5);
        
    
        var popup_d2de11803b4c47574438e60e3121e027 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b4b9d9fbe66d6969111bdc9fcdd35423 = $(`<div id="html_b4b9d9fbe66d6969111bdc9fcdd35423" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 파주시 문발동 650<br>사고발생일자: 2024-09-09 오전 00:00<br>클러스터: 2</div>`)[0];
                popup_d2de11803b4c47574438e60e3121e027.setContent(html_b4b9d9fbe66d6969111bdc9fcdd35423);
            
        

        marker_aa99be1b233802627687c0b79dfd7f97.bindPopup(popup_d2de11803b4c47574438e60e3121e027)
        ;

        
    
    
            var marker_f872f133ac008de4a64da87fb714536a = L.marker(
                [37.7236834898, 126.6927150316],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_b4c3e697c84177c19110efc945c06f10 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f872f133ac008de4a64da87fb714536a.setIcon(icon_b4c3e697c84177c19110efc945c06f10);
        
    
        var popup_7742d05221c61acdddabbfa69394bd31 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_34c0b4bf9d38269482350e5d53d3b8bd = $(`<div id="html_34c0b4bf9d38269482350e5d53d3b8bd" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 파주시 문발동 667<br>사고발생일자: 2024-07-30 오전 00:00<br>클러스터: 2</div>`)[0];
                popup_7742d05221c61acdddabbfa69394bd31.setContent(html_34c0b4bf9d38269482350e5d53d3b8bd);
            
        

        marker_f872f133ac008de4a64da87fb714536a.bindPopup(popup_7742d05221c61acdddabbfa69394bd31)
        ;

        
    
    
            var marker_e225ad906a26f5cf116644d09c1c4f0b = L.marker(
                [37.7240521079, 126.6924213297],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_6266b6b8307b75907db3800cd9a47228 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_e225ad906a26f5cf116644d09c1c4f0b.setIcon(icon_6266b6b8307b75907db3800cd9a47228);
        
    
        var popup_ed6521917a56c39cc979ab607c28e6e5 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_d629cbbcc237ec0262eec09cb7ddc53f = $(`<div id="html_d629cbbcc237ec0262eec09cb7ddc53f" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 파주시 문발동 650<br>사고발생일자: 2024-07-19 오전 00:00<br>클러스터: 2</div>`)[0];
                popup_ed6521917a56c39cc979ab607c28e6e5.setContent(html_d629cbbcc237ec0262eec09cb7ddc53f);
            
        

        marker_e225ad906a26f5cf116644d09c1c4f0b.bindPopup(popup_ed6521917a56c39cc979ab607c28e6e5)
        ;

        
    
    
            var marker_141afe6894f8e16b2beea13875297ae3 = L.marker(
                [35.1509317908, 128.9819158565],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_f330c772d168bc288a4038699a100c73 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_141afe6894f8e16b2beea13875297ae3.setIcon(icon_f330c772d168bc288a4038699a100c73);
        
    
        var popup_0f12d7542b4dbf5e3ae1b7f2c0a86f5e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_81aef33aac2f8cc5715ea05274539bc4 = $(`<div id="html_81aef33aac2f8cc5715ea05274539bc4" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 사상구 감전동 163-11번지 인근<br>사고발생일자: 2024-08-21 오전 00:00<br>클러스터: 3</div>`)[0];
                popup_0f12d7542b4dbf5e3ae1b7f2c0a86f5e.setContent(html_81aef33aac2f8cc5715ea05274539bc4);
            
        

        marker_141afe6894f8e16b2beea13875297ae3.bindPopup(popup_0f12d7542b4dbf5e3ae1b7f2c0a86f5e)
        ;

        
    
    
            var marker_2f1d2ca0e70cd93e5da57cc7f7ccc0ca = L.marker(
                [35.1510847239, 128.9820432035],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_c3f71d0d0fa901958e321ebba02432df = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_2f1d2ca0e70cd93e5da57cc7f7ccc0ca.setIcon(icon_c3f71d0d0fa901958e321ebba02432df);
        
    
        var popup_f6b0b0ff09ce32f23b947e42c9f44e91 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_09364886754cbdd43f8069ef81b0eb09 = $(`<div id="html_09364886754cbdd43f8069ef81b0eb09" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 사상구 감전동 162-22<br>사고발생일자: 2024-05-05 오전 00:00<br>클러스터: 3</div>`)[0];
                popup_f6b0b0ff09ce32f23b947e42c9f44e91.setContent(html_09364886754cbdd43f8069ef81b0eb09);
            
        

        marker_2f1d2ca0e70cd93e5da57cc7f7ccc0ca.bindPopup(popup_f6b0b0ff09ce32f23b947e42c9f44e91)
        ;

        
    
    
            var marker_acccc4973871c002f3c6bb45cd169e83 = L.marker(
                [35.1509993758, 128.9821694839],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_696ac4fa2719ef08c4de6b3f4a953f4e = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_acccc4973871c002f3c6bb45cd169e83.setIcon(icon_696ac4fa2719ef08c4de6b3f4a953f4e);
        
    
        var popup_fd13466405e02410f6433922c83e42ec = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_4e807c4c24deb95be823e8da3872b27e = $(`<div id="html_4e807c4c24deb95be823e8da3872b27e" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 사상구 감전동 162-22<br>사고발생일자: 2024-04-30 오전 00:00<br>클러스터: 3</div>`)[0];
                popup_fd13466405e02410f6433922c83e42ec.setContent(html_4e807c4c24deb95be823e8da3872b27e);
            
        

        marker_acccc4973871c002f3c6bb45cd169e83.bindPopup(popup_fd13466405e02410f6433922c83e42ec)
        ;

        
    
    
            var marker_f24e8e060e9392ffbd87ddd60a2d13d0 = L.marker(
                [35.1520168624, 128.9823978711],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_da114177431e956a6b0b78a0ea3d7efb = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f24e8e060e9392ffbd87ddd60a2d13d0.setIcon(icon_da114177431e956a6b0b78a0ea3d7efb);
        
    
        var popup_ff9bc30b734650eb3fd72b9a6e5c3a3c = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1b68748e8905ae94c190e359a10d4a25 = $(`<div id="html_1b68748e8905ae94c190e359a10d4a25" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 사상구 감전동 162-26(새벽로 122 인근)<br>사고발생일자: 2024-08-20 오전 00:00<br>클러스터: 4</div>`)[0];
                popup_ff9bc30b734650eb3fd72b9a6e5c3a3c.setContent(html_1b68748e8905ae94c190e359a10d4a25);
            
        

        marker_f24e8e060e9392ffbd87ddd60a2d13d0.bindPopup(popup_ff9bc30b734650eb3fd72b9a6e5c3a3c)
        ;

        
    
    
            var marker_263b1cfa2fa47830e327b8a791a081dd = L.marker(
                [35.1519140412, 128.9821729916],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_ae42c4fffcb4b910d252d6c355230735 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_263b1cfa2fa47830e327b8a791a081dd.setIcon(icon_ae42c4fffcb4b910d252d6c355230735);
        
    
        var popup_70cd55eca8a7dff1eebbcd128bf4c14a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_3a77e9d132d65f4905a4ba23597d5ff4 = $(`<div id="html_3a77e9d132d65f4905a4ba23597d5ff4" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 사상구 감전동 163-6(새벽로 117 인근)<br>사고발생일자: 2024-07-24 오전 00:00<br>클러스터: 4</div>`)[0];
                popup_70cd55eca8a7dff1eebbcd128bf4c14a.setContent(html_3a77e9d132d65f4905a4ba23597d5ff4);
            
        

        marker_263b1cfa2fa47830e327b8a791a081dd.bindPopup(popup_70cd55eca8a7dff1eebbcd128bf4c14a)
        ;

        
    
    
            var marker_2d8241bc05c58a4f838ef256ad001fb5 = L.marker(
                [37.5039987003, 127.0924137956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_afaba9bca57a5a8384a6d142498f3ec5 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_2d8241bc05c58a4f838ef256ad001fb5.setIcon(icon_afaba9bca57a5a8384a6d142498f3ec5);
        
    
        var popup_f60a7528f1a3ef5b29e596156e675c4c = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_7b8f7bca93d9cb782ace5cf8c63f4d14 = $(`<div id="html_7b8f7bca93d9cb782ace5cf8c63f4d14" style="width: 100.0%; height: 100.0%;">사고발생 위치: 서울특별시 송파구 삼전동 100-7<br>사고발생일자: 2024-07-22 오전 00:00<br>클러스터: 5</div>`)[0];
                popup_f60a7528f1a3ef5b29e596156e675c4c.setContent(html_7b8f7bca93d9cb782ace5cf8c63f4d14);
            
        

        marker_2d8241bc05c58a4f838ef256ad001fb5.bindPopup(popup_f60a7528f1a3ef5b29e596156e675c4c)
        ;

        
    
    
            var marker_bf72e04838293a72d496e0e6441eedd4 = L.marker(
                [37.5036191201, 127.0923557572],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_9c91160dc0b75a0efece2a5b078de7f4 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_bf72e04838293a72d496e0e6441eedd4.setIcon(icon_9c91160dc0b75a0efece2a5b078de7f4);
        
    
        var popup_1b61b99bb284afeb3809068f9cb07865 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_57f72a69e22d01095d81b7f34ec33cb5 = $(`<div id="html_57f72a69e22d01095d81b7f34ec33cb5" style="width: 100.0%; height: 100.0%;">사고발생 위치: 서울특별시 송파구 삼전동 100-7<br>사고발생일자: 2023-10-11 오전 00:00<br>클러스터: 5</div>`)[0];
                popup_1b61b99bb284afeb3809068f9cb07865.setContent(html_57f72a69e22d01095d81b7f34ec33cb5);
            
        

        marker_bf72e04838293a72d496e0e6441eedd4.bindPopup(popup_1b61b99bb284afeb3809068f9cb07865)
        ;

        
    
    
            var marker_02c5ef502bd8cca88d4e652b0120a673 = L.marker(
                [35.204724852, 129.0766961045],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_2fad258eb480e83599bfd6764d5e488c = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_02c5ef502bd8cca88d4e652b0120a673.setIcon(icon_2fad258eb480e83599bfd6764d5e488c);
        
    
        var popup_65ec97bc2e051daa0b86eade6acc1e25 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_38849404dcbdfa9ca78e4817d39a218d = $(`<div id="html_38849404dcbdfa9ca78e4817d39a218d" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 동래구 온천동 1441-13번지<br>사고발생일자: 2023-12-27 오전 00:00<br>클러스터: 6</div>`)[0];
                popup_65ec97bc2e051daa0b86eade6acc1e25.setContent(html_38849404dcbdfa9ca78e4817d39a218d);
            
        

        marker_02c5ef502bd8cca88d4e652b0120a673.bindPopup(popup_65ec97bc2e051daa0b86eade6acc1e25)
        ;

        
    
    
            var marker_ebc981e74b31aef31835992b52f2ddcb = L.marker(
                [35.2047993672, 129.0767872996],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_302b6d88178d90b2244b6e605a49b44a = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ebc981e74b31aef31835992b52f2ddcb.setIcon(icon_302b6d88178d90b2244b6e605a49b44a);
        
    
        var popup_91ec354f1b7c54c759dc996f90437318 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a6cd4ff6875af37e99d54b6ba96738d5 = $(`<div id="html_a6cd4ff6875af37e99d54b6ba96738d5" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 동래구 온천동 1441-13번지<br>사고발생일자: 2024-07-03 오전 00:00<br>클러스터: 6</div>`)[0];
                popup_91ec354f1b7c54c759dc996f90437318.setContent(html_a6cd4ff6875af37e99d54b6ba96738d5);
            
        

        marker_ebc981e74b31aef31835992b52f2ddcb.bindPopup(popup_91ec354f1b7c54c759dc996f90437318)
        ;

        
    
    
            var marker_78024ac44172c05413b5db312272e185 = L.marker(
                [35.1752224502, 128.1179123428],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_317cd3a1593c837af1830005406461f2 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_78024ac44172c05413b5db312272e185.setIcon(icon_317cd3a1593c837af1830005406461f2);
        
    
        var popup_a9b45dca9b323910b588065b039c698b = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1947a7c94bed6cfe4be41feff206ccd1 = $(`<div id="html_1947a7c94bed6cfe4be41feff206ccd1" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경상남도 진주시 상평동 대신로168<br>사고발생일자: 2024-05-14 오전 00:00<br>클러스터: 7</div>`)[0];
                popup_a9b45dca9b323910b588065b039c698b.setContent(html_1947a7c94bed6cfe4be41feff206ccd1);
            
        

        marker_78024ac44172c05413b5db312272e185.bindPopup(popup_a9b45dca9b323910b588065b039c698b)
        ;

        
    
    
            var marker_f7937970279561dd45e19fc45b107b9d = L.marker(
                [35.175073733, 128.1179433834],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_0d053d09642ca62449c6c25e7b3d0df8 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f7937970279561dd45e19fc45b107b9d.setIcon(icon_0d053d09642ca62449c6c25e7b3d0df8);
        
    
        var popup_9f6950f37f38d9dcb15436602ca9b477 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_d24029734f531baa0ca608935ff63f2b = $(`<div id="html_d24029734f531baa0ca608935ff63f2b" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경상남도 진주시 상평동 상평동 155-27<br>사고발생일자: 2023-09-17 오전 00:00<br>클러스터: 7</div>`)[0];
                popup_9f6950f37f38d9dcb15436602ca9b477.setContent(html_d24029734f531baa0ca608935ff63f2b);
            
        

        marker_f7937970279561dd45e19fc45b107b9d.bindPopup(popup_9f6950f37f38d9dcb15436602ca9b477)
        ;

        
    
    
            var marker_0f0ba14c3812a9da6e7f62ef2dd9bf35 = L.marker(
                [35.1752049108, 128.1179042962],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_f81f7bd4756fea90b4a8053e8a3f53fc = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0f0ba14c3812a9da6e7f62ef2dd9bf35.setIcon(icon_f81f7bd4756fea90b4a8053e8a3f53fc);
        
    
        var popup_664d783c469280c1ec6801a8faa49eb8 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_0770a0d8fec8e877ba8e4e21307c9e13 = $(`<div id="html_0770a0d8fec8e877ba8e4e21307c9e13" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경상남도 진주시 상평동 상평동 155-29번지<br>사고발생일자: 2023-09-04 오전 00:00<br>클러스터: 7</div>`)[0];
                popup_664d783c469280c1ec6801a8faa49eb8.setContent(html_0770a0d8fec8e877ba8e4e21307c9e13);
            
        

        marker_0f0ba14c3812a9da6e7f62ef2dd9bf35.bindPopup(popup_664d783c469280c1ec6801a8faa49eb8)
        ;

        
    
    
            var marker_f7a7e315e882de84910bac875443b336 = L.marker(
                [38.25346613, 128.5630043409],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_33a238feffa82453df83cad760027949 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f7a7e315e882de84910bac875443b336.setIcon(icon_33a238feffa82453df83cad760027949);
        
    
        var popup_f00a2e7c6816e958a5994e3e46bf5ea7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_5f787d732c53228a0e6361b1f00037c0 = $(`<div id="html_5f787d732c53228a0e6361b1f00037c0" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 고성군 토성면 봉포리 255-1<br>사고발생일자: 2024-01-08 오전 00:00<br>클러스터: 8</div>`)[0];
                popup_f00a2e7c6816e958a5994e3e46bf5ea7.setContent(html_5f787d732c53228a0e6361b1f00037c0);
            
        

        marker_f7a7e315e882de84910bac875443b336.bindPopup(popup_f00a2e7c6816e958a5994e3e46bf5ea7)
        ;

        
    
    
            var marker_9ac176263afd33d5fcd25954fbb0537d = L.marker(
                [38.2534598111, 128.5630043409],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_f73b3f3cf8d53426692e9653e0bc2d88 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_9ac176263afd33d5fcd25954fbb0537d.setIcon(icon_f73b3f3cf8d53426692e9653e0bc2d88);
        
    
        var popup_6170b49098f31ca3ddf667b0904ee8ed = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1c2d3e302af5189e9d0cf81b32cad5d4 = $(`<div id="html_1c2d3e302af5189e9d0cf81b32cad5d4" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 고성군 토성면 봉포리 255-1<br>사고발생일자: 2024-01-05 오전 00:00<br>클러스터: 8</div>`)[0];
                popup_6170b49098f31ca3ddf667b0904ee8ed.setContent(html_1c2d3e302af5189e9d0cf81b32cad5d4);
            
        

        marker_9ac176263afd33d5fcd25954fbb0537d.bindPopup(popup_6170b49098f31ca3ddf667b0904ee8ed)
        ;

        
    
    
            var marker_c515b87b2eb483eb5669f04e4ae3b113 = L.marker(
                [37.5263900301, 126.9261755766],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_7edf2edc123bd45d0e8a563be7eaa687 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_c515b87b2eb483eb5669f04e4ae3b113.setIcon(icon_7edf2edc123bd45d0e8a563be7eaa687);
        
    
        var popup_78e01d73b736f131775d55d9a075f768 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_72b73d1f04056812d0383a44a89b00e9 = $(`<div id="html_72b73d1f04056812d0383a44a89b00e9" style="width: 100.0%; height: 100.0%;">사고발생 위치: 서울특별시 영등포구 여의도동 23(IFC몰)<br>사고발생일자: 2022-07-06 오전 00:00<br>클러스터: 9</div>`)[0];
                popup_78e01d73b736f131775d55d9a075f768.setContent(html_72b73d1f04056812d0383a44a89b00e9);
            
        

        marker_c515b87b2eb483eb5669f04e4ae3b113.bindPopup(popup_78e01d73b736f131775d55d9a075f768)
        ;

        
    
    
            var marker_2e72402e0a2076fe8f5e997795acbe5e = L.marker(
                [37.5263690047, 126.92619268],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_2edad5ca43d8ed21fa9fd2fcabf7360b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_2e72402e0a2076fe8f5e997795acbe5e.setIcon(icon_2edad5ca43d8ed21fa9fd2fcabf7360b);
        
    
        var popup_84ccfab6f223fc65d7c25cf1b006e83b = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_57d181d406dbc2855b74249247760a06 = $(`<div id="html_57d181d406dbc2855b74249247760a06" style="width: 100.0%; height: 100.0%;">사고발생 위치: 서울특별시 영등포구 여의도동 22<br>사고발생일자: 2023-10-25 오전 00:00<br>클러스터: 9</div>`)[0];
                popup_84ccfab6f223fc65d7c25cf1b006e83b.setContent(html_57d181d406dbc2855b74249247760a06);
            
        

        marker_2e72402e0a2076fe8f5e997795acbe5e.bindPopup(popup_84ccfab6f223fc65d7c25cf1b006e83b)
        ;

        
    
    
            var marker_f21a9bfac5a2a35f2e63d22068ab41fc = L.marker(
                [37.4584199754, 128.0659660626],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_ef1e2f2793a574b1bde68cbe79748fc8 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f21a9bfac5a2a35f2e63d22068ab41fc.setIcon(icon_ef1e2f2793a574b1bde68cbe79748fc8);
        
    
        var popup_52da58c8bd46c6eb0b04923263e7e789 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_fd95136ffcb69aaa2e993c48810a4cca = $(`<div id="html_fd95136ffcb69aaa2e993c48810a4cca" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 횡성군 우천면 우천면 우항리 759번지 스마일파크빌 앞 도시계획도로(소로2-201호)<br>사고발생일자: 2023-08-20 오전 00:00<br>클러스터: 10</div>`)[0];
                popup_52da58c8bd46c6eb0b04923263e7e789.setContent(html_fd95136ffcb69aaa2e993c48810a4cca);
            
        

        marker_f21a9bfac5a2a35f2e63d22068ab41fc.bindPopup(popup_52da58c8bd46c6eb0b04923263e7e789)
        ;

        
    
    
            var marker_209a5b6f2cb88451dd4516906e7fcd8f = L.marker(
                [37.458194288, 128.0655422736],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_4d941187f55218023db1c38328c47a41 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_209a5b6f2cb88451dd4516906e7fcd8f.setIcon(icon_4d941187f55218023db1c38328c47a41);
        
    
        var popup_d7d5f72d22055918324d6afd24e01a9d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_318543927733ba813a89eb7ec377c233 = $(`<div id="html_318543927733ba813a89eb7ec377c233" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 횡성군 우천면 우천면 우항리 758번지 동산연립 앞 도시계획도로(소로3-205호)<br>사고발생일자: 2023-06-15 오전 00:00<br>클러스터: 10</div>`)[0];
                popup_d7d5f72d22055918324d6afd24e01a9d.setContent(html_318543927733ba813a89eb7ec377c233);
            
        

        marker_209a5b6f2cb88451dd4516906e7fcd8f.bindPopup(popup_d7d5f72d22055918324d6afd24e01a9d)
        ;

        
    
    
            var marker_969e2541b453e5e60cab28be8b8e3d7c = L.marker(
                [38.2174325396, 128.593896986],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_33f0c5054c5b0b36c7cde99c4c6f0fc5 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_969e2541b453e5e60cab28be8b8e3d7c.setIcon(icon_33f0c5054c5b0b36c7cde99c4c6f0fc5);
        
    
        var popup_e01a2dac1a51eed3c6ea029c812a3ce8 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_3bc692dbf9feb0fd42317e6b8067bfcc = $(`<div id="html_3bc692dbf9feb0fd42317e6b8067bfcc" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 속초시 영랑동 148-38번지<br>사고발생일자: 2023-07-31 오전 00:00<br>클러스터: 11</div>`)[0];
                popup_e01a2dac1a51eed3c6ea029c812a3ce8.setContent(html_3bc692dbf9feb0fd42317e6b8067bfcc);
            
        

        marker_969e2541b453e5e60cab28be8b8e3d7c.bindPopup(popup_e01a2dac1a51eed3c6ea029c812a3ce8)
        ;

        
    
    
            var marker_dc33a0a67c9a2608dcb5209c04b79d0b = L.marker(
                [38.2173138957, 128.5937595044],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_39efbbe32a50761541c477b547aea546 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_dc33a0a67c9a2608dcb5209c04b79d0b.setIcon(icon_39efbbe32a50761541c477b547aea546);
        
    
        var popup_da448e34d7a014dd5df518a94fada441 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_08f53dadcaad47e65e225aec35ab89a7 = $(`<div id="html_08f53dadcaad47e65e225aec35ab89a7" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 속초시 영랑동 148-38<br>사고발생일자: 2023-06-28 오전 00:00<br>클러스터: 11</div>`)[0];
                popup_da448e34d7a014dd5df518a94fada441.setContent(html_08f53dadcaad47e65e225aec35ab89a7);
            
        

        marker_dc33a0a67c9a2608dcb5209c04b79d0b.bindPopup(popup_da448e34d7a014dd5df518a94fada441)
        ;

        
    
    
            var marker_7ec5b9804b2ba2ca325b90e1df7c808c = L.marker(
                [38.217491965, 128.5935469393],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_44d031711f93543c252796a903b85d2f = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_7ec5b9804b2ba2ca325b90e1df7c808c.setIcon(icon_44d031711f93543c252796a903b85d2f);
        
    
        var popup_c9a85463b585f006f91a96d0610234b8 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_e0c3f3446aa4a6d352451ab12d571488 = $(`<div id="html_e0c3f3446aa4a6d352451ab12d571488" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 속초시 영랑동 148-38<br>사고발생일자: 2023-05-04 오전 00:00<br>클러스터: 11</div>`)[0];
                popup_c9a85463b585f006f91a96d0610234b8.setContent(html_e0c3f3446aa4a6d352451ab12d571488);
            
        

        marker_7ec5b9804b2ba2ca325b90e1df7c808c.bindPopup(popup_c9a85463b585f006f91a96d0610234b8)
        ;

        
    
    
            var marker_5fd8746a9052b3507ee356bfe344cbb1 = L.marker(
                [35.1966425401, 126.8056628531],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_8241e1d775145657f63442d302580985 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_5fd8746a9052b3507ee356bfe344cbb1.setIcon(icon_8241e1d775145657f63442d302580985);
        
    
        var popup_86742c544a0841656471b3c901ce315d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_c3ecaee56b633bdf5bdec5b66dfb3251 = $(`<div id="html_c3ecaee56b633bdf5bdec5b66dfb3251" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 광산구 장덕동 976-1<br>사고발생일자: 2023-07-25 오전 00:00<br>클러스터: 12</div>`)[0];
                popup_86742c544a0841656471b3c901ce315d.setContent(html_c3ecaee56b633bdf5bdec5b66dfb3251);
            
        

        marker_5fd8746a9052b3507ee356bfe344cbb1.bindPopup(popup_86742c544a0841656471b3c901ce315d)
        ;

        
    
    
            var marker_d00a6bcc30a31a5bfca7d11ffa56e60e = L.marker(
                [35.1967313508, 126.8060541933],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_815476d0fbfd53e3d90367eb8c256ce6 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_d00a6bcc30a31a5bfca7d11ffa56e60e.setIcon(icon_815476d0fbfd53e3d90367eb8c256ce6);
        
    
        var popup_2290205f8cf947a33167cda0c6b9e5d9 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ba97d08a799b702ee4fe1412b4de5fff = $(`<div id="html_ba97d08a799b702ee4fe1412b4de5fff" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 광산구 장덕동 972-7<br>사고발생일자: 2023-07-25 오전 00:00<br>클러스터: 12</div>`)[0];
                popup_2290205f8cf947a33167cda0c6b9e5d9.setContent(html_ba97d08a799b702ee4fe1412b4de5fff);
            
        

        marker_d00a6bcc30a31a5bfca7d11ffa56e60e.bindPopup(popup_2290205f8cf947a33167cda0c6b9e5d9)
        ;

        
    
    
            var marker_a7c0daa3eb027c65cfe5f3bb9c35e463 = L.marker(
                [35.1686598687, 126.8166501238],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_af3f0a96b5150b164e259641de6ef6c6 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_a7c0daa3eb027c65cfe5f3bb9c35e463.setIcon(icon_af3f0a96b5150b164e259641de6ef6c6);
        
    
        var popup_0a7ac218c944a1c96cffa604c53907d7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_d0f7f48b620bcc9eef051cdfebf7df72 = $(`<div id="html_d0f7f48b620bcc9eef051cdfebf7df72" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 광산구 월곡동 579-7<br>사고발생일자: 2023-06-30 오전 00:00<br>클러스터: 13</div>`)[0];
                popup_0a7ac218c944a1c96cffa604c53907d7.setContent(html_d0f7f48b620bcc9eef051cdfebf7df72);
            
        

        marker_a7c0daa3eb027c65cfe5f3bb9c35e463.bindPopup(popup_0a7ac218c944a1c96cffa604c53907d7)
        ;

        
    
    
            var marker_bc16fce33407cadfb905a7cdd4aeb6b2 = L.marker(
                [35.1686861799, 126.8166608527],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_02eef8a50b34d8d9a4ea8c91fa5ad1c5 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_bc16fce33407cadfb905a7cdd4aeb6b2.setIcon(icon_02eef8a50b34d8d9a4ea8c91fa5ad1c5);
        
    
        var popup_5977747c09f9c025325f5297a982cef7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_efa98ca57bac4d212f0e8572499bf26b = $(`<div id="html_efa98ca57bac4d212f0e8572499bf26b" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 광산구 월곡동 579-7<br>사고발생일자: 2020-08-11 오전 00:00<br>클러스터: 13</div>`)[0];
                popup_5977747c09f9c025325f5297a982cef7.setContent(html_efa98ca57bac4d212f0e8572499bf26b);
            
        

        marker_bc16fce33407cadfb905a7cdd4aeb6b2.bindPopup(popup_5977747c09f9c025325f5297a982cef7)
        ;

        
    
    
            var marker_87e015ef799b124cef3d4e0affa6cc60 = L.marker(
                [35.1607722848, 126.9327911354],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_125c38ba63d454cd923cd1880e5098df = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_87e015ef799b124cef3d4e0affa6cc60.setIcon(icon_125c38ba63d454cd923cd1880e5098df);
        
    
        var popup_2c0b9b94f433dc009e4cabf916483d5d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_d4fa85b2f25b227bd654bd0a6b229e6d = $(`<div id="html_d4fa85b2f25b227bd654bd0a6b229e6d" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 산수동 133-1<br>사고발생일자: 2023-06-27 오전 00:00<br>클러스터: 14</div>`)[0];
                popup_2c0b9b94f433dc009e4cabf916483d5d.setContent(html_d4fa85b2f25b227bd654bd0a6b229e6d);
            
        

        marker_87e015ef799b124cef3d4e0affa6cc60.bindPopup(popup_2c0b9b94f433dc009e4cabf916483d5d)
        ;

        
    
    
            var marker_fa1c3992d04a05fbb3b67e37093dfaca = L.marker(
                [35.1608573133, 126.9327999273],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1808cf7f24206a466c482bff639040b2 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_fa1c3992d04a05fbb3b67e37093dfaca.setIcon(icon_1808cf7f24206a466c482bff639040b2);
        
    
        var popup_174cb8f08f8be60af827d2056ba0539d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_eb778bd79a1a0e72c8563921e4226956 = $(`<div id="html_eb778bd79a1a0e72c8563921e4226956" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 갈마로 18<br>사고발생일자: 2021-05-21 오전 00:00<br>클러스터: 14</div>`)[0];
                popup_174cb8f08f8be60af827d2056ba0539d.setContent(html_eb778bd79a1a0e72c8563921e4226956);
            
        

        marker_fa1c3992d04a05fbb3b67e37093dfaca.bindPopup(popup_174cb8f08f8be60af827d2056ba0539d)
        ;

        
    
    
            var marker_ad92c7b8d8024b04bbabb05c94bfb58a = L.marker(
                [35.1443575599, 126.9261381355],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_8197f26b2a9b466a2ad1dd5d866bb730 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ad92c7b8d8024b04bbabb05c94bfb58a.setIcon(icon_8197f26b2a9b466a2ad1dd5d866bb730);
        
    
        var popup_871417b46997b43d12667401642cc15a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_943113dc7a839cec1c6103c50bbabf98 = $(`<div id="html_943113dc7a839cec1c6103c50bbabf98" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 서석동 421-1<br>사고발생일자: 2023-06-27 오전 00:00<br>클러스터: 15</div>`)[0];
                popup_871417b46997b43d12667401642cc15a.setContent(html_943113dc7a839cec1c6103c50bbabf98);
            
        

        marker_ad92c7b8d8024b04bbabb05c94bfb58a.bindPopup(popup_871417b46997b43d12667401642cc15a)
        ;

        
    
    
            var marker_ed6b6da6adb4eb7028fa1bbc45512bc1 = L.marker(
                [35.1443619464, 126.9257840839],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_822829d9b8a94511f09a3141d6f5586c = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ed6b6da6adb4eb7028fa1bbc45512bc1.setIcon(icon_822829d9b8a94511f09a3141d6f5586c);
        
    
        var popup_8f285a499109be8b352ac8da1b21b960 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_3abb7f09da0b0e39f914ff25bbdc0d0e = $(`<div id="html_3abb7f09da0b0e39f914ff25bbdc0d0e" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 서석동 421-1<br>사고발생일자: 2023-06-27 오전 00:00<br>클러스터: 15</div>`)[0];
                popup_8f285a499109be8b352ac8da1b21b960.setContent(html_3abb7f09da0b0e39f914ff25bbdc0d0e);
            
        

        marker_ed6b6da6adb4eb7028fa1bbc45512bc1.bindPopup(popup_8f285a499109be8b352ac8da1b21b960)
        ;

        
    
    
            var marker_34db70c49dd96e875b237c45fd88a252 = L.marker(
                [37.3900054342, 126.7413891584],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_d9a5593bd6e58e78ba9f2b630e15073b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_34db70c49dd96e875b237c45fd88a252.setIcon(icon_d9a5593bd6e58e78ba9f2b630e15073b);
        
    
        var popup_bac9625033d19defa9af5ac1957910b8 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_5384bc9e24663b8be3d6e2dd9e02c849 = $(`<div id="html_5384bc9e24663b8be3d6e2dd9e02c849" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 시흥시 월곶동 1004-4번지 외 3필지<br>사고발생일자: 2023-06-18 오전 00:00<br>클러스터: 16</div>`)[0];
                popup_bac9625033d19defa9af5ac1957910b8.setContent(html_5384bc9e24663b8be3d6e2dd9e02c849);
            
        

        marker_34db70c49dd96e875b237c45fd88a252.bindPopup(popup_bac9625033d19defa9af5ac1957910b8)
        ;

        
    
    
            var marker_0daaa35366217268d4f1f5073adeffd6 = L.marker(
                [37.3902217375, 126.7409807921],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_430b0428edee7f2196aa291c2065cba1 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0daaa35366217268d4f1f5073adeffd6.setIcon(icon_430b0428edee7f2196aa291c2065cba1);
        
    
        var popup_cbf9d5cb6808c13661cc948382a7fe7c = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_fe4b4ab85ba5d6fd65eb255508422344 = $(`<div id="html_fe4b4ab85ba5d6fd65eb255508422344" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 시흥시 월곶동 1004-5 인근<br>사고발생일자: 2023-06-13 오전 00:00<br>클러스터: 16</div>`)[0];
                popup_cbf9d5cb6808c13661cc948382a7fe7c.setContent(html_fe4b4ab85ba5d6fd65eb255508422344);
            
        

        marker_0daaa35366217268d4f1f5073adeffd6.bindPopup(popup_cbf9d5cb6808c13661cc948382a7fe7c)
        ;

        
    
    
            var marker_805239ac3ebf79864c291e3aa4ee5c60 = L.marker(
                [38.190093679, 128.6017893676],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_d864a62f9494b3d1b499f7c0462f4f1d = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_805239ac3ebf79864c291e3aa4ee5c60.setIcon(icon_d864a62f9494b3d1b499f7c0462f4f1d);
        
    
        var popup_37231c58dee57b07a73e1410812425d1 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_02b00d2dbdea0e064263e3112a13b5b0 = $(`<div id="html_02b00d2dbdea0e064263e3112a13b5b0" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 속초시 조양동 1452<br>사고발생일자: 2023-03-31 오전 00:00<br>클러스터: 17</div>`)[0];
                popup_37231c58dee57b07a73e1410812425d1.setContent(html_02b00d2dbdea0e064263e3112a13b5b0);
            
        

        marker_805239ac3ebf79864c291e3aa4ee5c60.bindPopup(popup_37231c58dee57b07a73e1410812425d1)
        ;

        
    
    
            var marker_dc41f89fc1f31a0a74e3b543b7026f8b = L.marker(
                [38.1901721845, 128.6012544124],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_01caf931e7b5af2bce7f7a4c342f7538 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_dc41f89fc1f31a0a74e3b543b7026f8b.setIcon(icon_01caf931e7b5af2bce7f7a4c342f7538);
        
    
        var popup_581104726b30c0e47cded0d73f1bd0e9 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_d48410024cbf51aa6f7215f9b1b43a2e = $(`<div id="html_d48410024cbf51aa6f7215f9b1b43a2e" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 속초시 조양동 1452<br>사고발생일자: 2022-08-13 오전 00:00<br>클러스터: 17</div>`)[0];
                popup_581104726b30c0e47cded0d73f1bd0e9.setContent(html_d48410024cbf51aa6f7215f9b1b43a2e);
            
        

        marker_dc41f89fc1f31a0a74e3b543b7026f8b.bindPopup(popup_581104726b30c0e47cded0d73f1bd0e9)
        ;

        
    
    
            var marker_f2faa1b4b6a30e2050ca2b986fa86915 = L.marker(
                [35.1399530663, 126.8820641442],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_9ae75bc5b5c7a12d1c989479b1dfb8c2 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f2faa1b4b6a30e2050ca2b986fa86915.setIcon(icon_9ae75bc5b5c7a12d1c989479b1dfb8c2);
        
    
        var popup_1a501a2d0e9e77e88aed39cbfa58ecb6 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_0a888c3043cbb4f2920b3a314442b3ea = $(`<div id="html_0a888c3043cbb4f2920b3a314442b3ea" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 서구 화정동 1020번지 주변<br>사고발생일자: 2021-05-22 오전 00:00<br>클러스터: 18</div>`)[0];
                popup_1a501a2d0e9e77e88aed39cbfa58ecb6.setContent(html_0a888c3043cbb4f2920b3a314442b3ea);
            
        

        marker_f2faa1b4b6a30e2050ca2b986fa86915.bindPopup(popup_1a501a2d0e9e77e88aed39cbfa58ecb6)
        ;

        
    
    
            var marker_d3804e3a6bd45d6df7a0ddf0948be031 = L.marker(
                [35.1402158547, 126.8818711168],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_343b6c9eb45de09bf3c91d34cfb1328f = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_d3804e3a6bd45d6df7a0ddf0948be031.setIcon(icon_343b6c9eb45de09bf3c91d34cfb1328f);
        
    
        var popup_d3f4353c7df7ea53191d892754334081 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_c9d07626de41158396bc78af72ace9a8 = $(`<div id="html_c9d07626de41158396bc78af72ace9a8" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 서구 화정동 화정동1035<br>사고발생일자: 2023-03-14 오전 00:00<br>클러스터: 18</div>`)[0];
                popup_d3f4353c7df7ea53191d892754334081.setContent(html_c9d07626de41158396bc78af72ace9a8);
            
        

        marker_d3804e3a6bd45d6df7a0ddf0948be031.bindPopup(popup_d3f4353c7df7ea53191d892754334081)
        ;

        
    
    
            var marker_5aef94fea83beb5bebee2659401fe18e = L.marker(
                [37.7748051255, 128.9327716097],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_618721ba9c65ed37443995c164b73dd0 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_5aef94fea83beb5bebee2659401fe18e.setIcon(icon_618721ba9c65ed37443995c164b73dd0);
        
    
        var popup_0be03fd5ce205e6ba3fd998c461c084e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_6749d908a8b6d907578865f753088e2c = $(`<div id="html_6749d908a8b6d907578865f753088e2c" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 강릉시 송정동 송정동 187-6<br>사고발생일자: 2020-08-06 오전 00:00<br>클러스터: 19</div>`)[0];
                popup_0be03fd5ce205e6ba3fd998c461c084e.setContent(html_6749d908a8b6d907578865f753088e2c);
            
        

        marker_5aef94fea83beb5bebee2659401fe18e.bindPopup(popup_0be03fd5ce205e6ba3fd998c461c084e)
        ;

        
    
    
            var marker_49e180c7379252c6d554e5be86b5f432 = L.marker(
                [37.7748496473, 128.9326435342],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_d301eb1a80b5adab0354032bb0ae1f40 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_49e180c7379252c6d554e5be86b5f432.setIcon(icon_d301eb1a80b5adab0354032bb0ae1f40);
        
    
        var popup_e1f421e296cc50a296d5cd45451a7bba = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1ecbe1536fa4558357c474ba74aa983f = $(`<div id="html_1ecbe1536fa4558357c474ba74aa983f" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 강릉시 송정동 송정동 187-4(팔송길 6 앞)<br>사고발생일자: 2021-06-08 오전 00:00<br>클러스터: 19</div>`)[0];
                popup_e1f421e296cc50a296d5cd45451a7bba.setContent(html_1ecbe1536fa4558357c474ba74aa983f);
            
        

        marker_49e180c7379252c6d554e5be86b5f432.bindPopup(popup_e1f421e296cc50a296d5cd45451a7bba)
        ;

        
    
    
            var marker_ad33286068a37d2ec0083f00533fd115 = L.marker(
                [37.7748256383, 128.9326486155],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_ebd0773543423b2da7d99b7353514ad9 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ad33286068a37d2ec0083f00533fd115.setIcon(icon_ebd0773543423b2da7d99b7353514ad9);
        
    
        var popup_dbd3388a99016fadaf92b3b1a59bccf4 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a6e31d716d305f603e7ab43adce671c8 = $(`<div id="html_a6e31d716d305f603e7ab43adce671c8" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 강릉시 송정동 187-4번지 일원<br>사고발생일자: 2023-02-27 오전 00:00<br>클러스터: 19</div>`)[0];
                popup_dbd3388a99016fadaf92b3b1a59bccf4.setContent(html_a6e31d716d305f603e7ab43adce671c8);
            
        

        marker_ad33286068a37d2ec0083f00533fd115.bindPopup(popup_dbd3388a99016fadaf92b3b1a59bccf4)
        ;

        
    
    
            var marker_f8e85629da751679b6f5c1bfb7201517 = L.marker(
                [37.644013731, 126.7877946013],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1473254ae1b7329fdea493918cb93c6f = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f8e85629da751679b6f5c1bfb7201517.setIcon(icon_1473254ae1b7329fdea493918cb93c6f);
        
    
        var popup_4deda6441e3055ea45d0ec8d133554ac = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ad403b98ad77e4e934b65436a8123ec1 = $(`<div id="html_ad403b98ad77e4e934b65436a8123ec1" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산동구 백석동 1297<br>사고발생일자: 2022-06-09 오전 00:00<br>클러스터: 20</div>`)[0];
                popup_4deda6441e3055ea45d0ec8d133554ac.setContent(html_ad403b98ad77e4e934b65436a8123ec1);
            
        

        marker_f8e85629da751679b6f5c1bfb7201517.bindPopup(popup_4deda6441e3055ea45d0ec8d133554ac)
        ;

        
    
    
            var marker_f0b01d4e4ce7422c3e938e0242c17c20 = L.marker(
                [37.6441029318, 126.7882505769],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_25790dd4abba0178b79df5d7af955993 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f0b01d4e4ce7422c3e938e0242c17c20.setIcon(icon_25790dd4abba0178b79df5d7af955993);
        
    
        var popup_23876564f2e80a79801a786ab62f6e88 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ddf8171f09fb028fbdc8d25a40005a5d = $(`<div id="html_ddf8171f09fb028fbdc8d25a40005a5d" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산동구 백석동 1297<br>사고발생일자: 2022-06-06 오전 00:00<br>클러스터: 20</div>`)[0];
                popup_23876564f2e80a79801a786ab62f6e88.setContent(html_ddf8171f09fb028fbdc8d25a40005a5d);
            
        

        marker_f0b01d4e4ce7422c3e938e0242c17c20.bindPopup(popup_23876564f2e80a79801a786ab62f6e88)
        ;

        
    
    
            var marker_fbf1b4d23db630814298a1ea4a7e5f5a = L.marker(
                [37.6439712545, 126.7880413645],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_e93ee75fecce6b03ca63f8e1d0e31df7 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_fbf1b4d23db630814298a1ea4a7e5f5a.setIcon(icon_e93ee75fecce6b03ca63f8e1d0e31df7);
        
    
        var popup_982a7649da9de74f89ceefc0a09385c5 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_5e243747764bec671d6869029f7a4fd8 = $(`<div id="html_5e243747764bec671d6869029f7a4fd8" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산동구 백석동 1297<br>사고발생일자: 2022-05-31 오전 00:00<br>클러스터: 20</div>`)[0];
                popup_982a7649da9de74f89ceefc0a09385c5.setContent(html_5e243747764bec671d6869029f7a4fd8);
            
        

        marker_fbf1b4d23db630814298a1ea4a7e5f5a.bindPopup(popup_982a7649da9de74f89ceefc0a09385c5)
        ;

        
    
    
            var marker_c3849daace1e7eccd2500537736d368e = L.marker(
                [37.6436734, 126.7878528],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_eff9e79e1c9c47624db989bcf6414d36 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_c3849daace1e7eccd2500537736d368e.setIcon(icon_eff9e79e1c9c47624db989bcf6414d36);
        
    
        var popup_1c0f2766b92e533f5f1e7595a585209d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_c665528e81871fbddd7e6757120d8d18 = $(`<div id="html_c665528e81871fbddd7e6757120d8d18" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산동구 백석동  1288-1<br>사고발생일자: 2019-05-23 오전 00:00<br>클러스터: 20</div>`)[0];
                popup_1c0f2766b92e533f5f1e7595a585209d.setContent(html_c665528e81871fbddd7e6757120d8d18);
            
        

        marker_c3849daace1e7eccd2500537736d368e.bindPopup(popup_1c0f2766b92e533f5f1e7595a585209d)
        ;

        
    
    
            var marker_628eec56fdc1a6d736559f17200b2599 = L.marker(
                [37.6440264982, 126.7883149193],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_a05fa651fb3dd2812ab3762fa9bd18b7 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_628eec56fdc1a6d736559f17200b2599.setIcon(icon_a05fa651fb3dd2812ab3762fa9bd18b7);
        
    
        var popup_fd45d55a8eb386b7b9ebbba87fa82215 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f0c0db591d41190d0fb84ca44cc3a8ba = $(`<div id="html_f0c0db591d41190d0fb84ca44cc3a8ba" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산동구 백석동 1297<br>사고발생일자: 2022-10-05 오전 00:00<br>클러스터: 20</div>`)[0];
                popup_fd45d55a8eb386b7b9ebbba87fa82215.setContent(html_f0c0db591d41190d0fb84ca44cc3a8ba);
            
        

        marker_628eec56fdc1a6d736559f17200b2599.bindPopup(popup_fd45d55a8eb386b7b9ebbba87fa82215)
        ;

        
    
    
            var marker_64e6421d4fad82f5e8ba87d1e8dc9e0f = L.marker(
                [37.6436734, 126.7878528],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_7f7dee9262005f3cca8a568e660e048b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_64e6421d4fad82f5e8ba87d1e8dc9e0f.setIcon(icon_7f7dee9262005f3cca8a568e660e048b);
        
    
        var popup_1b1094989374582ff8bd20d3516949e2 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_6758a15103a2d96ea89f40fc696723e5 = $(`<div id="html_6758a15103a2d96ea89f40fc696723e5" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산동구 백석동 1460<br>사고발생일자: 2019-07-03 오전 00:00<br>클러스터: 20</div>`)[0];
                popup_1b1094989374582ff8bd20d3516949e2.setContent(html_6758a15103a2d96ea89f40fc696723e5);
            
        

        marker_64e6421d4fad82f5e8ba87d1e8dc9e0f.bindPopup(popup_1b1094989374582ff8bd20d3516949e2)
        ;

        
    
    
            var marker_4f14385123304c97b7a02e3ad23b4e90 = L.marker(
                [38.1174338362, 128.6318926006],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_a804d53c69cec7b46317e7d21bfbdf33 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_4f14385123304c97b7a02e3ad23b4e90.setIcon(icon_a804d53c69cec7b46317e7d21bfbdf33);
        
    
        var popup_5d523704cc808724572cbe30ea449619 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_e3ffe6e42048c83c26d6708519efbfe0 = $(`<div id="html_e3ffe6e42048c83c26d6708519efbfe0" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 양양군 강현면 주청리2-15번지  신축 공사장 인근<br>사고발생일자: 2022-05-06 오전 00:00<br>클러스터: 21</div>`)[0];
                popup_5d523704cc808724572cbe30ea449619.setContent(html_e3ffe6e42048c83c26d6708519efbfe0);
            
        

        marker_4f14385123304c97b7a02e3ad23b4e90.bindPopup(popup_5d523704cc808724572cbe30ea449619)
        ;

        
    
    
            var marker_bbc60597dcd98b9dd82d6bde8fc9b196 = L.marker(
                [38.117451765, 128.6319266681],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_508fd63313e18daf3a6f3da74e564d0b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_bbc60597dcd98b9dd82d6bde8fc9b196.setIcon(icon_508fd63313e18daf3a6f3da74e564d0b);
        
    
        var popup_1600a5072c7c48e82d9a29099487484c = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_16d6abb7ae4bf907126d8dd333c73a02 = $(`<div id="html_16d6abb7ae4bf907126d8dd333c73a02" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 양양군 강현면 주청리 2-15<br>사고발생일자: 2022-08-24 오전 00:00<br>클러스터: 21</div>`)[0];
                popup_1600a5072c7c48e82d9a29099487484c.setContent(html_16d6abb7ae4bf907126d8dd333c73a02);
            
        

        marker_bbc60597dcd98b9dd82d6bde8fc9b196.bindPopup(popup_1600a5072c7c48e82d9a29099487484c)
        ;

        
    
    
            var marker_3eaa1a0661c527f0edffb85264aae4e3 = L.marker(
                [38.1176330978, 128.6323529455],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1c152c57f356d779ae1c87cb2b1439d7 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_3eaa1a0661c527f0edffb85264aae4e3.setIcon(icon_1c152c57f356d779ae1c87cb2b1439d7);
        
    
        var popup_53f98316d9ac2386c436e4886d67243a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_920861120bca458e0229c7ee733c68ae = $(`<div id="html_920861120bca458e0229c7ee733c68ae" style="width: 100.0%; height: 100.0%;">사고발생 위치: 강원특별자치도 양양군 강현면 주청리 2-15<br>사고발생일자: 2022-08-03 오전 00:00<br>클러스터: 21</div>`)[0];
                popup_53f98316d9ac2386c436e4886d67243a.setContent(html_920861120bca458e0229c7ee733c68ae);
            
        

        marker_3eaa1a0661c527f0edffb85264aae4e3.bindPopup(popup_53f98316d9ac2386c436e4886d67243a)
        ;

        
    
    
            var marker_0f8614753f4706b24a9076aad0a71c31 = L.marker(
                [35.7947429982, 127.1359621411],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_6f106c00f20cedfda3d0eba17ea28cc5 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0f8614753f4706b24a9076aad0a71c31.setIcon(icon_6f106c00f20cedfda3d0eba17ea28cc5);
        
    
        var popup_6d56a009dc85dcdad75065dbc3979fd6 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_3b7e27b172bb648fc37ca6930c191c15 = $(`<div id="html_3b7e27b172bb648fc37ca6930c191c15" style="width: 100.0%; height: 100.0%;">사고발생 위치: 전북특별자치도 전주시 완산구 평화동1가 725-5<br>사고발생일자: 2022-08-15 오전 00:00<br>클러스터: 22</div>`)[0];
                popup_6d56a009dc85dcdad75065dbc3979fd6.setContent(html_3b7e27b172bb648fc37ca6930c191c15);
            
        

        marker_0f8614753f4706b24a9076aad0a71c31.bindPopup(popup_6d56a009dc85dcdad75065dbc3979fd6)
        ;

        
    
    
            var marker_7020a2e2380e9e373edd703478a02a53 = L.marker(
                [35.7948983411, 127.13593266],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_2b73879410043fd40277704f09030b61 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_7020a2e2380e9e373edd703478a02a53.setIcon(icon_2b73879410043fd40277704f09030b61);
        
    
        var popup_1f2dcdb73b839b77fcf3622337e51c48 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_38adbef08aea54a50e972d12299b6b26 = $(`<div id="html_38adbef08aea54a50e972d12299b6b26" style="width: 100.0%; height: 100.0%;">사고발생 위치: 전북특별자치도 전주시 완산구 평화동1가 725-5<br>사고발생일자: 2022-06-24 오전 00:00<br>클러스터: 22</div>`)[0];
                popup_1f2dcdb73b839b77fcf3622337e51c48.setContent(html_38adbef08aea54a50e972d12299b6b26);
            
        

        marker_7020a2e2380e9e373edd703478a02a53.bindPopup(popup_1f2dcdb73b839b77fcf3622337e51c48)
        ;

        
    
    
            var marker_d53a01a4929c1b9bc5c3bfeda3b5e4eb = L.marker(
                [35.7949244481, 127.1359219312],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_f9153424c381f73f7986e389de2c1a8a = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_d53a01a4929c1b9bc5c3bfeda3b5e4eb.setIcon(icon_f9153424c381f73f7986e389de2c1a8a);
        
    
        var popup_44e06a9ca602bc291f3ff23e23c42b99 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a5c93d515bb3f7b06490cc4cc1604f7f = $(`<div id="html_a5c93d515bb3f7b06490cc4cc1604f7f" style="width: 100.0%; height: 100.0%;">사고발생 위치: 전북특별자치도 전주시 완산구 평화동1가 725-5<br>사고발생일자: 2022-03-09 오전 00:00<br>클러스터: 22</div>`)[0];
                popup_44e06a9ca602bc291f3ff23e23c42b99.setContent(html_a5c93d515bb3f7b06490cc4cc1604f7f);
            
        

        marker_d53a01a4929c1b9bc5c3bfeda3b5e4eb.bindPopup(popup_44e06a9ca602bc291f3ff23e23c42b99)
        ;

        
    
    
            var marker_ef71ec3ec996b079b62b9ad56badfc7e = L.marker(
                [35.7947604029, 127.1358924037],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_79b01414f1317d3ddb0e8d69926efbda = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ef71ec3ec996b079b62b9ad56badfc7e.setIcon(icon_79b01414f1317d3ddb0e8d69926efbda);
        
    
        var popup_b858192ae3f9cc3fc822fcbae279176e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_740515509824dac118d8ea065b8b3bc0 = $(`<div id="html_740515509824dac118d8ea065b8b3bc0" style="width: 100.0%; height: 100.0%;">사고발생 위치: 전북특별자치도 전주시 완산구 평화동1가 725-5<br>사고발생일자: 2022-08-16 오전 00:00<br>클러스터: 22</div>`)[0];
                popup_b858192ae3f9cc3fc822fcbae279176e.setContent(html_740515509824dac118d8ea065b8b3bc0);
            
        

        marker_ef71ec3ec996b079b62b9ad56badfc7e.bindPopup(popup_b858192ae3f9cc3fc822fcbae279176e)
        ;

        
    
    
            var marker_9791c12574027c511504eab44b308379 = L.marker(
                [35.9419540614, 126.5312731801],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_e3a730f474aebb1df4411664db935dc7 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_9791c12574027c511504eab44b308379.setIcon(icon_e3a730f474aebb1df4411664db935dc7);
        
    
        var popup_cb17b4123ad0908969ccd35e18a5e54b = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_c022e795dc51e8545cdefe866879abd3 = $(`<div id="html_c022e795dc51e8545cdefe866879abd3" style="width: 100.0%; height: 100.0%;">사고발생 위치: 전북특별자치도 군산시 비응도동 42(43-1 앞)<br>사고발생일자: 2020-09-15 오전 00:00<br>클러스터: 23</div>`)[0];
                popup_cb17b4123ad0908969ccd35e18a5e54b.setContent(html_c022e795dc51e8545cdefe866879abd3);
            
        

        marker_9791c12574027c511504eab44b308379.bindPopup(popup_cb17b4123ad0908969ccd35e18a5e54b)
        ;

        
    
    
            var marker_de2b57a47a2aee0e1d26c510916cf4a5 = L.marker(
                [35.9419920082, 126.5313111797],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_0da6e1c17410edd7e3279588fe28f029 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_de2b57a47a2aee0e1d26c510916cf4a5.setIcon(icon_0da6e1c17410edd7e3279588fe28f029);
        
    
        var popup_c972cd174e9818eecce0cc60bb054e74 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f93859b39b7bc21a52f5a58f1f739190 = $(`<div id="html_f93859b39b7bc21a52f5a58f1f739190" style="width: 100.0%; height: 100.0%;">사고발생 위치: 전북특별자치도 군산시 비응도동 41-4<br>사고발생일자: 2022-06-30 오전 00:00<br>클러스터: 23</div>`)[0];
                popup_c972cd174e9818eecce0cc60bb054e74.setContent(html_f93859b39b7bc21a52f5a58f1f739190);
            
        

        marker_de2b57a47a2aee0e1d26c510916cf4a5.bindPopup(popup_c972cd174e9818eecce0cc60bb054e74)
        ;

        
    
    
            var marker_5dcf312196c56f67fdaf31cf5d94f42a = L.marker(
                [37.6194469, 126.8372169],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_69634269e7862089ea157d47b8141f10 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_5dcf312196c56f67fdaf31cf5d94f42a.setIcon(icon_69634269e7862089ea157d47b8141f10);
        
    
        var popup_43322886c042c3e8191f25e2a9a6d2fb = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_aded307993bcc5c0fca20b0f9ed467e6 = $(`<div id="html_aded307993bcc5c0fca20b0f9ed467e6" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 덕양구 행신동 1121<br>사고발생일자: 2019-07-22 오전 00:00<br>클러스터: 24</div>`)[0];
                popup_43322886c042c3e8191f25e2a9a6d2fb.setContent(html_aded307993bcc5c0fca20b0f9ed467e6);
            
        

        marker_5dcf312196c56f67fdaf31cf5d94f42a.bindPopup(popup_43322886c042c3e8191f25e2a9a6d2fb)
        ;

        
    
    
            var marker_18ec1f3531c8b0fe51c742cb86c9864b = L.marker(
                [37.6194469, 126.8372169],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_7ea98e40efd7ce6b1d55998522fad553 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_18ec1f3531c8b0fe51c742cb86c9864b.setIcon(icon_7ea98e40efd7ce6b1d55998522fad553);
        
    
        var popup_7626b2674add0b51a44c947d480306ba = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1e3b51fdff0dcac6625ea74f03b25655 = $(`<div id="html_1e3b51fdff0dcac6625ea74f03b25655" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 행신동 736-7<br>사고발생일자: 2021-07-24 오전 00:00<br>클러스터: 24</div>`)[0];
                popup_7626b2674add0b51a44c947d480306ba.setContent(html_1e3b51fdff0dcac6625ea74f03b25655);
            
        

        marker_18ec1f3531c8b0fe51c742cb86c9864b.bindPopup(popup_7626b2674add0b51a44c947d480306ba)
        ;

        
    
    
            var marker_cb692f28c2a9642a82cf74454d5f2435 = L.marker(
                [35.1634352379, 126.9243911688],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_5f6b5c170b26caf55150abb9c4546bcb = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_cb692f28c2a9642a82cf74454d5f2435.setIcon(icon_5f6b5c170b26caf55150abb9c4546bcb);
        
    
        var popup_85a9aa2897350bd8d26705a3ce825e6a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_9011b9c46de0bd45f0830f41e24d08ab = $(`<div id="html_9011b9c46de0bd45f0830f41e24d08ab" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 계림동 계림동 1072<br>사고발생일자: 2021-07-06 오전 00:00<br>클러스터: 25</div>`)[0];
                popup_85a9aa2897350bd8d26705a3ce825e6a.setContent(html_9011b9c46de0bd45f0830f41e24d08ab);
            
        

        marker_cb692f28c2a9642a82cf74454d5f2435.bindPopup(popup_85a9aa2897350bd8d26705a3ce825e6a)
        ;

        
    
    
            var marker_afc00bce454344f83a3520a61929000c = L.marker(
                [35.163555999, 126.9242172591],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_9321915ab12f0eab8f3089673ae029e7 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_afc00bce454344f83a3520a61929000c.setIcon(icon_9321915ab12f0eab8f3089673ae029e7);
        
    
        var popup_d5ae37e1203514f1bb1db54620443a39 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_421bf99b250b0d9e7a59b6b84645217a = $(`<div id="html_421bf99b250b0d9e7a59b6b84645217a" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 계림동 1070<br>사고발생일자: 2020-08-08 오전 00:00<br>클러스터: 25</div>`)[0];
                popup_d5ae37e1203514f1bb1db54620443a39.setContent(html_421bf99b250b0d9e7a59b6b84645217a);
            
        

        marker_afc00bce454344f83a3520a61929000c.bindPopup(popup_d5ae37e1203514f1bb1db54620443a39)
        ;

        
    
    
            var marker_f20b204db1d4523c9d12148e90113f8d = L.marker(
                [35.9974307979, 129.389134004],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1c157ae223010b45a0a1589730e6da6f = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f20b204db1d4523c9d12148e90113f8d.setIcon(icon_1c157ae223010b45a0a1589730e6da6f);
        
    
        var popup_9990fca85551a8bbe6bfaea9a0ac5980 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_9dcf0dcf947e6a92813400bab9c6b445 = $(`<div id="html_9dcf0dcf947e6a92813400bab9c6b445" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경상북도 포항시 남구 동촌동 543-67<br>사고발생일자: 2021-04-02 오전 00:00<br>클러스터: 26</div>`)[0];
                popup_9990fca85551a8bbe6bfaea9a0ac5980.setContent(html_9dcf0dcf947e6a92813400bab9c6b445);
            
        

        marker_f20b204db1d4523c9d12148e90113f8d.bindPopup(popup_9990fca85551a8bbe6bfaea9a0ac5980)
        ;

        
    
    
            var marker_06a1a0ddb42b9ae76a77a2a63579e8b9 = L.marker(
                [35.997274556, 129.3889784359],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_26cc9147f2dbdd1ebe30cf7aafebf123 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_06a1a0ddb42b9ae76a77a2a63579e8b9.setIcon(icon_26cc9147f2dbdd1ebe30cf7aafebf123);
        
    
        var popup_10d203b65caec68aebe335c7c5d64d18 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_09e259dcfec5e8fcebc82e5f293f2b0a = $(`<div id="html_09e259dcfec5e8fcebc82e5f293f2b0a" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경상북도 포항시 남구 동촌동 545-6<br>사고발생일자: 2021-04-02 오전 00:00<br>클러스터: 26</div>`)[0];
                popup_10d203b65caec68aebe335c7c5d64d18.setContent(html_09e259dcfec5e8fcebc82e5f293f2b0a);
            
        

        marker_06a1a0ddb42b9ae76a77a2a63579e8b9.bindPopup(popup_10d203b65caec68aebe335c7c5d64d18)
        ;

        
    
    
            var marker_3701ffb40d2e62304ef787664e4e27a0 = L.marker(
                [36.0013497627, 129.3841129088],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_e7714e1e080d9fcbb8c34eea11fd37b7 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_3701ffb40d2e62304ef787664e4e27a0.setIcon(icon_e7714e1e080d9fcbb8c34eea11fd37b7);
        
    
        var popup_33761b04dbc77b4842ce424824afdcde = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f3cb39e45310bf60aba3f44cfd959ea6 = $(`<div id="html_f3cb39e45310bf60aba3f44cfd959ea6" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경상북도 포항시 남구 동촌동 800-3<br>사고발생일자: 2021-04-02 오전 00:00<br>클러스터: 27</div>`)[0];
                popup_33761b04dbc77b4842ce424824afdcde.setContent(html_f3cb39e45310bf60aba3f44cfd959ea6);
            
        

        marker_3701ffb40d2e62304ef787664e4e27a0.bindPopup(popup_33761b04dbc77b4842ce424824afdcde)
        ;

        
    
    
            var marker_9c6c2eac0104a8bfd28b189a9c2c722e = L.marker(
                [36.0011935286, 129.3842631125],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_91cb869ef5ae33a7d7d80a9a8b96d7d6 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_9c6c2eac0104a8bfd28b189a9c2c722e.setIcon(icon_91cb869ef5ae33a7d7d80a9a8b96d7d6);
        
    
        var popup_5dce94900cf6c077dcbfbc7350c6f42f = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_516557d4fe6cfaf4045cad1e6a870cab = $(`<div id="html_516557d4fe6cfaf4045cad1e6a870cab" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경상북도 포항시 남구 동촌동 800-3<br>사고발생일자: 2021-04-02 오전 00:00<br>클러스터: 27</div>`)[0];
                popup_5dce94900cf6c077dcbfbc7350c6f42f.setContent(html_516557d4fe6cfaf4045cad1e6a870cab);
            
        

        marker_9c6c2eac0104a8bfd28b189a9c2c722e.bindPopup(popup_5dce94900cf6c077dcbfbc7350c6f42f)
        ;

        
    
    
            var marker_e6d440de4761f3bdb9a8e88dc63d6ce3 = L.marker(
                [35.1708013279, 126.8825790638],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_b8d861176b9b5ecc6bbbff8d72149e96 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_e6d440de4761f3bdb9a8e88dc63d6ce3.setIcon(icon_b8d861176b9b5ecc6bbbff8d72149e96);
        
    
        var popup_68372424241b75da4adfda7d94e16f5b = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_11c2f410db94716a56a427c9d5838bec = $(`<div id="html_11c2f410db94716a56a427c9d5838bec" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 북구 동림동 26-1<br>사고발생일자: 2020-08-21 오전 00:00<br>클러스터: 28</div>`)[0];
                popup_68372424241b75da4adfda7d94e16f5b.setContent(html_11c2f410db94716a56a427c9d5838bec);
            
        

        marker_e6d440de4761f3bdb9a8e88dc63d6ce3.bindPopup(popup_68372424241b75da4adfda7d94e16f5b)
        ;

        
    
    
            var marker_43160501c3d116d09b4723b98228eae7 = L.marker(
                [35.1708421788, 126.8822775721],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_5521b4e04760b6e464a706b653c1d29e = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_43160501c3d116d09b4723b98228eae7.setIcon(icon_5521b4e04760b6e464a706b653c1d29e);
        
    
        var popup_ac847d675c590e05bbf0c156ba1e908f = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b32f6ad0cc9e011d679a2c004e721f2a = $(`<div id="html_b32f6ad0cc9e011d679a2c004e721f2a" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 북구 운암동 1578<br>사고발생일자: 2020-08-19 오전 00:00<br>클러스터: 28</div>`)[0];
                popup_ac847d675c590e05bbf0c156ba1e908f.setContent(html_b32f6ad0cc9e011d679a2c004e721f2a);
            
        

        marker_43160501c3d116d09b4723b98228eae7.bindPopup(popup_ac847d675c590e05bbf0c156ba1e908f)
        ;

        
    
    
            var marker_ebf0b606d810c00cc8af6d9a2247bca4 = L.marker(
                [37.6844028, 126.7690149],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_39a664def4107669d7f03efe705d6bab = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ebf0b606d810c00cc8af6d9a2247bca4.setIcon(icon_39a664def4107669d7f03efe705d6bab);
        
    
        var popup_be253096ee8c28bc6441d3c74233b103 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b6c2e0fca346092a4c4c9c749152e512 = $(`<div id="html_b6c2e0fca346092a4c4c9c749152e512" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산서구 일산동  2340<br>사고발생일자: 2018-08-16 오전 00:00<br>클러스터: 29</div>`)[0];
                popup_be253096ee8c28bc6441d3c74233b103.setContent(html_b6c2e0fca346092a4c4c9c749152e512);
            
        

        marker_ebf0b606d810c00cc8af6d9a2247bca4.bindPopup(popup_be253096ee8c28bc6441d3c74233b103)
        ;

        
    
    
            var marker_5bb6b83e9c37cb51ef2293e0617d3c60 = L.marker(
                [37.6844028, 126.7690149],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_73a5f33d642d2baaf4d43ef4be9aca11 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_5bb6b83e9c37cb51ef2293e0617d3c60.setIcon(icon_73a5f33d642d2baaf4d43ef4be9aca11);
        
    
        var popup_448a0fdf84919e0e0e1e4ff012d26a0d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ce14d876bf858d128488ab6f03483f4f = $(`<div id="html_ce14d876bf858d128488ab6f03483f4f" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산서구 일산동  1398<br>사고발생일자: 2019-06-11 오전 00:00<br>클러스터: 29</div>`)[0];
                popup_448a0fdf84919e0e0e1e4ff012d26a0d.setContent(html_ce14d876bf858d128488ab6f03483f4f);
            
        

        marker_5bb6b83e9c37cb51ef2293e0617d3c60.bindPopup(popup_448a0fdf84919e0e0e1e4ff012d26a0d)
        ;

        
    
    
            var marker_580efbc7744fc66f15facd36b316c755 = L.marker(
                [37.6839918737, 126.7692336515],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_bc01d85f628851e054e2f840ab67f7a4 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_580efbc7744fc66f15facd36b316c755.setIcon(icon_bc01d85f628851e054e2f840ab67f7a4);
        
    
        var popup_ab01bdf22184dbb22d5eef2b00e7164a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_7b91a8cedccc391f344c1ab2860b6576 = $(`<div id="html_7b91a8cedccc391f344c1ab2860b6576" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산서구 일산동 1025-13<br>사고발생일자: 2020-08-14 오전 00:00<br>클러스터: 29</div>`)[0];
                popup_ab01bdf22184dbb22d5eef2b00e7164a.setContent(html_7b91a8cedccc391f344c1ab2860b6576);
            
        

        marker_580efbc7744fc66f15facd36b316c755.bindPopup(popup_ab01bdf22184dbb22d5eef2b00e7164a)
        ;

        
    
    
            var marker_69dc11dcb8e3163bdf4d62630dfbb0ed = L.marker(
                [37.6844028, 126.7690149],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_609e68ca5703b3ec0936ed6cff28c981 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_69dc11dcb8e3163bdf4d62630dfbb0ed.setIcon(icon_609e68ca5703b3ec0936ed6cff28c981);
        
    
        var popup_0eddde14c9cdd65df56831d990cc047a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b6d5c4184c36e24bcc46e478dff66d97 = $(`<div id="html_b6d5c4184c36e24bcc46e478dff66d97" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산서구 일산동 1979<br>사고발생일자: 2019-09-26 오전 00:00<br>클러스터: 29</div>`)[0];
                popup_0eddde14c9cdd65df56831d990cc047a.setContent(html_b6d5c4184c36e24bcc46e478dff66d97);
            
        

        marker_69dc11dcb8e3163bdf4d62630dfbb0ed.bindPopup(popup_0eddde14c9cdd65df56831d990cc047a)
        ;

        
    
    
            var marker_9ee58edf66183f50f5168dbc2c9a681f = L.marker(
                [36.6336514854, 127.4643646297],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_2446c131f3b71bb844e34fa67a2a62e0 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_9ee58edf66183f50f5168dbc2c9a681f.setIcon(icon_2446c131f3b71bb844e34fa67a2a62e0);
        
    
        var popup_b851a56abcb995ba20e10be69caa8619 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_dc3a2e5eb3892a54c2585d6c57e1db54 = $(`<div id="html_dc3a2e5eb3892a54c2585d6c57e1db54" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 서원구 사창동 265-5<br>사고발생일자: 2020-08-13 오전 00:00<br>클러스터: 30</div>`)[0];
                popup_b851a56abcb995ba20e10be69caa8619.setContent(html_dc3a2e5eb3892a54c2585d6c57e1db54);
            
        

        marker_9ee58edf66183f50f5168dbc2c9a681f.bindPopup(popup_b851a56abcb995ba20e10be69caa8619)
        ;

        
    
    
            var marker_739d0b48b89a4f74ad3b7695aeb1b64e = L.marker(
                [36.6337676899, 127.4643603543],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_bd604a682172eb4305e7539d808b2895 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_739d0b48b89a4f74ad3b7695aeb1b64e.setIcon(icon_bd604a682172eb4305e7539d808b2895);
        
    
        var popup_2b4281abb18d769fcc248ae28a75ae34 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_4b5e06f26fe99ea505cf66c124b469ff = $(`<div id="html_4b5e06f26fe99ea505cf66c124b469ff" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 서원구 사창동 265-3<br>사고발생일자: 2020-08-13 오전 00:00<br>클러스터: 30</div>`)[0];
                popup_2b4281abb18d769fcc248ae28a75ae34.setContent(html_4b5e06f26fe99ea505cf66c124b469ff);
            
        

        marker_739d0b48b89a4f74ad3b7695aeb1b64e.bindPopup(popup_2b4281abb18d769fcc248ae28a75ae34)
        ;

        
    
    
            var marker_edc0519d146ad592090d9be75d106589 = L.marker(
                [37.4899024408, 126.6750656984],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_cfdd25a2521c8f169c450a6e9f2369c9 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_edc0519d146ad592090d9be75d106589.setIcon(icon_cfdd25a2521c8f169c450a6e9f2369c9);
        
    
        var popup_2ac664156afd8895381b417cb9a40014 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_e2291879505ea062ed87b9abbc67dc57 = $(`<div id="html_e2291879505ea062ed87b9abbc67dc57" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 서구 가좌동 가좌역2번출입구 E/V 옆 환기구 전면 보도<br>사고발생일자: 2020-08-13 오전 00:00<br>클러스터: 31</div>`)[0];
                popup_2ac664156afd8895381b417cb9a40014.setContent(html_e2291879505ea062ed87b9abbc67dc57);
            
        

        marker_edc0519d146ad592090d9be75d106589.bindPopup(popup_2ac664156afd8895381b417cb9a40014)
        ;

        
    
    
            var marker_197d52fb9f81ca357b34664df8965a92 = L.marker(
                [37.4899779928, 126.6751367769],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_b652ec4a7d46e4aab42cc007aa857054 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_197d52fb9f81ca357b34664df8965a92.setIcon(icon_b652ec4a7d46e4aab42cc007aa857054);
        
    
        var popup_1e87dfbaff4f367467474653cc222a99 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_562dad805df2e3cf18ed8fad343ca058 = $(`<div id="html_562dad805df2e3cf18ed8fad343ca058" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 서구 가좌동 가좌역2번출입구 E/V옆 전방 도로<br>사고발생일자: 2020-08-13 오전 00:00<br>클러스터: 31</div>`)[0];
                popup_1e87dfbaff4f367467474653cc222a99.setContent(html_562dad805df2e3cf18ed8fad343ca058);
            
        

        marker_197d52fb9f81ca357b34664df8965a92.bindPopup(popup_1e87dfbaff4f367467474653cc222a99)
        ;

        
    
    
            var marker_636eca0bcc13ea3e7f22276ed71421e3 = L.marker(
                [37.5408979165, 127.203031213],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_76cfb94bf34ceffdcd50b4dd3b72750b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_636eca0bcc13ea3e7f22276ed71421e3.setIcon(icon_76cfb94bf34ceffdcd50b4dd3b72750b);
        
    
        var popup_d71546f00cc3cc0f03aafb153e36d648 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_686d5127e2028cbdb439e92f65847471 = $(`<div id="html_686d5127e2028cbdb439e92f65847471" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 하남시 덕풍동 396-1번지<br>사고발생일자: 2020-08-10 오전 00:00<br>클러스터: 32</div>`)[0];
                popup_d71546f00cc3cc0f03aafb153e36d648.setContent(html_686d5127e2028cbdb439e92f65847471);
            
        

        marker_636eca0bcc13ea3e7f22276ed71421e3.bindPopup(popup_d71546f00cc3cc0f03aafb153e36d648)
        ;

        
    
    
            var marker_a75d9380c1af453e8ad536bdb9292644 = L.marker(
                [37.5408787006, 127.2034245202],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_282cfce0e682919283ef9ca32791e161 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_a75d9380c1af453e8ad536bdb9292644.setIcon(icon_282cfce0e682919283ef9ca32791e161);
        
    
        var popup_2ddcc3d371ea3b6479b5ddd52baa872f = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a176a58455fd16ce36beb6bc94f150ee = $(`<div id="html_a176a58455fd16ce36beb6bc94f150ee" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 하남시 덕풍동 401-11번지<br>사고발생일자: 2020-08-13 오전 00:00<br>클러스터: 32</div>`)[0];
                popup_2ddcc3d371ea3b6479b5ddd52baa872f.setContent(html_a176a58455fd16ce36beb6bc94f150ee);
            
        

        marker_a75d9380c1af453e8ad536bdb9292644.bindPopup(popup_2ddcc3d371ea3b6479b5ddd52baa872f)
        ;

        
    
    
            var marker_18ce0184c5f7862e3ba41c19176c8297 = L.marker(
                [37.3532667576, 126.6195405769],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_a47378481fb3a21e6f33d9a98f1c59f5 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_18ce0184c5f7862e3ba41c19176c8297.setIcon(icon_a47378481fb3a21e6f33d9a98f1c59f5);
        
    
        var popup_85d2994634764427b670ba970b027576 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1a1ea030bcd4fd550d543b3ba05db96a = $(`<div id="html_1a1ea030bcd4fd550d543b3ba05db96a" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 연수구 송도동 신항대로 892번길 50<br>사고발생일자: 2020-08-09 오전 00:00<br>클러스터: 33</div>`)[0];
                popup_85d2994634764427b670ba970b027576.setContent(html_1a1ea030bcd4fd550d543b3ba05db96a);
            
        

        marker_18ce0184c5f7862e3ba41c19176c8297.bindPopup(popup_85d2994634764427b670ba970b027576)
        ;

        
    
    
            var marker_cb13e5c4a64f313413439d3eec69b403 = L.marker(
                [37.3533037421, 126.6195394998],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_77d9f3a8865fcb5296c0300936286efa = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_cb13e5c4a64f313413439d3eec69b403.setIcon(icon_77d9f3a8865fcb5296c0300936286efa);
        
    
        var popup_2574b76b20910b2f78abd8406bcd0273 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_7c14e6ce7bd7f537f95008f7d69398f7 = $(`<div id="html_7c14e6ce7bd7f537f95008f7d69398f7" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 연수구 송도동 신항대로 892번길 50<br>사고발생일자: 2020-08-11 오전 00:00<br>클러스터: 33</div>`)[0];
                popup_2574b76b20910b2f78abd8406bcd0273.setContent(html_7c14e6ce7bd7f537f95008f7d69398f7);
            
        

        marker_cb13e5c4a64f313413439d3eec69b403.bindPopup(popup_2574b76b20910b2f78abd8406bcd0273)
        ;

        
    
    
            var marker_2dcbe982cb785aec66530d02a08e4bf5 = L.marker(
                [35.2205000587, 126.8246532854],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_b9d187d179b1b55d5b35337fb8c59f75 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_2dcbe982cb785aec66530d02a08e4bf5.setIcon(icon_b9d187d179b1b55d5b35337fb8c59f75);
        
    
        var popup_3e5229a86a1f06ccef047d030549a314 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_090372489d4d74fbfb703048d4358c9a = $(`<div id="html_090372489d4d74fbfb703048d4358c9a" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 광산구 비아동 707-8<br>사고발생일자: 2020-08-11 오전 00:00<br>클러스터: 34</div>`)[0];
                popup_3e5229a86a1f06ccef047d030549a314.setContent(html_090372489d4d74fbfb703048d4358c9a);
            
        

        marker_2dcbe982cb785aec66530d02a08e4bf5.bindPopup(popup_3e5229a86a1f06ccef047d030549a314)
        ;

        
    
    
            var marker_8e291c712e12696b9b85f7cbe7672a1b = L.marker(
                [35.2208788127, 126.8247391847],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_715c1506d67818ab62025a3327ccf7b6 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_8e291c712e12696b9b85f7cbe7672a1b.setIcon(icon_715c1506d67818ab62025a3327ccf7b6);
        
    
        var popup_aff391dde795007d53df872851e0701d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_61ce9b6b84d0db2c630a6fa3d44d09cf = $(`<div id="html_61ce9b6b84d0db2c630a6fa3d44d09cf" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 광산구 비아동 비아동707-14번지 주변<br>사고발생일자: 2020-08-11 오전 00:00<br>클러스터: 34</div>`)[0];
                popup_aff391dde795007d53df872851e0701d.setContent(html_61ce9b6b84d0db2c630a6fa3d44d09cf);
            
        

        marker_8e291c712e12696b9b85f7cbe7672a1b.bindPopup(popup_aff391dde795007d53df872851e0701d)
        ;

        
    
    
            var marker_3f24253c00db0c6a21b499d9b37c0781 = L.marker(
                [35.1468494184, 126.8698836921],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_0ac8566ea3f281d0a72ec0c843a84cf0 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_3f24253c00db0c6a21b499d9b37c0781.setIcon(icon_0ac8566ea3f281d0a72ec0c843a84cf0);
        
    
        var popup_10070e8641b22b595f2370d017f4af87 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_7ca0d76b2ed8c52edd08e9fd1f0c91f4 = $(`<div id="html_7ca0d76b2ed8c52edd08e9fd1f0c91f4" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 서구 쌍촌동 1229<br>사고발생일자: 2020-08-10 오전 00:00<br>클러스터: 35</div>`)[0];
                popup_10070e8641b22b595f2370d017f4af87.setContent(html_7ca0d76b2ed8c52edd08e9fd1f0c91f4);
            
        

        marker_3f24253c00db0c6a21b499d9b37c0781.bindPopup(popup_10070e8641b22b595f2370d017f4af87)
        ;

        
    
    
            var marker_99bebf20234f26b542896ccfc6e7f35a = L.marker(
                [35.1465974208, 126.8699687716],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_673bf4d4f0571e3df6409a94beaaff5b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_99bebf20234f26b542896ccfc6e7f35a.setIcon(icon_673bf4d4f0571e3df6409a94beaaff5b);
        
    
        var popup_b7837ab49880a50d1b517cc89cca0d44 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_25dde07c61a130a07acec577dce70cff = $(`<div id="html_25dde07c61a130a07acec577dce70cff" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 서구 쌍촌동 1229번지 인근<br>사고발생일자: 2020-08-10 오전 00:00<br>클러스터: 35</div>`)[0];
                popup_b7837ab49880a50d1b517cc89cca0d44.setContent(html_25dde07c61a130a07acec577dce70cff);
            
        

        marker_99bebf20234f26b542896ccfc6e7f35a.bindPopup(popup_b7837ab49880a50d1b517cc89cca0d44)
        ;

        
    
    
            var marker_47b98763df1c9b21725294ca95c4c921 = L.marker(
                [37.2328629188, 127.286407536],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_58f317a75308b927129b67e3d05c198b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_47b98763df1c9b21725294ca95c4c921.setIcon(icon_58f317a75308b927129b67e3d05c198b);
        
    
        var popup_a8949475587bafa6904d1db003d40c22 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_fe8e92993e084431e5a74bf8427b5ecd = $(`<div id="html_fe8e92993e084431e5a74bf8427b5ecd" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도  양지면 814<br>사고발생일자: 2020-08-09 오전 00:00<br>클러스터: 36</div>`)[0];
                popup_a8949475587bafa6904d1db003d40c22.setContent(html_fe8e92993e084431e5a74bf8427b5ecd);
            
        

        marker_47b98763df1c9b21725294ca95c4c921.bindPopup(popup_a8949475587bafa6904d1db003d40c22)
        ;

        
    
    
            var marker_5bb9ce25554ec60f75fbfd0301a9bca9 = L.marker(
                [37.2329689673, 127.2860471183],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1d346fb94b4c37350ebf6e51184a9b12 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_5bb9ce25554ec60f75fbfd0301a9bca9.setIcon(icon_1d346fb94b4c37350ebf6e51184a9b12);
        
    
        var popup_0db3cab33bd5d7e7282314a0be71461b = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_42a796e31f1d8ca11d7b5c79f0f88030 = $(`<div id="html_42a796e31f1d8ca11d7b5c79f0f88030" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 용인시 처인구 양지면 남곡리 130-2<br>사고발생일자: 2020-08-03 오전 00:00<br>클러스터: 36</div>`)[0];
                popup_0db3cab33bd5d7e7282314a0be71461b.setContent(html_42a796e31f1d8ca11d7b5c79f0f88030);
            
        

        marker_5bb9ce25554ec60f75fbfd0301a9bca9.bindPopup(popup_0db3cab33bd5d7e7282314a0be71461b)
        ;

        
    
    
            var marker_f1d3c0a79b674fed03b7bb28f8f3a80d = L.marker(
                [35.140063, 126.92252],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_d328c39f75126c22939728ac3a85754d = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f1d3c0a79b674fed03b7bb28f8f3a80d.setIcon(icon_d328c39f75126c22939728ac3a85754d);
        
    
        var popup_9dd8f85bb9992932eeb5b914c3d2ef41 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ce4078cb458d4f433e922a5a782bf494 = $(`<div id="html_ce4078cb458d4f433e922a5a782bf494" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 학동 12-1번지<br>사고발생일자: 2019-05-30 오전 00:00<br>클러스터: 37</div>`)[0];
                popup_9dd8f85bb9992932eeb5b914c3d2ef41.setContent(html_ce4078cb458d4f433e922a5a782bf494);
            
        

        marker_f1d3c0a79b674fed03b7bb28f8f3a80d.bindPopup(popup_9dd8f85bb9992932eeb5b914c3d2ef41)
        ;

        
    
    
            var marker_3d959f8f75032483d50d7e32102dbee1 = L.marker(
                [35.1402664474, 126.9221227751],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_647e018735f699a0e285b884d5820df0 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_3d959f8f75032483d50d7e32102dbee1.setIcon(icon_647e018735f699a0e285b884d5820df0);
        
    
        var popup_64e6745a3bb05d81210eb8a4a1f7627b = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a3a71ded13606f752295af86f4be791f = $(`<div id="html_a3a71ded13606f752295af86f4be791f" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 학동 994<br>사고발생일자: 2020-08-08 오전 00:00<br>클러스터: 37</div>`)[0];
                popup_64e6745a3bb05d81210eb8a4a1f7627b.setContent(html_a3a71ded13606f752295af86f4be791f);
            
        

        marker_3d959f8f75032483d50d7e32102dbee1.bindPopup(popup_64e6745a3bb05d81210eb8a4a1f7627b)
        ;

        
    
    
            var marker_c9313d389a8bb1f6829820df81768a29 = L.marker(
                [35.1403037346, 126.9220691309],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_c23dd92a2f656e6cec32a636bdee9079 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_c9313d389a8bb1f6829820df81768a29.setIcon(icon_c23dd92a2f656e6cec32a636bdee9079);
        
    
        var popup_b8ec6c7c3bad47721174198461f7740b = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_6e6c05d8c751d380b152391c70797f72 = $(`<div id="html_6e6c05d8c751d380b152391c70797f72" style="width: 100.0%; height: 100.0%;">사고발생 위치: 광주광역시 동구 제봉로 15<br>사고발생일자: 2020-08-08 오전 00:00<br>클러스터: 37</div>`)[0];
                popup_b8ec6c7c3bad47721174198461f7740b.setContent(html_6e6c05d8c751d380b152391c70797f72);
            
        

        marker_c9313d389a8bb1f6829820df81768a29.bindPopup(popup_b8ec6c7c3bad47721174198461f7740b)
        ;

        
    
    
            var marker_80afb5a30a76f8fa2eda426c907b0af6 = L.marker(
                [36.9912111206, 127.586867378],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1948de6131949234729e940d907c8d32 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_80afb5a30a76f8fa2eda426c907b0af6.setIcon(icon_1948de6131949234729e940d907c8d32);
        
    
        var popup_323d9d0f8b3723e2952fc5bdbfcf90af = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a29581ea6abc3792e0c3600ee0872a73 = $(`<div id="html_a29581ea6abc3792e0c3600ee0872a73" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 음성군 금왕읍 무극리 523-3<br>사고발생일자: 2020-08-06 오전 00:00<br>클러스터: 38</div>`)[0];
                popup_323d9d0f8b3723e2952fc5bdbfcf90af.setContent(html_a29581ea6abc3792e0c3600ee0872a73);
            
        

        marker_80afb5a30a76f8fa2eda426c907b0af6.bindPopup(popup_323d9d0f8b3723e2952fc5bdbfcf90af)
        ;

        
    
    
            var marker_b0d23aeda77d987eee9d8baaf3bd3f75 = L.marker(
                [36.9914483218, 127.5869488367],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_342acf4033474a3837e2ae1e6c747b41 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_b0d23aeda77d987eee9d8baaf3bd3f75.setIcon(icon_342acf4033474a3837e2ae1e6c747b41);
        
    
        var popup_5f953d867e232960e5401812926832d1 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_9d6a2131c9aa5f3dc3947a5e9420ac4b = $(`<div id="html_9d6a2131c9aa5f3dc3947a5e9420ac4b" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 음성군 금왕읍 무극로 221<br>사고발생일자: 2020-07-30 오전 00:00<br>클러스터: 38</div>`)[0];
                popup_5f953d867e232960e5401812926832d1.setContent(html_9d6a2131c9aa5f3dc3947a5e9420ac4b);
            
        

        marker_b0d23aeda77d987eee9d8baaf3bd3f75.bindPopup(popup_5f953d867e232960e5401812926832d1)
        ;

        
    
    
            var marker_23e7bff9ccd89c7978d63cb41bf77c74 = L.marker(
                [37.54055956672804, 126.7226445452843],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_9ef59420ca3ee8ac2bf9ca03a61c3031 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_23e7bff9ccd89c7978d63cb41bf77c74.setIcon(icon_9ef59420ca3ee8ac2bf9ca03a61c3031);
        
    
        var popup_7532096b3fb62846e7c4f0a1f5465459 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_7b73401cc4759282857f8f7f0fb5b08f = $(`<div id="html_7b73401cc4759282857f8f7f0fb5b08f" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 계양구 계산동 1034(계양대로 161-2)<br>사고발생일자: 2020-02-18 오전 00:00<br>클러스터: 39</div>`)[0];
                popup_7532096b3fb62846e7c4f0a1f5465459.setContent(html_7b73401cc4759282857f8f7f0fb5b08f);
            
        

        marker_23e7bff9ccd89c7978d63cb41bf77c74.bindPopup(popup_7532096b3fb62846e7c4f0a1f5465459)
        ;

        
    
    
            var marker_54406e66abc86d213eeb03e194570681 = L.marker(
                [37.54055956672804, 126.7226445452843],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_03b5bded60200481ec0d70ed5f87b9f8 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_54406e66abc86d213eeb03e194570681.setIcon(icon_03b5bded60200481ec0d70ed5f87b9f8);
        
    
        var popup_5eda8f8f1b24f6a2d45d868fc6388b7f = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_7ec07479edbbdce5212c12a0393e1437 = $(`<div id="html_7ec07479edbbdce5212c12a0393e1437" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 계양구 계산동 1034(계양대로 161-2)<br>사고발생일자: 2020-06-27 오전 00:00<br>클러스터: 39</div>`)[0];
                popup_5eda8f8f1b24f6a2d45d868fc6388b7f.setContent(html_7ec07479edbbdce5212c12a0393e1437);
            
        

        marker_54406e66abc86d213eeb03e194570681.bindPopup(popup_5eda8f8f1b24f6a2d45d868fc6388b7f)
        ;

        
    
    
            var marker_076dcc4403fb8f132aa98c04876a275f = L.marker(
                [36.6360473, 127.4405923],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_0b456c1fd4207697055ea62f5bf6c522 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_076dcc4403fb8f132aa98c04876a275f.setIcon(icon_0b456c1fd4207697055ea62f5bf6c522);
        
    
        var popup_c299a48680d2e001bde5f920a7360ea7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_76e2d67e2909f031b92a53e62d4165bd = $(`<div id="html_76e2d67e2909f031b92a53e62d4165bd" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 흥덕구 복대동 31-6<br>사고발생일자: 2018-02-07 오전 00:00<br>클러스터: 40</div>`)[0];
                popup_c299a48680d2e001bde5f920a7360ea7.setContent(html_76e2d67e2909f031b92a53e62d4165bd);
            
        

        marker_076dcc4403fb8f132aa98c04876a275f.bindPopup(popup_c299a48680d2e001bde5f920a7360ea7)
        ;

        
    
    
            var marker_be41c6c2362b80c7fcc6ee2a68bcbaad = L.marker(
                [36.6360473, 127.4405923],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_5c4001c701cfe165050eaefddd99c0c8 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_be41c6c2362b80c7fcc6ee2a68bcbaad.setIcon(icon_5c4001c701cfe165050eaefddd99c0c8);
        
    
        var popup_8a7bdac0e19f5de2b4b5090088656d69 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_3722034d296811e2ee35406d2f158143 = $(`<div id="html_3722034d296811e2ee35406d2f158143" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 흥덕구 복대동 2200<br>사고발생일자: 2018-02-19 오전 00:00<br>클러스터: 40</div>`)[0];
                popup_8a7bdac0e19f5de2b4b5090088656d69.setContent(html_3722034d296811e2ee35406d2f158143);
            
        

        marker_be41c6c2362b80c7fcc6ee2a68bcbaad.bindPopup(popup_8a7bdac0e19f5de2b4b5090088656d69)
        ;

        
    
    
            var marker_0df19b871e793de2a3948d5d3eff9587 = L.marker(
                [36.6360473, 127.4405923],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_8e6c5eadcaa8249dfc78003d99de231b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0df19b871e793de2a3948d5d3eff9587.setIcon(icon_8e6c5eadcaa8249dfc78003d99de231b);
        
    
        var popup_63c9dd5a43ebf549d2da955bf3943e36 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b24b66940ca359a82c18937452aceb91 = $(`<div id="html_b24b66940ca359a82c18937452aceb91" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 흥덕구 복대동 204-11<br>사고발생일자: 2018-05-25 오전 00:00<br>클러스터: 40</div>`)[0];
                popup_63c9dd5a43ebf549d2da955bf3943e36.setContent(html_b24b66940ca359a82c18937452aceb91);
            
        

        marker_0df19b871e793de2a3948d5d3eff9587.bindPopup(popup_63c9dd5a43ebf549d2da955bf3943e36)
        ;

        
    
    
            var marker_de655209dcea603ed07d95653212200a = L.marker(
                [36.6360473, 127.4405923],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_d37a568b7d1164fa75c7b29722c1dc73 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_de655209dcea603ed07d95653212200a.setIcon(icon_d37a568b7d1164fa75c7b29722c1dc73);
        
    
        var popup_04f72e2b1abd122a9c8aea6536c86906 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_c5b0507caddede6b74bf270e727a7489 = $(`<div id="html_c5b0507caddede6b74bf270e727a7489" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 흥덕구 복대동 220<br>사고발생일자: 2020-06-01 오전 00:00<br>클러스터: 40</div>`)[0];
                popup_04f72e2b1abd122a9c8aea6536c86906.setContent(html_c5b0507caddede6b74bf270e727a7489);
            
        

        marker_de655209dcea603ed07d95653212200a.bindPopup(popup_04f72e2b1abd122a9c8aea6536c86906)
        ;

        
    
    
            var marker_c254d7f3bb666810cdba382629c90596 = L.marker(
                [37.4813456, 126.8104404],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_5265d10d0090ed515d9f7aa4194d3c6b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_c254d7f3bb666810cdba382629c90596.setIcon(icon_5265d10d0090ed515d9f7aa4194d3c6b);
        
    
        var popup_c59b7ded1589c6ff376c2a6192ad35b1 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_d6d8f59c37eddf0c751d51a827efee39 = $(`<div id="html_d6d8f59c37eddf0c751d51a827efee39" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 괴안동 167<br>사고발생일자: 2020-04-14 오전 00:00<br>클러스터: 41</div>`)[0];
                popup_c59b7ded1589c6ff376c2a6192ad35b1.setContent(html_d6d8f59c37eddf0c751d51a827efee39);
            
        

        marker_c254d7f3bb666810cdba382629c90596.bindPopup(popup_c59b7ded1589c6ff376c2a6192ad35b1)
        ;

        
    
    
            var marker_f4440ae64984079783e479fd7b2df4bb = L.marker(
                [37.4813456, 126.8104404],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_5a50f672b48bc537c16d29eefd191747 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f4440ae64984079783e479fd7b2df4bb.setIcon(icon_5a50f672b48bc537c16d29eefd191747);
        
    
        var popup_5597f8f40a5a2512928929696e99b7c3 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_e02754650b9f1a75590042c3c4fa309d = $(`<div id="html_e02754650b9f1a75590042c3c4fa309d" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 괴안동  108<br>사고발생일자: 2019-06-05 오전 00:00<br>클러스터: 41</div>`)[0];
                popup_5597f8f40a5a2512928929696e99b7c3.setContent(html_e02754650b9f1a75590042c3c4fa309d);
            
        

        marker_f4440ae64984079783e479fd7b2df4bb.bindPopup(popup_5597f8f40a5a2512928929696e99b7c3)
        ;

        
    
    
            var marker_fc619ae4a2e9b1e5b5e3ef4648fd78ab = L.marker(
                [36.6485352, 127.4754254],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_0d11632cd1af414dc3d7d6e06f23a730 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_fc619ae4a2e9b1e5b5e3ef4648fd78ab.setIcon(icon_0d11632cd1af414dc3d7d6e06f23a730);
        
    
        var popup_90127d529594a8b35d7dc71890391f15 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_92cf2d5282ab8f33f79afc480ea9fba8 = $(`<div id="html_92cf2d5282ab8f33f79afc480ea9fba8" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 흥덕구 운천동 1493<br>사고발생일자: 2020-03-11 오전 00:00<br>클러스터: 42</div>`)[0];
                popup_90127d529594a8b35d7dc71890391f15.setContent(html_92cf2d5282ab8f33f79afc480ea9fba8);
            
        

        marker_fc619ae4a2e9b1e5b5e3ef4648fd78ab.bindPopup(popup_90127d529594a8b35d7dc71890391f15)
        ;

        
    
    
            var marker_494a8e3ce86edbf72ed6a4f5d89ee370 = L.marker(
                [36.6485352, 127.4754254],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_3adfea5a5650112abae72a7a0166513a = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_494a8e3ce86edbf72ed6a4f5d89ee370.setIcon(icon_3adfea5a5650112abae72a7a0166513a);
        
    
        var popup_1f82ab59e49876bd8c8494746cce14ca = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_9303cd6c01e21aaa0f7ac10a748b02f0 = $(`<div id="html_9303cd6c01e21aaa0f7ac10a748b02f0" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 흥덕구 운천동 660<br>사고발생일자: 2018-01-16 오전 00:00<br>클러스터: 42</div>`)[0];
                popup_1f82ab59e49876bd8c8494746cce14ca.setContent(html_9303cd6c01e21aaa0f7ac10a748b02f0);
            
        

        marker_494a8e3ce86edbf72ed6a4f5d89ee370.bindPopup(popup_1f82ab59e49876bd8c8494746cce14ca)
        ;

        
    
    
            var marker_8a25695e97e96a3bb263257d58ce473c = L.marker(
                [37.4991027, 126.7676559],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_954f98965d0efc24e4603831b520e3ee = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_8a25695e97e96a3bb263257d58ce473c.setIcon(icon_954f98965d0efc24e4603831b520e3ee);
        
    
        var popup_3d5a6ad0f287a91e4386bbe3618254f8 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_89f9d2eb869ab1d22c187e58c07ea88c = $(`<div id="html_89f9d2eb869ab1d22c187e58c07ea88c" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 중동  1142-4<br>사고발생일자: 2019-06-14 오전 00:00<br>클러스터: 43</div>`)[0];
                popup_3d5a6ad0f287a91e4386bbe3618254f8.setContent(html_89f9d2eb869ab1d22c187e58c07ea88c);
            
        

        marker_8a25695e97e96a3bb263257d58ce473c.bindPopup(popup_3d5a6ad0f287a91e4386bbe3618254f8)
        ;

        
    
    
            var marker_a90726aeb219dc628d1ca61756ec8ded = L.marker(
                [37.4991027, 126.7676559],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_c7d7f6decce2c75b409dfc4c158704ea = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_a90726aeb219dc628d1ca61756ec8ded.setIcon(icon_c7d7f6decce2c75b409dfc4c158704ea);
        
    
        var popup_835ca56f916efa13e90373237ed7a03d = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ed8f45e4dfb181e19e1980e8d7795f74 = $(`<div id="html_ed8f45e4dfb181e19e1980e8d7795f74" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 중동 1151<br>사고발생일자: 2019-07-01 오전 00:00<br>클러스터: 43</div>`)[0];
                popup_835ca56f916efa13e90373237ed7a03d.setContent(html_ed8f45e4dfb181e19e1980e8d7795f74);
            
        

        marker_a90726aeb219dc628d1ca61756ec8ded.bindPopup(popup_835ca56f916efa13e90373237ed7a03d)
        ;

        
    
    
            var marker_ab4fe5581e64019aeaa2ed0db1b2ce22 = L.marker(
                [37.4991027, 126.7676559],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_ea126c360e20b9ade2c41cc23f12d506 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ab4fe5581e64019aeaa2ed0db1b2ce22.setIcon(icon_ea126c360e20b9ade2c41cc23f12d506);
        
    
        var popup_8331a885153c88eb2186d81de9291360 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_85b802fff3a1c23ece6fdb0625870136 = $(`<div id="html_85b802fff3a1c23ece6fdb0625870136" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 중동 1058-4<br>사고발생일자: 2019-08-13 오전 00:00<br>클러스터: 43</div>`)[0];
                popup_8331a885153c88eb2186d81de9291360.setContent(html_85b802fff3a1c23ece6fdb0625870136);
            
        

        marker_ab4fe5581e64019aeaa2ed0db1b2ce22.bindPopup(popup_8331a885153c88eb2186d81de9291360)
        ;

        
    
    
            var marker_f35b85aba655341b81e9292f38d63718 = L.marker(
                [37.4991027, 126.7676559],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_634a0ca8cb6dabd702ec21920b5cb763 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f35b85aba655341b81e9292f38d63718.setIcon(icon_634a0ca8cb6dabd702ec21920b5cb763);
        
    
        var popup_7ed75f3d6e2762355aa9ac43a5b19230 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_031fbd954556f596e5913558d6b31524 = $(`<div id="html_031fbd954556f596e5913558d6b31524" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 중동 1150<br>사고발생일자: 2019-12-26 오전 00:00<br>클러스터: 43</div>`)[0];
                popup_7ed75f3d6e2762355aa9ac43a5b19230.setContent(html_031fbd954556f596e5913558d6b31524);
            
        

        marker_f35b85aba655341b81e9292f38d63718.bindPopup(popup_7ed75f3d6e2762355aa9ac43a5b19230)
        ;

        
    
    
            var marker_7003d4b3d67a218b868b9314c786c28e = L.marker(
                [37.8598747, 127.077004],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1573977122bdd74c08239577646c599a = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_7003d4b3d67a218b868b9314c786c28e.setIcon(icon_1573977122bdd74c08239577646c599a);
        
    
        var popup_b8ac3afee7dd0ab37d24995a2ea386cc = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_6776a23f057621891cf7aab9862682f1 = $(`<div id="html_6776a23f057621891cf7aab9862682f1" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 양주시 봉양동 340<br>사고발생일자: 2019-10-17 오전 00:00<br>클러스터: 44</div>`)[0];
                popup_b8ac3afee7dd0ab37d24995a2ea386cc.setContent(html_6776a23f057621891cf7aab9862682f1);
            
        

        marker_7003d4b3d67a218b868b9314c786c28e.bindPopup(popup_b8ac3afee7dd0ab37d24995a2ea386cc)
        ;

        
    
    
            var marker_b01aabb1681ef96632d89e7138c8d7ff = L.marker(
                [37.8598747, 127.077004],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_302f3998da228b03c6d1fa2f3a969b64 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_b01aabb1681ef96632d89e7138c8d7ff.setIcon(icon_302f3998da228b03c6d1fa2f3a969b64);
        
    
        var popup_9a961755d208f6fe74841d126388176a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_d402615bd8c70287d07769a1a07651fe = $(`<div id="html_d402615bd8c70287d07769a1a07651fe" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 양주시 봉양동 311-4<br>사고발생일자: 2019-10-17 오전 00:00<br>클러스터: 44</div>`)[0];
                popup_9a961755d208f6fe74841d126388176a.setContent(html_d402615bd8c70287d07769a1a07651fe);
            
        

        marker_b01aabb1681ef96632d89e7138c8d7ff.bindPopup(popup_9a961755d208f6fe74841d126388176a)
        ;

        
    
    
            var marker_c5aadae9c1f51b17ba23399ffb88b5d3 = L.marker(
                [37.3961195, 126.9877019],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_daa106db90d185ec51459ed2ca548185 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_c5aadae9c1f51b17ba23399ffb88b5d3.setIcon(icon_daa106db90d185ec51459ed2ca548185);
        
    
        var popup_95b2207a9b7e1931b43a1c4a694f3f7e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_5a736e23113e9666976c73786f2756e6 = $(`<div id="html_5a736e23113e9666976c73786f2756e6" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 의왕시 포일동 680<br>사고발생일자: 2019-07-15 오전 00:00<br>클러스터: 45</div>`)[0];
                popup_95b2207a9b7e1931b43a1c4a694f3f7e.setContent(html_5a736e23113e9666976c73786f2756e6);
            
        

        marker_c5aadae9c1f51b17ba23399ffb88b5d3.bindPopup(popup_95b2207a9b7e1931b43a1c4a694f3f7e)
        ;

        
    
    
            var marker_a8c2e9c90d6e901c6a597a76658a9595 = L.marker(
                [37.3961195, 126.9877019],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_c0e59354891689a5b0e233697eb0ce5c = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_a8c2e9c90d6e901c6a597a76658a9595.setIcon(icon_c0e59354891689a5b0e233697eb0ce5c);
        
    
        var popup_418134a411805c71b1b033e77a548fb5 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1018d4b070ea5eb5c45202955568944b = $(`<div id="html_1018d4b070ea5eb5c45202955568944b" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 의왕시 포일동  505-107<br>사고발생일자: 2019-06-23 오전 00:00<br>클러스터: 45</div>`)[0];
                popup_418134a411805c71b1b033e77a548fb5.setContent(html_1018d4b070ea5eb5c45202955568944b);
            
        

        marker_a8c2e9c90d6e901c6a597a76658a9595.bindPopup(popup_418134a411805c71b1b033e77a548fb5)
        ;

        
    
    
            var marker_f289c944a3977735135b9c59d3c74a0e = L.marker(
                [37.3961195, 126.9877019],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_7e8d9aef4d25f4ff0f8803e889520b31 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f289c944a3977735135b9c59d3c74a0e.setIcon(icon_7e8d9aef4d25f4ff0f8803e889520b31);
        
    
        var popup_c9aa88410603e5f258af87f2d965844e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_9bd65ace0f38eca141127155d9d9ab94 = $(`<div id="html_9bd65ace0f38eca141127155d9d9ab94" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 의왕시 포일동 505-79<br>사고발생일자: 2019-07-01 오전 00:00<br>클러스터: 45</div>`)[0];
                popup_c9aa88410603e5f258af87f2d965844e.setContent(html_9bd65ace0f38eca141127155d9d9ab94);
            
        

        marker_f289c944a3977735135b9c59d3c74a0e.bindPopup(popup_c9aa88410603e5f258af87f2d965844e)
        ;

        
    
    
            var marker_813a707ddf809339a8454a213c8c6e38 = L.marker(
                [37.3961195, 126.9877019],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1fce9a8abb3e310b37d619674b86dae4 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_813a707ddf809339a8454a213c8c6e38.setIcon(icon_1fce9a8abb3e310b37d619674b86dae4);
        
    
        var popup_62eecb604651c6d5d80f851012f2e1ac = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_4505ee8922c2bb8620fa59757e3a4f4b = $(`<div id="html_4505ee8922c2bb8620fa59757e3a4f4b" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 의왕시 포일동 485-5<br>사고발생일자: 2019-10-01 오전 00:00<br>클러스터: 45</div>`)[0];
                popup_62eecb604651c6d5d80f851012f2e1ac.setContent(html_4505ee8922c2bb8620fa59757e3a4f4b);
            
        

        marker_813a707ddf809339a8454a213c8c6e38.bindPopup(popup_62eecb604651c6d5d80f851012f2e1ac)
        ;

        
    
    
            var marker_759717240df5d7384fccf96a0f038f9f = L.marker(
                [37.6712292, 126.7618004],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_969bd76cd16f1a31fbe093131f8edb9e = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_759717240df5d7384fccf96a0f038f9f.setIcon(icon_969bd76cd16f1a31fbe093131f8edb9e);
        
    
        var popup_a06c1109c88a34220bc45b7f7ff0f799 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f69e038fae6ce992f52856fe1f6cef78 = $(`<div id="html_f69e038fae6ce992f52856fe1f6cef78" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산서구 주엽동  151<br>사고발생일자: 2018-09-03 오전 00:00<br>클러스터: 46</div>`)[0];
                popup_a06c1109c88a34220bc45b7f7ff0f799.setContent(html_f69e038fae6ce992f52856fe1f6cef78);
            
        

        marker_759717240df5d7384fccf96a0f038f9f.bindPopup(popup_a06c1109c88a34220bc45b7f7ff0f799)
        ;

        
    
    
            var marker_7e5acc7b866d74b2acc8b079dd1eced4 = L.marker(
                [37.6712292, 126.7618004],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_28028e29e0dc3ec69a9b97af044ff5ac = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_7e5acc7b866d74b2acc8b079dd1eced4.setIcon(icon_28028e29e0dc3ec69a9b97af044ff5ac);
        
    
        var popup_9c1b8925dcf5c8a3554a0b2b0484d26a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_49cc4256fc33411954defba989a7954e = $(`<div id="html_49cc4256fc33411954defba989a7954e" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 고양시 일산서구 주엽동  14<br>사고발생일자: 2019-05-14 오전 00:00<br>클러스터: 46</div>`)[0];
                popup_9c1b8925dcf5c8a3554a0b2b0484d26a.setContent(html_49cc4256fc33411954defba989a7954e);
            
        

        marker_7e5acc7b866d74b2acc8b079dd1eced4.bindPopup(popup_9c1b8925dcf5c8a3554a0b2b0484d26a)
        ;

        
    
    
            var marker_256a5f847d9b6f0f170b58133e2be350 = L.marker(
                [37.507173, 126.72047],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_16fceb751b21229143b77bd099bdd732 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_256a5f847d9b6f0f170b58133e2be350.setIcon(icon_16fceb751b21229143b77bd099bdd732);
        
    
        var popup_ae92c6a8dc6384996f77ebab78a084b2 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_92f4c525a700c56e1c33f9035ee6933c = $(`<div id="html_92f4c525a700c56e1c33f9035ee6933c" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 부평구 청천동  112 번지 쌍용아파트 삼거리<br>사고발생일자: 2019-02-08 오전 00:00<br>클러스터: 47</div>`)[0];
                popup_ae92c6a8dc6384996f77ebab78a084b2.setContent(html_92f4c525a700c56e1c33f9035ee6933c);
            
        

        marker_256a5f847d9b6f0f170b58133e2be350.bindPopup(popup_ae92c6a8dc6384996f77ebab78a084b2)
        ;

        
    
    
            var marker_b673fb9824b85c78f8e3883353f76e26 = L.marker(
                [37.507173, 126.72047],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_beac97e4f6334dabcfbe02551fe21557 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_b673fb9824b85c78f8e3883353f76e26.setIcon(icon_beac97e4f6334dabcfbe02551fe21557);
        
    
        var popup_e15f6f09e1f240dd560db13656bdfc3b = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_888cbffc131d376f278f67368f0eb833 = $(`<div id="html_888cbffc131d376f278f67368f0eb833" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 부평구 청천동  112 번지 쌍용아파트 삼거리<br>사고발생일자: 2019-02-06 오전 00:00<br>클러스터: 47</div>`)[0];
                popup_e15f6f09e1f240dd560db13656bdfc3b.setContent(html_888cbffc131d376f278f67368f0eb833);
            
        

        marker_b673fb9824b85c78f8e3883353f76e26.bindPopup(popup_e15f6f09e1f240dd560db13656bdfc3b)
        ;

        
    
    
            var marker_2e41755a0d8a9dfe34d31f102f5edff3 = L.marker(
                [37.507173, 126.72047],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_a1e293b45d0c8e9ec674b79f28a81aca = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_2e41755a0d8a9dfe34d31f102f5edff3.setIcon(icon_a1e293b45d0c8e9ec674b79f28a81aca);
        
    
        var popup_2223d9cbc5e4e44e85e7482173459a7f = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_8f0c0f9954dfef50d5e65f1e4b683bea = $(`<div id="html_8f0c0f9954dfef50d5e65f1e4b683bea" style="width: 100.0%; height: 100.0%;">사고발생 위치: 인천광역시 부평구 청천동  112 번지 쌍용아파트 삼거리<br>사고발생일자: 2019-01-18 오전 00:00<br>클러스터: 47</div>`)[0];
                popup_2223d9cbc5e4e44e85e7482173459a7f.setContent(html_8f0c0f9954dfef50d5e65f1e4b683bea);
            
        

        marker_2e41755a0d8a9dfe34d31f102f5edff3.bindPopup(popup_2223d9cbc5e4e44e85e7482173459a7f)
        ;

        
    
    
            var marker_81502aebd1a10fe18d580b121abaee7e = L.marker(
                [37.4884377, 126.779519],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_be3f6f8f9fb12394ea20305a5f958e32 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_81502aebd1a10fe18d580b121abaee7e.setIcon(icon_be3f6f8f9fb12394ea20305a5f958e32);
        
    
        var popup_0738af41b2bf67cd3e4d5b1d8f0ade24 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_2a51b2415d5d56b8cca7128869786b76 = $(`<div id="html_2a51b2415d5d56b8cca7128869786b76" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 심곡동 426-4<br>사고발생일자: 2018-09-12 오전 00:00<br>클러스터: 48</div>`)[0];
                popup_0738af41b2bf67cd3e4d5b1d8f0ade24.setContent(html_2a51b2415d5d56b8cca7128869786b76);
            
        

        marker_81502aebd1a10fe18d580b121abaee7e.bindPopup(popup_0738af41b2bf67cd3e4d5b1d8f0ade24)
        ;

        
    
    
            var marker_839abd9d760ff1cb5e1bf297e9dc8ffd = L.marker(
                [37.4884377, 126.779519],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_e7401d432bc427f0d7cda397a612a804 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_839abd9d760ff1cb5e1bf297e9dc8ffd.setIcon(icon_e7401d432bc427f0d7cda397a612a804);
        
    
        var popup_c4217be054195497c8f7045fddef2d7a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_064c0d84d48a06e0bbbab64cb6255bba = $(`<div id="html_064c0d84d48a06e0bbbab64cb6255bba" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 심곡동 399-11<br>사고발생일자: 2018-09-12 오전 00:00<br>클러스터: 48</div>`)[0];
                popup_c4217be054195497c8f7045fddef2d7a.setContent(html_064c0d84d48a06e0bbbab64cb6255bba);
            
        

        marker_839abd9d760ff1cb5e1bf297e9dc8ffd.bindPopup(popup_c4217be054195497c8f7045fddef2d7a)
        ;

        
    
    
            var marker_f847d865d2982a48cb93369398f696b3 = L.marker(
                [37.4884377, 126.779519],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_6d070742feaeddd1bae3295358294e26 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f847d865d2982a48cb93369398f696b3.setIcon(icon_6d070742feaeddd1bae3295358294e26);
        
    
        var popup_e48977e52bad53fb8b37adf0f8be3892 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_02a1424f4fc6940d547f43895284b571 = $(`<div id="html_02a1424f4fc6940d547f43895284b571" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 심곡동 349-3<br>사고발생일자: 2018-09-03 오전 00:00<br>클러스터: 48</div>`)[0];
                popup_e48977e52bad53fb8b37adf0f8be3892.setContent(html_02a1424f4fc6940d547f43895284b571);
            
        

        marker_f847d865d2982a48cb93369398f696b3.bindPopup(popup_e48977e52bad53fb8b37adf0f8be3892)
        ;

        
    
    
            var marker_d02cdf7ca742f4f8a35084c37e410da7 = L.marker(
                [37.4884377, 126.779519],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_4c556ecd608b7627f31a1921ba36b735 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_d02cdf7ca742f4f8a35084c37e410da7.setIcon(icon_4c556ecd608b7627f31a1921ba36b735);
        
    
        var popup_70e5c5b0a422deb83fe8a2e69399b4d7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a43ee854d687d84c6f694def11c56d07 = $(`<div id="html_a43ee854d687d84c6f694def11c56d07" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 심곡동 349-6<br>사고발생일자: 2018-08-15 오전 00:00<br>클러스터: 48</div>`)[0];
                popup_70e5c5b0a422deb83fe8a2e69399b4d7.setContent(html_a43ee854d687d84c6f694def11c56d07);
            
        

        marker_d02cdf7ca742f4f8a35084c37e410da7.bindPopup(popup_70e5c5b0a422deb83fe8a2e69399b4d7)
        ;

        
    
    
            var marker_110fd0350b02621f57e9a30587b1c8ec = L.marker(
                [35.18864947977809, 129.0735575380294],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_4101afb4575e16813d4df406925f54fa = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_110fd0350b02621f57e9a30587b1c8ec.setIcon(icon_4101afb4575e16813d4df406925f54fa);
        
    
        var popup_a93b028298c160aa6b3ab54b10370276 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b5b159790c2d15b1b2f4d385874ab65b = $(`<div id="html_b5b159790c2d15b1b2f4d385874ab65b" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 연제구 월드컵대로 21<br>사고발생일자: 2018-08-21 오전 00:00<br>클러스터: 49</div>`)[0];
                popup_a93b028298c160aa6b3ab54b10370276.setContent(html_b5b159790c2d15b1b2f4d385874ab65b);
            
        

        marker_110fd0350b02621f57e9a30587b1c8ec.bindPopup(popup_a93b028298c160aa6b3ab54b10370276)
        ;

        
    
    
            var marker_71c08ae79d00f3c8dfce538b45df3887 = L.marker(
                [35.18864947977809, 129.0735575380294],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_e9c4bb8f41765f8b1b25d11aab2af2ec = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_71c08ae79d00f3c8dfce538b45df3887.setIcon(icon_e9c4bb8f41765f8b1b25d11aab2af2ec);
        
    
        var popup_f4003c8d53a2534da4cf3df087f4d530 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1de1a7422a3ac71c126e68a304150246 = $(`<div id="html_1de1a7422a3ac71c126e68a304150246" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 연제구 월드컵대로 224<br>사고발생일자: 2018-04-21 오전 00:00<br>클러스터: 49</div>`)[0];
                popup_f4003c8d53a2534da4cf3df087f4d530.setContent(html_1de1a7422a3ac71c126e68a304150246);
            
        

        marker_71c08ae79d00f3c8dfce538b45df3887.bindPopup(popup_f4003c8d53a2534da4cf3df087f4d530)
        ;

        
    
    
            var marker_25faae971ad84d75a634ac4b75792df8 = L.marker(
                [35.18864947977809, 129.0735575380294],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_6f0cea8ef3a568514bbaa335e14334a9 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_25faae971ad84d75a634ac4b75792df8.setIcon(icon_6f0cea8ef3a568514bbaa335e14334a9);
        
    
        var popup_a52d346f2f0eb4a055909fdf3b634be7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_cb2bff94049a799f0e10b25bf9314317 = $(`<div id="html_cb2bff94049a799f0e10b25bf9314317" style="width: 100.0%; height: 100.0%;">사고발생 위치: 부산광역시 연제구 월드컵대로 233<br>사고발생일자: 2018-07-20 오전 00:00<br>클러스터: 49</div>`)[0];
                popup_a52d346f2f0eb4a055909fdf3b634be7.setContent(html_cb2bff94049a799f0e10b25bf9314317);
            
        

        marker_25faae971ad84d75a634ac4b75792df8.bindPopup(popup_a52d346f2f0eb4a055909fdf3b634be7)
        ;

        
    
    
            var marker_ed94a4b9ede27fe0d1dbfb32c0b74649 = L.marker(
                [37.486586, 126.795417],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_b84bf94da054d4d2306237d73037313f = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ed94a4b9ede27fe0d1dbfb32c0b74649.setIcon(icon_b84bf94da054d4d2306237d73037313f);
        
    
        var popup_76b1076a279af84ae34f658cdfc64906 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_fc49503d3306a8f2d27a4e5f7890a9ec = $(`<div id="html_fc49503d3306a8f2d27a4e5f7890a9ec" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 소사동  18-38<br>사고발생일자: 2018-06-28 오전 00:00<br>클러스터: 50</div>`)[0];
                popup_76b1076a279af84ae34f658cdfc64906.setContent(html_fc49503d3306a8f2d27a4e5f7890a9ec);
            
        

        marker_ed94a4b9ede27fe0d1dbfb32c0b74649.bindPopup(popup_76b1076a279af84ae34f658cdfc64906)
        ;

        
    
    
            var marker_645de12384e7588d051099ebc142e106 = L.marker(
                [37.486586, 126.795417],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_ef1641c0991d217d4e7be7c433b4d696 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_645de12384e7588d051099ebc142e106.setIcon(icon_ef1641c0991d217d4e7be7c433b4d696);
        
    
        var popup_6aac71825a562268cfaba9f9cc41d746 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_fdf515a214b50132c0c4bf71449df4ed = $(`<div id="html_fdf515a214b50132c0c4bf71449df4ed" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 소사동  17-15<br>사고발생일자: 2018-07-23 오전 00:00<br>클러스터: 50</div>`)[0];
                popup_6aac71825a562268cfaba9f9cc41d746.setContent(html_fdf515a214b50132c0c4bf71449df4ed);
            
        

        marker_645de12384e7588d051099ebc142e106.bindPopup(popup_6aac71825a562268cfaba9f9cc41d746)
        ;

        
    
    
            var marker_13bc0540020d995def090d8f1a1272ab = L.marker(
                [37.3779842, 126.9543224],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_86d35d5ad545ef879e577d0d1761d6a3 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_13bc0540020d995def090d8f1a1272ab.setIcon(icon_86d35d5ad545ef879e577d0d1761d6a3);
        
    
        var popup_cc598880e5b2e9b70b680601aa37b699 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b4385a8ae0f4a29d057a831bc0ae4b42 = $(`<div id="html_b4385a8ae0f4a29d057a831bc0ae4b42" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 안양시 동안구 호계동  1022-5<br>사고발생일자: 2018-06-07 오전 00:00<br>클러스터: 51</div>`)[0];
                popup_cc598880e5b2e9b70b680601aa37b699.setContent(html_b4385a8ae0f4a29d057a831bc0ae4b42);
            
        

        marker_13bc0540020d995def090d8f1a1272ab.bindPopup(popup_cc598880e5b2e9b70b680601aa37b699)
        ;

        
    
    
            var marker_2a85fd5d9e27363e485f7f02bfbbed13 = L.marker(
                [37.3779842, 126.9543224],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1eb4bc9a2859af187da8207c6398c7dc = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_2a85fd5d9e27363e485f7f02bfbbed13.setIcon(icon_1eb4bc9a2859af187da8207c6398c7dc);
        
    
        var popup_e67d068e072c0503cc17c50d9bb64f4e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b3c746cc50205857f7b23ef81ea8eacc = $(`<div id="html_b3c746cc50205857f7b23ef81ea8eacc" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 안양시 동안구 호계동  1014-1<br>사고발생일자: 2018-06-28 오전 00:00<br>클러스터: 51</div>`)[0];
                popup_e67d068e072c0503cc17c50d9bb64f4e.setContent(html_b3c746cc50205857f7b23ef81ea8eacc);
            
        

        marker_2a85fd5d9e27363e485f7f02bfbbed13.bindPopup(popup_e67d068e072c0503cc17c50d9bb64f4e)
        ;

        
    
    
            var marker_de3a2f510d53fef23212eab38d3f3c0a = L.marker(
                [36.6645694, 127.501849],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_a89142b55267b6c5a4f982bd251f4e59 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_de3a2f510d53fef23212eab38d3f3c0a.setIcon(icon_a89142b55267b6c5a4f982bd251f4e59);
        
    
        var popup_281bd6e5cc0bf24cf8cddf041d22e986 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_5428e7a668973284cf8fad0bac2c6760 = $(`<div id="html_5428e7a668973284cf8fad0bac2c6760" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 율량동 1052<br>사고발생일자: 2018-06-26 오전 00:00<br>클러스터: 52</div>`)[0];
                popup_281bd6e5cc0bf24cf8cddf041d22e986.setContent(html_5428e7a668973284cf8fad0bac2c6760);
            
        

        marker_de3a2f510d53fef23212eab38d3f3c0a.bindPopup(popup_281bd6e5cc0bf24cf8cddf041d22e986)
        ;

        
    
    
            var marker_346826a210f9255587745baeb77d546b = L.marker(
                [36.6645694, 127.501849],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_a997e2691a927752f258470fed257524 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_346826a210f9255587745baeb77d546b.setIcon(icon_a997e2691a927752f258470fed257524);
        
    
        var popup_d2b8863566896a4ce55388a2434cf2e5 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_da520eb526a4b656a85aa6c5dc267e3a = $(`<div id="html_da520eb526a4b656a85aa6c5dc267e3a" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 율량동 1183<br>사고발생일자: 2018-04-17 오전 00:00<br>클러스터: 52</div>`)[0];
                popup_d2b8863566896a4ce55388a2434cf2e5.setContent(html_da520eb526a4b656a85aa6c5dc267e3a);
            
        

        marker_346826a210f9255587745baeb77d546b.bindPopup(popup_d2b8863566896a4ce55388a2434cf2e5)
        ;

        
    
    
            var marker_605d447dd4560b6a0bbc95185cbd8f61 = L.marker(
                [36.6645694, 127.501849],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_d0f8a308f18e744a939edf73ed3a495b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_605d447dd4560b6a0bbc95185cbd8f61.setIcon(icon_d0f8a308f18e744a939edf73ed3a495b);
        
    
        var popup_448444771d84c349b2d93056134f9b82 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_09dc67084aa2f4ddb9ea5c99cc2aa3d8 = $(`<div id="html_09dc67084aa2f4ddb9ea5c99cc2aa3d8" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 율량동 1183<br>사고발생일자: 2018-04-17 오전 00:00<br>클러스터: 52</div>`)[0];
                popup_448444771d84c349b2d93056134f9b82.setContent(html_09dc67084aa2f4ddb9ea5c99cc2aa3d8);
            
        

        marker_605d447dd4560b6a0bbc95185cbd8f61.bindPopup(popup_448444771d84c349b2d93056134f9b82)
        ;

        
    
    
            var marker_0b99e940546ea2fbb2171f72845b290a = L.marker(
                [36.6645694, 127.501849],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_ca2e155bc00892cd4b06c1a56767e6d4 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0b99e940546ea2fbb2171f72845b290a.setIcon(icon_ca2e155bc00892cd4b06c1a56767e6d4);
        
    
        var popup_9e2da93fa9f4f70aa5b9d7bb2073de6e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f485fa15afe241b46f32002d9481fd32 = $(`<div id="html_f485fa15afe241b46f32002d9481fd32" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 율량동 1052<br>사고발생일자: 2018-06-26 오전 00:00<br>클러스터: 52</div>`)[0];
                popup_9e2da93fa9f4f70aa5b9d7bb2073de6e.setContent(html_f485fa15afe241b46f32002d9481fd32);
            
        

        marker_0b99e940546ea2fbb2171f72845b290a.bindPopup(popup_9e2da93fa9f4f70aa5b9d7bb2073de6e)
        ;

        
    
    
            var marker_f24cd65c17e155379cd5a59b678ef030 = L.marker(
                [36.6491506, 127.4888956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_4c28fefca77427d35d5287f0f3a8a003 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f24cd65c17e155379cd5a59b678ef030.setIcon(icon_4c28fefca77427d35d5287f0f3a8a003);
        
    
        var popup_88f566b95c4d8568c86ff1c7177bba76 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_2aea2ba2dbe54b2ca1e853792baf504a = $(`<div id="html_2aea2ba2dbe54b2ca1e853792baf504a" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 우암동 397-20<br>사고발생일자: 2018-04-02 오전 00:00<br>클러스터: 53</div>`)[0];
                popup_88f566b95c4d8568c86ff1c7177bba76.setContent(html_2aea2ba2dbe54b2ca1e853792baf504a);
            
        

        marker_f24cd65c17e155379cd5a59b678ef030.bindPopup(popup_88f566b95c4d8568c86ff1c7177bba76)
        ;

        
    
    
            var marker_ede10004f7d70537429a730043cf5e2a = L.marker(
                [36.6491506, 127.4888956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_9bc6a81406704556548fc71cfbc8db7b = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ede10004f7d70537429a730043cf5e2a.setIcon(icon_9bc6a81406704556548fc71cfbc8db7b);
        
    
        var popup_f06dc02d2733b8f69aee4a1b1247cee7 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_ed4a54fa43c8102e15db40fd2fc919f7 = $(`<div id="html_ed4a54fa43c8102e15db40fd2fc919f7" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 우암동 397-20<br>사고발생일자: 2018-04-02 오전 00:00<br>클러스터: 53</div>`)[0];
                popup_f06dc02d2733b8f69aee4a1b1247cee7.setContent(html_ed4a54fa43c8102e15db40fd2fc919f7);
            
        

        marker_ede10004f7d70537429a730043cf5e2a.bindPopup(popup_f06dc02d2733b8f69aee4a1b1247cee7)
        ;

        
    
    
            var marker_7b3b3db7f7ebe818edf4b8aaf1243108 = L.marker(
                [36.6491506, 127.4888956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_e5965c81f6d2adfdf511cbcd616f2928 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_7b3b3db7f7ebe818edf4b8aaf1243108.setIcon(icon_e5965c81f6d2adfdf511cbcd616f2928);
        
    
        var popup_97c05f1c42ef46e1c1ce8fda616353c1 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1f291e3405da2c6345a489ec1bba9b89 = $(`<div id="html_1f291e3405da2c6345a489ec1bba9b89" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 우암동 766-6<br>사고발생일자: 2018-04-04 오전 00:00<br>클러스터: 53</div>`)[0];
                popup_97c05f1c42ef46e1c1ce8fda616353c1.setContent(html_1f291e3405da2c6345a489ec1bba9b89);
            
        

        marker_7b3b3db7f7ebe818edf4b8aaf1243108.bindPopup(popup_97c05f1c42ef46e1c1ce8fda616353c1)
        ;

        
    
    
            var marker_f72d612168d8e29dcda2c051277a9735 = L.marker(
                [36.6491506, 127.4888956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_5fc3582168421bcaf9fe88aa47689099 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_f72d612168d8e29dcda2c051277a9735.setIcon(icon_5fc3582168421bcaf9fe88aa47689099);
        
    
        var popup_76372d16f23353a3269fe4c84973d888 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_890ffd0ed062f39092282347c6152a0d = $(`<div id="html_890ffd0ed062f39092282347c6152a0d" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 우암동 766-6<br>사고발생일자: 2018-04-04 오전 00:00<br>클러스터: 53</div>`)[0];
                popup_76372d16f23353a3269fe4c84973d888.setContent(html_890ffd0ed062f39092282347c6152a0d);
            
        

        marker_f72d612168d8e29dcda2c051277a9735.bindPopup(popup_76372d16f23353a3269fe4c84973d888)
        ;

        
    
    
            var marker_188fefb1c9505158b03fa61c6bf1067c = L.marker(
                [36.6491506, 127.4888956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_568ea761f6b91c51d83d1b3a2fbedd7e = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_188fefb1c9505158b03fa61c6bf1067c.setIcon(icon_568ea761f6b91c51d83d1b3a2fbedd7e);
        
    
        var popup_29f35b79b01846d08475ea28d2ae6b77 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_4d6d2a0b126d1a8840c70ba7cf3d01ef = $(`<div id="html_4d6d2a0b126d1a8840c70ba7cf3d01ef" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 우암동 333-11<br>사고발생일자: 2018-06-12 오전 00:00<br>클러스터: 53</div>`)[0];
                popup_29f35b79b01846d08475ea28d2ae6b77.setContent(html_4d6d2a0b126d1a8840c70ba7cf3d01ef);
            
        

        marker_188fefb1c9505158b03fa61c6bf1067c.bindPopup(popup_29f35b79b01846d08475ea28d2ae6b77)
        ;

        
    
    
            var marker_90527c82a492c76cae2ad41c93bb1a85 = L.marker(
                [36.6491506, 127.4888956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_c902646ea8044f2e2876390ade74f33e = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_90527c82a492c76cae2ad41c93bb1a85.setIcon(icon_c902646ea8044f2e2876390ade74f33e);
        
    
        var popup_0aa03b97bf3af2baa26dbde16870017e = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_e4a4abfea636b14a960e5546543677d9 = $(`<div id="html_e4a4abfea636b14a960e5546543677d9" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 우암동 333-11<br>사고발생일자: 2018-06-12 오전 00:00<br>클러스터: 53</div>`)[0];
                popup_0aa03b97bf3af2baa26dbde16870017e.setContent(html_e4a4abfea636b14a960e5546543677d9);
            
        

        marker_90527c82a492c76cae2ad41c93bb1a85.bindPopup(popup_0aa03b97bf3af2baa26dbde16870017e)
        ;

        
    
    
            var marker_e885fdebf3f86aa272bb4d593ee27420 = L.marker(
                [36.6491506, 127.4888956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_2036bf3a77179f78dca53a23c8092c91 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_e885fdebf3f86aa272bb4d593ee27420.setIcon(icon_2036bf3a77179f78dca53a23c8092c91);
        
    
        var popup_f3525fef440d85a3cc937ecf9f8bfba2 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_74a829e39503dd700c5656262fc5616c = $(`<div id="html_74a829e39503dd700c5656262fc5616c" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 우암동 111-13<br>사고발생일자: 2018-05-30 오전 00:00<br>클러스터: 53</div>`)[0];
                popup_f3525fef440d85a3cc937ecf9f8bfba2.setContent(html_74a829e39503dd700c5656262fc5616c);
            
        

        marker_e885fdebf3f86aa272bb4d593ee27420.bindPopup(popup_f3525fef440d85a3cc937ecf9f8bfba2)
        ;

        
    
    
            var marker_fe2c27aa2226a52669375009103aa070 = L.marker(
                [36.6491506, 127.4888956],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_a4fc2f4530b67fc89137ba3196d5f7cc = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_fe2c27aa2226a52669375009103aa070.setIcon(icon_a4fc2f4530b67fc89137ba3196d5f7cc);
        
    
        var popup_161b34fb221ff884d63ef2f1c1e50b79 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_be68c333a241da4211d5233dcacdd04e = $(`<div id="html_be68c333a241da4211d5233dcacdd04e" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 우암동 111-13<br>사고발생일자: 2018-05-30 오전 00:00<br>클러스터: 53</div>`)[0];
                popup_161b34fb221ff884d63ef2f1c1e50b79.setContent(html_be68c333a241da4211d5233dcacdd04e);
            
        

        marker_fe2c27aa2226a52669375009103aa070.bindPopup(popup_161b34fb221ff884d63ef2f1c1e50b79)
        ;

        
    
    
            var marker_3db2ad2fe82c7026154922d8802f2ad0 = L.marker(
                [36.6340352, 127.4634162],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_010eb2bb716ecb559b69292ecff063ce = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_3db2ad2fe82c7026154922d8802f2ad0.setIcon(icon_010eb2bb716ecb559b69292ecff063ce);
        
    
        var popup_24371fbfa17af5d23972aeca9a84a0c6 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_a1228ff46a154fcfeb0c0c6e12826e64 = $(`<div id="html_a1228ff46a154fcfeb0c0c6e12826e64" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 서원구 사창동 사창동 149-11<br>사고발생일자: 2018-06-11 오전 00:00<br>클러스터: 54</div>`)[0];
                popup_24371fbfa17af5d23972aeca9a84a0c6.setContent(html_a1228ff46a154fcfeb0c0c6e12826e64);
            
        

        marker_3db2ad2fe82c7026154922d8802f2ad0.bindPopup(popup_24371fbfa17af5d23972aeca9a84a0c6)
        ;

        
    
    
            var marker_509436cb44495c257f67575ddb91a5c1 = L.marker(
                [36.6340352, 127.4634162],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_59280dc691f646857a47968bccc679df = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_509436cb44495c257f67575ddb91a5c1.setIcon(icon_59280dc691f646857a47968bccc679df);
        
    
        var popup_a4e49c0352361d8d68de71f08c4450bf = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f2c420bdb5de68edca15966951746337 = $(`<div id="html_f2c420bdb5de68edca15966951746337" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 서원구 사창동 154-1<br>사고발생일자: 2018-05-31 오전 00:00<br>클러스터: 54</div>`)[0];
                popup_a4e49c0352361d8d68de71f08c4450bf.setContent(html_f2c420bdb5de68edca15966951746337);
            
        

        marker_509436cb44495c257f67575ddb91a5c1.bindPopup(popup_a4e49c0352361d8d68de71f08c4450bf)
        ;

        
    
    
            var marker_64c5f8c12239e24692666006d7d3cb71 = L.marker(
                [36.6023493, 127.5035348],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_7a514775b1172c3089f9d907e6eb6bcf = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_64c5f8c12239e24692666006d7d3cb71.setIcon(icon_7a514775b1172c3089f9d907e6eb6bcf);
        
    
        var popup_84839c1dd19df25696dabe782614c3da = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_6d4a3d7199c25a698fec4a9a3572fc29 = $(`<div id="html_6d4a3d7199c25a698fec4a9a3572fc29" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 상당구 방서동 644-117<br>사고발생일자: 2018-02-01 오전 00:00<br>클러스터: 55</div>`)[0];
                popup_84839c1dd19df25696dabe782614c3da.setContent(html_6d4a3d7199c25a698fec4a9a3572fc29);
            
        

        marker_64c5f8c12239e24692666006d7d3cb71.bindPopup(popup_84839c1dd19df25696dabe782614c3da)
        ;

        
    
    
            var marker_eb92f5399bf228fa741ada9b3007c326 = L.marker(
                [36.6023493, 127.5035348],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_0598f2b7a8c24e8be595cbcc034fa2b8 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_eb92f5399bf228fa741ada9b3007c326.setIcon(icon_0598f2b7a8c24e8be595cbcc034fa2b8);
        
    
        var popup_29a543406135b1488ac2e8198dfe527a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_97571631371ebf2401ff66cfb9e6ca58 = $(`<div id="html_97571631371ebf2401ff66cfb9e6ca58" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 상당구 방서동 210-3<br>사고발생일자: 2018-06-10 오전 00:00<br>클러스터: 55</div>`)[0];
                popup_29a543406135b1488ac2e8198dfe527a.setContent(html_97571631371ebf2401ff66cfb9e6ca58);
            
        

        marker_eb92f5399bf228fa741ada9b3007c326.bindPopup(popup_29a543406135b1488ac2e8198dfe527a)
        ;

        
    
    
            var marker_48ac58d111b115dd1243b0d7c8825dbc = L.marker(
                [36.6059863, 127.4898563],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_3f84776cd0d89e45ec78e46688d2e638 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_48ac58d111b115dd1243b0d7c8825dbc.setIcon(icon_3f84776cd0d89e45ec78e46688d2e638);
        
    
        var popup_7f29f32f649055de25959f1e35ba56cc = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1f3455470b0ca1e4dfe1ad95cadc2ae1 = $(`<div id="html_1f3455470b0ca1e4dfe1ad95cadc2ae1" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 서원구 분평동 249-26<br>사고발생일자: 2018-06-07 오전 00:00<br>클러스터: 56</div>`)[0];
                popup_7f29f32f649055de25959f1e35ba56cc.setContent(html_1f3455470b0ca1e4dfe1ad95cadc2ae1);
            
        

        marker_48ac58d111b115dd1243b0d7c8825dbc.bindPopup(popup_7f29f32f649055de25959f1e35ba56cc)
        ;

        
    
    
            var marker_1a41ccd589266b0e7370844b4ce92225 = L.marker(
                [36.6059863, 127.4898563],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_6ca50d679a78e3c176a16220de7dbdef = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_1a41ccd589266b0e7370844b4ce92225.setIcon(icon_6ca50d679a78e3c176a16220de7dbdef);
        
    
        var popup_6fc8299223b2b624636e195c3313db25 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_f4e75ca7fa3bbcc7bfe5777dbce28f07 = $(`<div id="html_f4e75ca7fa3bbcc7bfe5777dbce28f07" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 서원구 분평동 249-5<br>사고발생일자: 2018-05-14 오전 00:00<br>클러스터: 56</div>`)[0];
                popup_6fc8299223b2b624636e195c3313db25.setContent(html_f4e75ca7fa3bbcc7bfe5777dbce28f07);
            
        

        marker_1a41ccd589266b0e7370844b4ce92225.bindPopup(popup_6fc8299223b2b624636e195c3313db25)
        ;

        
    
    
            var marker_66a3214373145e45775b6b2695d110d5 = L.marker(
                [36.6059863, 127.4898563],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_5df2fae70c948103d13a1eae125b8a6c = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_66a3214373145e45775b6b2695d110d5.setIcon(icon_5df2fae70c948103d13a1eae125b8a6c);
        
    
        var popup_1f0ced299870387c73d0ab83bd2261aa = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_341680ebec293c07e1bf9a9ad038df9e = $(`<div id="html_341680ebec293c07e1bf9a9ad038df9e" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 서원구 분평동 1385<br>사고발생일자: 2018-06-06 오전 00:00<br>클러스터: 56</div>`)[0];
                popup_1f0ced299870387c73d0ab83bd2261aa.setContent(html_341680ebec293c07e1bf9a9ad038df9e);
            
        

        marker_66a3214373145e45775b6b2695d110d5.bindPopup(popup_1f0ced299870387c73d0ab83bd2261aa)
        ;

        
    
    
            var marker_0086e547c52a445bcbd85287c6668e53 = L.marker(
                [36.6624407, 127.5067783],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_1d66094e4635166f1bd71ce7e8b40d0e = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0086e547c52a445bcbd85287c6668e53.setIcon(icon_1d66094e4635166f1bd71ce7e8b40d0e);
        
    
        var popup_eea3a60187e58f7d3d9446f806dbf9c8 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b825e5f9940dbc68ebd2e9b0f566fb26 = $(`<div id="html_b825e5f9940dbc68ebd2e9b0f566fb26" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 율량동 1015<br>사고발생일자: 2018-06-01 오전 00:00<br>클러스터: 57</div>`)[0];
                popup_eea3a60187e58f7d3d9446f806dbf9c8.setContent(html_b825e5f9940dbc68ebd2e9b0f566fb26);
            
        

        marker_0086e547c52a445bcbd85287c6668e53.bindPopup(popup_eea3a60187e58f7d3d9446f806dbf9c8)
        ;

        
    
    
            var marker_75c9314013b23a9cecdfbc51f597dd98 = L.marker(
                [36.6624407, 127.5067783],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_b097576f545d522c23ec92425a21b1e7 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_75c9314013b23a9cecdfbc51f597dd98.setIcon(icon_b097576f545d522c23ec92425a21b1e7);
        
    
        var popup_84d315c74c727ed014ed98ed73e5e323 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b4262f2cf63712320b635cf6baa0d73e = $(`<div id="html_b4262f2cf63712320b635cf6baa0d73e" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 율량동 1015<br>사고발생일자: 2018-06-01 오전 00:00<br>클러스터: 57</div>`)[0];
                popup_84d315c74c727ed014ed98ed73e5e323.setContent(html_b4262f2cf63712320b635cf6baa0d73e);
            
        

        marker_75c9314013b23a9cecdfbc51f597dd98.bindPopup(popup_84d315c74c727ed014ed98ed73e5e323)
        ;

        
    
    
            var marker_a84cd570acdee51f72b3cdd1ad0e7191 = L.marker(
                [36.6577738, 127.489478],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_61186d273282bdbbc7f4e1fc474a7c16 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_a84cd570acdee51f72b3cdd1ad0e7191.setIcon(icon_61186d273282bdbbc7f4e1fc474a7c16);
        
    
        var popup_21a667afcaff10f2f83d86d6a2d15012 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1072cb45baa02689eb51cbf01b0520b7 = $(`<div id="html_1072cb45baa02689eb51cbf01b0520b7" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 내덕동 740-10<br>사고발생일자: 2018-05-03 오전 00:00<br>클러스터: 58</div>`)[0];
                popup_21a667afcaff10f2f83d86d6a2d15012.setContent(html_1072cb45baa02689eb51cbf01b0520b7);
            
        

        marker_a84cd570acdee51f72b3cdd1ad0e7191.bindPopup(popup_21a667afcaff10f2f83d86d6a2d15012)
        ;

        
    
    
            var marker_e95235e87f740bbc33d84e8569b81444 = L.marker(
                [36.6577738, 127.489478],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_dc228af5b5fd4f2e0ad9e41dcf0a5a9a = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_e95235e87f740bbc33d84e8569b81444.setIcon(icon_dc228af5b5fd4f2e0ad9e41dcf0a5a9a);
        
    
        var popup_c07e664ec501fb365abfe88b2c505753 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_b6cb37f0c32b035f6a5cbccc9082d991 = $(`<div id="html_b6cb37f0c32b035f6a5cbccc9082d991" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 내덕동 740-10<br>사고발생일자: 2018-05-03 오전 00:00<br>클러스터: 58</div>`)[0];
                popup_c07e664ec501fb365abfe88b2c505753.setContent(html_b6cb37f0c32b035f6a5cbccc9082d991);
            
        

        marker_e95235e87f740bbc33d84e8569b81444.bindPopup(popup_c07e664ec501fb365abfe88b2c505753)
        ;

        
    
    
            var marker_0433916c7a4020fb8707200b8ec3b4fe = L.marker(
                [36.6577738, 127.489478],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_a95d60cde87f9671326d6a3ea7710ed4 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0433916c7a4020fb8707200b8ec3b4fe.setIcon(icon_a95d60cde87f9671326d6a3ea7710ed4);
        
    
        var popup_9c03ae777df84d860f8149c32434ec8c = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_5b7f51b9405d416a81d444a9da028995 = $(`<div id="html_5b7f51b9405d416a81d444a9da028995" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 내덕동 740-10<br>사고발생일자: 2018-03-22 오전 00:00<br>클러스터: 58</div>`)[0];
                popup_9c03ae777df84d860f8149c32434ec8c.setContent(html_5b7f51b9405d416a81d444a9da028995);
            
        

        marker_0433916c7a4020fb8707200b8ec3b4fe.bindPopup(popup_9c03ae777df84d860f8149c32434ec8c)
        ;

        
    
    
            var marker_43a7f8514704f5a7248d7dc88b26716a = L.marker(
                [36.6577738, 127.489478],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_00091b0dd797d905991ffa94302cd468 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_43a7f8514704f5a7248d7dc88b26716a.setIcon(icon_00091b0dd797d905991ffa94302cd468);
        
    
        var popup_a5b6c7ab9950185739fc2ed6e227af22 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_cef5330825074ed0eea5e0bf2329d3bb = $(`<div id="html_cef5330825074ed0eea5e0bf2329d3bb" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 내덕동 740-10<br>사고발생일자: 2018-03-22 오전 00:00<br>클러스터: 58</div>`)[0];
                popup_a5b6c7ab9950185739fc2ed6e227af22.setContent(html_cef5330825074ed0eea5e0bf2329d3bb);
            
        

        marker_43a7f8514704f5a7248d7dc88b26716a.bindPopup(popup_a5b6c7ab9950185739fc2ed6e227af22)
        ;

        
    
    
            var marker_07fbce6c2cd088c2d98ebf52600a29e3 = L.marker(
                [36.6577738, 127.489478],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_b8f7081b881a22ca55f0d6f4ea5981aa = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_07fbce6c2cd088c2d98ebf52600a29e3.setIcon(icon_b8f7081b881a22ca55f0d6f4ea5981aa);
        
    
        var popup_05585cc01d8cf67dea36287ba45318a2 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_1451eb57a687a3ebac338fd4c3c51843 = $(`<div id="html_1451eb57a687a3ebac338fd4c3c51843" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 내덕동 648-14<br>사고발생일자: 2018-03-10 오전 00:00<br>클러스터: 58</div>`)[0];
                popup_05585cc01d8cf67dea36287ba45318a2.setContent(html_1451eb57a687a3ebac338fd4c3c51843);
            
        

        marker_07fbce6c2cd088c2d98ebf52600a29e3.bindPopup(popup_05585cc01d8cf67dea36287ba45318a2)
        ;

        
    
    
            var marker_0e665272bba9de63a28d0f7a447177cd = L.marker(
                [36.6577738, 127.489478],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_dff921f6ad42dbea70505486e9f7248f = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0e665272bba9de63a28d0f7a447177cd.setIcon(icon_dff921f6ad42dbea70505486e9f7248f);
        
    
        var popup_b048b9f8b5266a584fcd3845576d3294 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_bca720cc7f538eb236def9b505b7d06f = $(`<div id="html_bca720cc7f538eb236def9b505b7d06f" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 내덕동 648-14<br>사고발생일자: 2018-03-10 오전 00:00<br>클러스터: 58</div>`)[0];
                popup_b048b9f8b5266a584fcd3845576d3294.setContent(html_bca720cc7f538eb236def9b505b7d06f);
            
        

        marker_0e665272bba9de63a28d0f7a447177cd.bindPopup(popup_b048b9f8b5266a584fcd3845576d3294)
        ;

        
    
    
            var marker_b62fc34b25b18f772e56256a860f0372 = L.marker(
                [36.6577738, 127.489478],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_91e20bbce4fb806182216f667667d2d3 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_b62fc34b25b18f772e56256a860f0372.setIcon(icon_91e20bbce4fb806182216f667667d2d3);
        
    
        var popup_690cbc705aee7cec46f017d458d4af95 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_72acd372b405a981303276d43e34c364 = $(`<div id="html_72acd372b405a981303276d43e34c364" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 내덕동 188-3<br>사고발생일자: 2018-05-11 오전 00:00<br>클러스터: 58</div>`)[0];
                popup_690cbc705aee7cec46f017d458d4af95.setContent(html_72acd372b405a981303276d43e34c364);
            
        

        marker_b62fc34b25b18f772e56256a860f0372.bindPopup(popup_690cbc705aee7cec46f017d458d4af95)
        ;

        
    
    
            var marker_34b9d75292e4d5ffa03cde289e217979 = L.marker(
                [36.6577738, 127.489478],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_809c77fa91dd88dba2f3a4c92f8882ba = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_34b9d75292e4d5ffa03cde289e217979.setIcon(icon_809c77fa91dd88dba2f3a4c92f8882ba);
        
    
        var popup_c6fea148a277f15d21a1a1eaadca857a = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_0bff61f3916897292967b134f6862def = $(`<div id="html_0bff61f3916897292967b134f6862def" style="width: 100.0%; height: 100.0%;">사고발생 위치: 충청북도 청주시 청원구 내덕동 188-3<br>사고발생일자: 2018-05-11 오전 00:00<br>클러스터: 58</div>`)[0];
                popup_c6fea148a277f15d21a1a1eaadca857a.setContent(html_0bff61f3916897292967b134f6862def);
            
        

        marker_34b9d75292e4d5ffa03cde289e217979.bindPopup(popup_c6fea148a277f15d21a1a1eaadca857a)
        ;

        
    
    
            var marker_0afcd422295fbd68972f5fc310b7b76f = L.marker(
                [37.4750208, 126.7960639],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_baf68e502398e2dab433279546d8fd3e = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_0afcd422295fbd68972f5fc310b7b76f.setIcon(icon_baf68e502398e2dab433279546d8fd3e);
        
    
        var popup_a64689fd67e6e1b479b0d5f355e8a537 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_6912d7ffd6361290dd383270f3a05a31 = $(`<div id="html_6912d7ffd6361290dd383270f3a05a31" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 소사본동  196<br>사고발생일자: 2018-04-02 오전 00:00<br>클러스터: 59</div>`)[0];
                popup_a64689fd67e6e1b479b0d5f355e8a537.setContent(html_6912d7ffd6361290dd383270f3a05a31);
            
        

        marker_0afcd422295fbd68972f5fc310b7b76f.bindPopup(popup_a64689fd67e6e1b479b0d5f355e8a537)
        ;

        
    
    
            var marker_bfb495342006f1a438adfac72afaee3e = L.marker(
                [37.4750208, 126.7960639],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_907f9ab78cfff88966e355fb0ffa0cc0 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_bfb495342006f1a438adfac72afaee3e.setIcon(icon_907f9ab78cfff88966e355fb0ffa0cc0);
        
    
        var popup_386290cc6bf382c4a0d392c0093b626c = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_89acde7fbb4680b6cb1a227d6f300c85 = $(`<div id="html_89acde7fbb4680b6cb1a227d6f300c85" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 소사본동  148-9<br>사고발생일자: 2018-02-06 오전 00:00<br>클러스터: 59</div>`)[0];
                popup_386290cc6bf382c4a0d392c0093b626c.setContent(html_89acde7fbb4680b6cb1a227d6f300c85);
            
        

        marker_bfb495342006f1a438adfac72afaee3e.bindPopup(popup_386290cc6bf382c4a0d392c0093b626c)
        ;

        
    
    
            var marker_8cc721ac4c3385b949dee6f8bc2a5229 = L.marker(
                [37.4926826, 126.7914425],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_4b3b1433ff2ef08eb00290801cfd55d2 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_8cc721ac4c3385b949dee6f8bc2a5229.setIcon(icon_4b3b1433ff2ef08eb00290801cfd55d2);
        
    
        var popup_1442c849023cb5c3717e083f1724f172 = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_906bfd7e755e146fca1252dd28c3d599 = $(`<div id="html_906bfd7e755e146fca1252dd28c3d599" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 원미동 189-96<br>사고발생일자: 2018-03-15 오전 00:00<br>클러스터: 60</div>`)[0];
                popup_1442c849023cb5c3717e083f1724f172.setContent(html_906bfd7e755e146fca1252dd28c3d599);
            
        

        marker_8cc721ac4c3385b949dee6f8bc2a5229.bindPopup(popup_1442c849023cb5c3717e083f1724f172)
        ;

        
    
    
            var marker_ad3d0569811f0363261a7c7b5de9fc58 = L.marker(
                [37.4926826, 126.7914425],
                {
}
            ).addTo(map_59bfbb039e60e8b3f1943f352691808d);
        
    
            var icon_e473e86447068373293bac3d132bc196 = L.AwesomeMarkers.icon(
                {
  "markerColor": "orange",
  "iconColor": "white",
  "icon": "triangle-exclamation",
  "prefix": "fa",
  "extraClasses": "fa-rotate-0",
}
            );
            marker_ad3d0569811f0363261a7c7b5de9fc58.setIcon(icon_e473e86447068373293bac3d132bc196);
        
    
        var popup_776d4e7e5abf4eb530786d8e2966331f = L.popup({
  "maxWidth": "100%",
});

        
            
                var html_4f80c791545ee5044a2c9dc9a58405ac = $(`<div id="html_4f80c791545ee5044a2c9dc9a58405ac" style="width: 100.0%; height: 100.0%;">사고발생 위치: 경기도 부천시 원미동 181-3<br>사고발생일자: 2018-03-13 오전 00:00<br>클러스터: 60</div>`)[0];
                popup_776d4e7e5abf4eb530786d8e2966331f.setContent(html_4f80c791545ee5044a2c9dc9a58405ac);
            
        

        marker_ad3d0569811f0363261a7c7b5de9fc58.bindPopup(popup_776d4e7e5abf4eb530786d8e2966331f)
        ;

        
    
</script>
</html>
