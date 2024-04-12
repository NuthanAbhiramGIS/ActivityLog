# Integrating two layers in leaflet code that was created

Date: 04-11-2024
Start time: 12:00 pm
End time: 1:30 pm
Total time: 90 min
Energy: High
Value: High

## Step followed
1. A html file with inclusion of code related to leaflet is already created. This file is edited so that two Geojson layers are include in one leaflet map.
2. A new Geojson layer with name “geojsonlayer2” is created.
![Layers1](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/f8cf7bff-64d0-4f5b-a2ea-5fe3f8ff4b97)
3. As this layer will have same functions related to the first layer, same code is assigned to this layer also.
![layers2new](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/89bfa6a5-681d-4a75-a881-2971d1e1ad6d)
4. Map was not loading after this new layer was added and the code is edited.
5.The problem was with the fetchdata function which was used for the first map.
6. Fetchdata should be separate for each layer. Therefore, the parameter was changed to fetchdata1 and fetchdata2 are used to get data from layer 1 and layer 2.
![Layers3](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/0dc1e23b-f47f-4282-acbb-f32e1efa8aea)
7. Customized marker is added to display newly collected data so that there is a difference between first layer’s data and second layer’s data.
![Layers4](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/8179f509-6697-46cd-9ee1-01344850ec3f)

## Outcomes

1. Two layers are joined.
2. Data of these two layers has been displayed successfully.
3. The problem related to fetchdata was resolved.
![outcome](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/26c5bb85-f95b-4c1a-b003-ac63b9d52111)


## Next steps

Update these details in website through GitHub repository or VS code.

## Resources:

https://leafletjs.com/

https://stackoverflow.com/







