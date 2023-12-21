# Welcome to the ETH Zurich Geomatics Master Project: <br> "3D model of a cultural heritage building" <br>
This repository contains methods and results of a ETH Zurich Geomatics MSc project developed by Thierry Weber. The project had three main goals: Creating a **digital twin** of a cultural heritage building in Switzerland, including the 3D model in a **VR-Experience** and **assessing the accuracy** of the obtained 3D model. 

## The Model:
<p style="text-align:justify"> The following renderings show the highest quality Mesh of Kreuzkirche created in this project. </p>

![Church Model](ModelScreenshots/Full_MODEL_V10.png)
![Church Model](ModelScreenshots/Full_MODEL_V10_2.png)
![Church Model](ModelScreenshots/Full_MODEL_V10_3.png)
![Church Model](ModelScreenshots/Full_MODEL_V10_4.png)
3D Models to download can be found in the *3D Models* folder. 


## VR-Experience
<p style="text-align:justify">
  The Virtual Reality (VR) experience created as part of this project, has three main functionalities (shown in the GIFS below). First the user can 
  show or hide the information buttons distributed over the scaled 3D model with the big button on the left side of the pedestal. The big button on 
  the right side of the pedestal, allows the user to enlarge the model to full scale and shrink it again. When clicked, the information buttons on the scaled 
  model show information about the church.

</p>
<p float="left">
  <img src="VRExperienceGIFS/com.oculus.vrshell-20231217-120507.gif" width="200" />
  <img src="VRExperienceGIFS/com.oculus.vrshell-20231217-120507_1.gif" width="200" /> 
  <img src="VRExperienceGIFS/PopUpGIF.gif" width="200" /> 
</p>

## Workflow 
<p style="text-align:justify">
  The diagram below provides an overview of the project's workflow. The project started with selecting an interesting cultural heritage building. 
  This was done by visiting mulitple churches in the city of Zurich (Fraumünster, Kirche Enge, Kreuzkirche). After assessing the situation at each church, 
  the decision fell on Kreuzkirche in Hottingen ZH. While planning the data acquisition, not only the required instruments had to be defined, but site access, permits and restrictions had to be checked out.
  With the architectural complexity and size of the church, drone data had to be included to realize this project. With drone flight restictions in Switzerland, clarification for legal drone flight at Kreuzkirche had to be made. TO BE CONTINUED
</p>

![WorkflowDiagram](Workflow/MP_3D_Model_Workflow2_6.drawio.png)
<p style="text-align:justify">
  A more detailed workflow for the integration of the point clouds of all components in Reality Capture is shown in the diagram below.
</p>

![WorkflowDiagram](Workflow/Workflow_RealityCaptureV2.drawio.png)


## Data Acquisition
<p float="left">
  <img src="DataAcquisition/20231019_143718891_iOS.jpg" width="355" />
  <img src="DataAcquisition/20231019_130802292_iOS.jpg" width="200" /> 
  
</p>

![Tragets](DataAcquisition/Target_Overview.PNG)

## Point Cloud Accuracy Assessment 
<p style="text-align: justify">
The following figures show the cloud-to-cloud distance between the point cloud obtained using data and the one obtained only from drone photogrammetry. The differences are in meters. 
As expected, the areas with high discrepancies are the once with data gabs from the drone data. The back facade (alot of red in the plot) was close to high trees, which prevented 
detailed drone images of the facade.
</p>

![CloudToCloudDistance](Cloud-toCloudDistance/Cloud-toCloudDrone-All14.png)
![CloudToCloudDistance Model](Cloud-toCloudDistance/Cloud-toCloudDrone-All8.png)
![CloudToCloudDistance Model](Cloud-toCloudDistance/Cloud-toCloudDrone-All9.png)


