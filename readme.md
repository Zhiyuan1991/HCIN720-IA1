**********This is the HCIN720 IA1***********

Part A: Sparkfun Weather Station
http://rawgit.com/Zhiyuan1991/HCIN720-IA1/master/Weather_Station.html
(1) weather_station.html shows lines of temperature and humidity. The data is provided by sparkfun.com(https://data.sparkfun.com/streams/ZGYmKDKVMxTDxrx6agWa)
(2) Y-axis will automatically change max and min value to show the line more clearly. X-axis shows the time stamp.
(3) Lines will updated when read new data. New data will appear from the right side of the table.

Part B: Twitter World Maps Hotspots
http://rawgit.com/Zhiyuan1991/HCIN720-IA1/master/Twitter_Hotspots.html
(1) Twitter_Hotspots.html shows a Twitter location hotspots on a world map. Once a Twitter is created, there will be a blob showing up at that location.
(2) The world map is draw by "SVG map with locations"(https://codepen.io/stroperik/pen/Ggbbxr). Original license file is copied.
(3) The Twitter data stream is got by Pubnub API(https://www.pubnub.com/developers/realtime-data-streams/twitter-stream/).
(4) In this assignment, I collect Twitter's longitude and latitude from Pubnub API, then convert it to pixel's coordinate and draw a blob on the world map.