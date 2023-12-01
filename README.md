# Swapped-Faces-ETRI-Dataset(SFED)
![title](https://github.com/EtriHRIFace/Face-Dataset/assets/149992598/c1b230e6-242c-4dd7-8bd5-ccd2b8d2e7ec)
<br>
## 1. Overview of swapped facial dataset 
  We created a facial dataset by capturing images in various environments using cameras, featuring faces adorned with masks, sunglasses, hats, scarves, or left unadorned. The dataset accounts for real-world conditions, including lighting, distance, pose, and camera resolution. To protect privacy, we transformed facial image data acquired in real-world scenarios into swapped faces and are making it available as open data. The compiled face swap dataset is accessible for research purposes
### 1) Data Collection Target
  * 50 males and 50 females
### 2) Data Acquisition Environment 
  * Types of cameras : UHD, QHD, FHD, HD cameras <br>
  * Camera height : 3m, 2.5m, 2m <br>
  * Accessories used: Mask, Sunglasses, Hat, Scarf <br>
  * Lighting conditions : Left, Right, Bilateral lighting <br>
  * Distance from the camera : 4m, 3m, 2m, 1m <br>
  * Pose variation : Frontal view, Left and right profile at 45 degrees/90 degrees
 ![facefile1](https://github.com/EtriHRIFace/Face-Dataset/assets/149992598/6776df9b-7bfa-42a9-8845-0d6be03af441)
### 3) Data collection time
 * 2 hours in the morning, 2 hours in the afternoon, 2 hours in the evening (after sunset)
### 4) Mask Images
 * 100 images from [CelebA-HQ-Deltas](https://drive.google.com/drive/folders/0B4qLcYyJmiz0TXY1NG02bzZVRGs?resourcekey=0-arAVTUfW9KRhN-irJchVKQ) are used as mask images, which are images used to swap the original facial images.
![mask image](https://github.com/EtriHRIFace/Face-Dataset/assets/149992598/07c501e6-0f21-4be9-b717-291c1d159028)


## 2. Dataset composition
### 1) Performance validation facial dataset 
* Enroll face data set : 100 individuals x 12 images of frontal faces <br>
* Verify face data set : 100 individuals x 100 images of frontal or side faces <br>
### 2) Full facial dataset  
All data is hosted on Google Drive:
* 5,697,636 images for 100 individuals (5.22 TB) 

| Path | Size | Files | Format | Description
| :---- | :---: | -----: | :-----: | :----------
|[SFED](https://drive.google.com/drive/folders/0AC6PJOIeh1ufUk9PVA?q=parent:0AC6PJOIeh1ufUk9PVA%20sharedwith:public) | 5.2TB|5,697,636 | JPG | Main folder
|&boxvr;&nbsp; [Enroll](https://drive.google.com/file/d/10i87Ht9TpDC3woLif5d0Dh5n768ceeMI/view?usp=sharing) | 1.08GB|1,200 | JPG | 12 frontal images for each of the 100 individuals
|&boxvr;&nbsp; [Verify](https://drive.google.com/file/d/1YJ4m6w6NkriC-ouGLoz6OCysNUIg5SuL/view?usp=sharing) | 9.46GB|10,000 | JPG | 100 images for each of the 100 individuals
|&boxvr;&nbsp; [Valid-1](https://drive.google.com/file/d/1CLZBIpax7MWQQw3x0xejz6lCw76VnpyM/view?usp=sharing) | 1.2GB|650 | JPG | Multi-resolution for each of the 100 individuals at 3840×2160/1920x1080/2688x1520

 
## 3. Examples of sample data
### 1) Enroll facial images  
![Enroll](https://github.com/EtriHRIFace/Face-Dataset/assets/149992598/829cdee9-e500-4dfd-b18e-6f725036e851)
### 2) Verify facial images
![Verify](https://github.com/EtriHRIFace/Face-Dataset/assets/149992598/b678f427-a2c3-4add-b4c3-6a34296f3a05)
* The facial dataset includes facial images with some flickering, caused by the capturing environment.
## 4. Data Download method
If you are interested in acquiring the dataset, please contact us at the provided email( jangjy@etri.re.kr), and we will assist you in accessing the data. <br>
<br>

## Licenses
Swapped-faces-Etri-Dataset (SFED) is available for non-commercial research purposes only. All images in the SFED dataset are the property of the Electronics and Telecommunications Research Institute (ETRI). The license allows for free use, redistribution, and adaptation for non-commercial purposes. Compliance with the following is required when applied for non-commercial purposes:
* The images cannot be sold, traded, or used for commercial purposes.
* Do not publish or distribute without the consent of ETRI.
* ETRI reserves the right to terminate access to the SFED dataset at any time. For further details, please contact us.

## Acknowledgement
This work was supported by the Institute of Information & communications Technology Planning & Evaluation(IITP) grant funded by the Korea government(MSIT) (No. 2021-0-00172, The development of human Re-identification and masked face recognition based on CCTV camera)
<br>
## Contact information
Contact jangjy@etri.re.kr
