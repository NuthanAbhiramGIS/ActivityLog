# Creating a Virtual Machine

Date: 03-07-2024
Start time: 12 pm
End time: 12:50 pm
Total time: 50 min
(Energy: Moderate)
Value: High


## Steps Followed

1. A new VM instance has been enabled by the “create new instance” option that will be available in the compute engine – VM Instances – Enable.
2. The name of this VM should be given accordingly.
3. The VM image is selected from the Boot disk from a different VM.
4. Firewall settings are updated to let the web server work and a new VM has been created.
5. After the instance is created, the Windows password for the account needs to be saved which will be available in the “set new Windows password” option.

## Outcomes

1. The image has been loaded successfully.
2. Firewall settings have been updated.
3. VM has been created successfully.

## Next Steps 

Access the VM through a remote desktop and publish the map.

## Resources

•	Console.cloud.google.com
•	https://youtu.be/dyFeyBX9jIY 
•	Resources provided by lecturer.


# Accessing remote desktop 

Date: 03-07-2024
Start time: 01:00 pm
End time: 01: 20 pm
Total time: 20 min
(Energy: Moderate)
Value: High


## Steps Followed
1. Open the remote desktop connection application on the PC. 
2. The external IP of the VM instance needs to be used to connect through this.
3. This external IP will be changed every time we shut down the server. TCP port needs to be provided along with the external IP.
4. Now the machine is connected, and the data is copied to the local machine.
5. Open the ArcGIS server manager and provide the credentials. This will help to check the content available.

## Outcomes

1. Connecting to a remote desktop using the external IP of the VM instance.
2. Understood the use of Windows username and password.


![before shutdown](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/bac53a6e-150e-4160-b9c9-2cb7f71de6e6)


## Next Steps 

Publish the map through the ArcGIS server using ArcGIS Pro.

Note: Shut down the server after the publishing process is completed to save credits. To shut down, go to the newly created VM instance click on “three dots” and click “stop”.


## Resources

https://www.youtube.com/watch?v=dyFeyBX9jIY

# Publishing the map through the ArcGIS server

Date: 03-07-2024
Start time: 1:20 pm
End time:2:10 pm
Total time: 50 min
(Energy: Moderate)
Value: High


## Steps Followed
1. ArcGIS Pro is used to add the data from the folder which was on the virtual machine.
2. The folder was registered in the publisher folder path.
3. The server should be added successfully.
4. ArcGIS manager was set according to the credentials that were set.
5. ArcGIS pro server publish

## Outcomes

1. The map was published on the ArcGIS server. The IP address of the computer which was the external IP in the VM machine played a server role in this instance.
2. https://34.42.157.184:6443/arcgis/rest/services/NChenell_Web/MapServer (Link might not work in future)

![Serverconnectionss](https://github.com/NuthanAbhiramGIS/Activitylog/assets/146375982/833a0896-b55e-4e05-b0c4-26c5d14ce0b6)


## Next Steps 

1. Check whether the map published was successful.

2. Continue with other items on checklist and join a group for the project.

## Resources

1. ArcGIS Server Manager
2. ArcGIS Pro
3. Resources provided by professor.



