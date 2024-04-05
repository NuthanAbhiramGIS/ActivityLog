# Creating an HTML file with the inclusion of leaflet maps.

date: 04-01-2024
Start time: 8:30 pm
End time: 10:00 pm
Total time: 90 min
Value: High
Energy: Moderate

## Steps followed

1. An HTML file is created with the name “leaflet”. The data which will be shown on the map is the City assets data collected by smart forms created in Field maps.
2. Style sheet and script source are added to this file.
![1](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/9754b964-df0d-41ae-85ba-a1754841de88)
3. The main things involved in the script of this file are the map, tile layer, Geojson layer, fetch data function and set interval function.
4. Leaflet CSS file and Leaflet JavaScript file are linked. The links for both are on the leaflet website.
6. A Div element for the map has been added.
7. The “Var map” function is used to create the map according to the coordinates of the Kawartha Lake region. Zoom is set accordingly. 
![2](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/06367a00-235d-49aa-b5b4-8879d87ff15b)
8. Open street maps tile layer has been added from the link provided on the website. 
![3](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/b40952b4-15b5-45a3-b72a-6840a6c84e99)
9. The Geojson layer is added to the HTML with the help of the function “Var geojsonlayer”.
10. Fetch data function is added to get the data from the Geojson feature server layer link which is added from ArcGIS online. This feature layer’s data will be used and shown as markers with the help of the function “on Each Feature’. 
![5](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/1b936a04-d6e8-4645-a18e-9366cd6da45a)
11. The feature layer here has the data that was collected from the Field maps smart form. 
12. This data will be updated for every 1 minute with the help of the “set interval” function.


## Outcomes
1. The REST end URL of the feature is acquired from the ArcGIS online feature layer.
2. A map is added with the preferred location and tile layers. 
3. The Geojson layer is added with the help of the REST end URL and the data in this layer is being fetched for every 1 minute.
4. Markers are added to the data which will be shown on the map. This data is the city assets data collected by users from field maps in smart form.
   ![6](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/723b75c2-c5ec-4902-9b70-512ef8e5d2ab)

## Resources used
1. https://stackoverflow.com/questions/69125945/leaflet-mapping-assign-object-to-fetch-promise-for-local-geojson-file
2. https://leafletjs.com/index.html
3. https://leafletjs.com/examples/geojson/









