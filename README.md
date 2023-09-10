# NASA-SPACE-APPS-CHALLENGE-2021---JEVG
![image](https://github.com/JoseEmmanuelVG/NASA-SPACE-APPS-CHALLENGE-2021---JEVG/assets/89156254/b1ecfe3b-56d3-4ae2-9419-23ce792875b9)

https://2021.spaceappschallenge.org/challenges/statements/identifying-risk-with-science-communities/teams/progressive-landslide-alert/project

# ENGLISH REPORT
##  					**CHALLENGE**
## IDENTIFYING RISK WITH SCIENCE + COMMUNITIES
###### "SOFTWARE AND CONSCIENCE FEED INTELLIGENCE" 

### GENERAL OBJECTIVE
Create prototypes and methodologies to incorporate Earth observations (as satellite data) with local open data provided by national entities and scientific institutes. 
### SECUNDARY OBJECTIVES
Additionally, participants are encouraged to include the information that the general public can contribute by capturing data in their territories to improve the precision of the analysis. 
Finally, any tool or prototype that meets the overall objective of this challenge must potentially be implemented and executed at a low cost by local governments.
### Introduction / Theoretical framework
We can define a landslide as the downward movement of mass (through a process of gravitational fall), in this sense there is primarily the descent of earthy materials such as rock, soil or debris. Said landslide is nothing more than the failure of a slope that leads to a variety of movements in the ground, including rock falls and debris flows.
#### ClassificationClassification
Falls or landslides. They are gravitational processes (practically free fall), originated in large slopes or cliffs, where there is a sudden movement of soils and / or isolated fragments of rocks.
Glide. Downhill mass movements, mainly of earth materials, on one or more fault surfaces delimited by a stable mass of a slope (that or that belonging to or relative to the side), the term slope is often used to name slopes of mountains or of a overall height.
Flow. Those movements of the soils and / or rock fragments sloping down a slope, with relative movements within the mass in which the particles (grains or fragments) move. This type of gliding can be very fast or slow, as well as dry or wet.
#### Factors causing a landslide
 “The general stability of a slope depends on internal and external factors and its analysis is carried out from the definition of the acting forces and the resisting forces. "
Terzaghi (1950)


 In this way, we have the following conditions:
 
o	**Discontinuities**. Interruptions or amorphous conditions to the surface.
o	**Lithology**. Part of geology that studies rocks (physiological factors to these).
o	**Hydrogeology**. Part of geology that deals with the study of fresh water, and in particular underground, and its use. Factors that moisten the area.
o	**Weathering**. Also known as weathering, it is the physical and chemical alteration of rocky materials exposed to the “bad weather” (In the open sky, without a roof or any other repair.).
o	**Pending**. Incline, slope or slope of the terrain.
o	**Land use**. Human interventions that break the natural order of biodiversity, in this case of the surface (modifications or adaptations of the soil.).

That with the help of triggers (external that cause instability), it contributes to causing a landslide. Having the following:

•	**Precipitation**. Rains or water leaks that increase the humidity of the environment.
•	**Earthquakes**. Also known as an earthquake, it is a shaking of the earth's crust.
•	**Volcanic activity.** Any volcanic change that affects the risk zone (explosions that cause earthquakes, ash and gases that change the temperature, etc.).
•	**Human activity**. Soil overload, deforestation, cutting or extraction of land.

### DelimitationDelimitation
America is a continent very prone to having a landslide, taking data from the Center for Disease Control and Prevention (CDC), in the United States alone, these landslides cause between 25 and 50 deaths each year. One more precedent of the danger of these natural disasters in America informs us the United Nations (UN), warning that Latin America and the Caribbean are the second most prone to natural disasters in the world.
In this sense, since 2000, the Latin American region has had an average of 152 million people affected by natural disasters (which directly and indirectly cause landslides); Thus, since the 2000s there have been an approximate 3,000 deaths caused by 66 recorded landslides. Being one of the most recent, the Chiquihuite hill landslide, located in the conurbation municipality of Tlanepantla, Mexico. Reason why, there will be a greater research focus on this event.

### Proposed solutions

#### Using satellite visualization means
###### 1.- Probabilistic method for forecasting future landslides, use of WORLDVIEW and artificial intelligence.

**Azure Real Time Analytics on Big Data Architecture or Azure Stream Analytics** is used, where the data that **WORLDVIEW** gives us will be obtained, such as humidity, volcanic activity, temperature and those triggers of the area to be studied. All these data can be obtained through the **EARTHDATA SEARCH.**
An example of the case of Cerro Chiquihuite, a day before the landslide, the conditions and climatological factors were favorable to produce a landslide:
![1](https://user-images.githubusercontent.com/89156254/135971244-48c3c0b8-2662-4b48-b0e9-822ca86f0a15.png)

One day later, when the collapse occurs, the energy begins to dissipate after having been released.
![2](https://user-images.githubusercontent.com/89156254/135971437-8b5ea41b-acc9-4965-bfa2-9eb5e19fdb44.png)

This type of data is found in the EARTHDATA SEARCH, and with the help of Azure Real Time Analytics on Big Data Architecture or Azure Stream Analytics, we can perform an analysis of the data in real time. The parameters to search using the satellite medium are the following:
- Focus on landslide risk areas (NASA has a world map of risk)
- Relative humidity in the Area and rainfall
- Abrupt changes in temperature
- Wind speed
- Recent tremors or earthquakes

In this way, we can comply with the parameters that make the soil may have some cracking, and that this is the cause of a landslide.
- Low mechanical consistency subsoil (From the zoning of seismic wave velocity values).
- Water content in the subsoil (From geoelectric tomography and vertical electrical soundings).
- Existence of a firm layer or hard rock in the subsoil (From seismic exploration).
- nfiltration of water in the subsoil (From geohydrological analysis combined with firm layer surface).

#### Social conscience
###### 2.- Analytical method of hashtags, use of AI and data science, images and messages published on different social networks.
To date, social networks have a great impact as means of communication, by delimiting the project, we can say that in Mexico about 100 million people make use of social networks, we are talking about more than 70% of the population has the scope to implement information by this means.

 The method consists of reading the hashtags provided by any user in the selected applications of the network, for this the use of Azure logic Apps is proposed, a service that allows us to create this citizen awareness solution, to integrate it into an analysis of factors risks that may cause landslides.
 
So, we create the logic application and give it the design to obtain the data from the social networks to analyze; In this case, we have the option of Twitter (it will inform us when a new Tweet is sent), we start our session and configure the timing of the data collection. 

For this usage example, use the tag **# SCIENCE + COMMUNITIES**, to make the keyword trigger.

![3](https://user-images.githubusercontent.com/89156254/135972049-5613633c-14bb-4efd-a9dc-2dd5b5147599.png)![4](https://user-images.githubusercontent.com/89156254/135972050-d45eed72-46d2-43f9-8609-c8abc945e179.png)

We can create a similar algorithm for each of the most widely used social platforms (Twitter, Facebook, Instagram, TikTok, Reddit, ReadChan, etc.), some are included in Azure, and for the missing ones, an isolated code can be generated and added. to the logic App.
![7 1](https://user-images.githubusercontent.com/89156254/135972240-1a4fac9b-e7a1-4cd7-b2b1-f0a1d8f53797.png)              ![7 2](https://user-images.githubusercontent.com/89156254/135972242-6f1e5be4-f3d5-4cbb-8e97-20b5308bdb91.png)

 Subsequently, the **TextAnalitycs resource, part of Azure Cognitive Services**, is used in order to obtain the keywords that can influence the risk factors (location, rainfall, human influence activities, low-level landslides, among others). Taking into account that one of the main declining factors is rainfall with more than 80%, it is formulated to give higher priority to the area and rainfall. The Responsible AI Notice must be taken into account.
![5](https://user-images.githubusercontent.com/89156254/135972051-5bda5b5d-6b8c-4225-a915-3a0b27768450.png)![6](https://user-images.githubusercontent.com/89156254/135972239-a40b2a07-3cc5-4120-9741-7ad27d892799.png)

The implementation of a method of reliability and reliability of the users is proposed, where all the information collected is directed towards a web page (Use of Azure for the Wordpress host). In this sense, there will be a section with the contribution, in this way we create a bond OF TEAM SPIRIT with all those involved.
![7](https://user-images.githubusercontent.com/89156254/135972364-7deae155-c160-4716-9367-9eb3bdcb818e.png)

In this way, we will obtain the data on the website in Wordpres, which will give the project reliability, and we will also have a database with the following information: 

![8](https://user-images.githubusercontent.com/89156254/135972366-bcad88a9-3b0b-4c05-8f08-7c742e9833b7.png)

Once the data has been obtained in an Excel, the data will continue to be uploaded to an **Azure SQL Database**, where the steps to follow can be found in the following link on the Azure page:  https://docs.microsoft.com/es-es/azure/azure-sql/database/connect-excel

Then, a predictive machine learning model will be created, where we will use the **Azure Machine Learning Designer** tool. You can follow the following example tutorial to carry out the realization of 

#### Conjunción de los métodos pasados para el análisis de ImágenesConjunción de los métodos pasados para el análisis de Imágenes

###### 3.- Implementation of spatial images and provided by the community (either by the aforementioned method of hashtags, or a direct image collection method). Using artificial intelligence, with the help of Azure Computer Vision and Azure Cognitive Services, high-quality AI can be entered as an API; Thus we can analyze the content of images and videos found in the collection.

In our project we use the following example factors (visuals), which can be detected by the images that are supplied by conscious users.

- Discontinuities
-  Factors that promote humidity
- Inclination
- Land use
- Landslide

We will initially use **Azure Cognitive Services to train AI** and identify the most important aspects to take into account for the analysis; for this, we start with the creation of a new project:
![9](https://user-images.githubusercontent.com/89156254/135972368-f041f294-d45b-4e2e-9bfc-23abd4ee9894.png)

We generate a new resource and specify the use of **Cognitive Services** for object detection, in a general way.
![10](https://user-images.githubusercontent.com/89156254/135972369-b3a88046-9095-45bb-9510-c317c25800ec.png)![11](https://user-images.githubusercontent.com/89156254/135972371-91fe47d3-9efc-4a01-944a-099751def93f.png)

We begin to implement the Tags and specify them within images that are related to the objects to study (risk factors).
![121](https://user-images.githubusercontent.com/89156254/135973209-6058cc48-3019-453b-90a7-fea2090e03c8.png)

Finally we let the AI train to wait for the results, in this example the **quick training** option was used, a set of** 40 initial images**, which were entered directly into the application, but which can easily come from a collection cloud as indicated in a start. After a 5-minute workout, they obtained the following results:
![14](https://user-images.githubusercontent.com/89156254/135973257-28b9c41a-ddd0-4b88-b9c1-07876d8282a9.png)![15](https://user-images.githubusercontent.com/89156254/135973261-9010135a-bb40-4076-b13b-74719f0bcdbb.png)
We observe an efficiency of approximately 40%, being a first attempt it is something quite high. The use of our labels has an average precision of 42.24%, noting that an analysis of many images or in contrast to very few, brings deficiencies. The middle term being the one indicated, so they are **features to improve** in terms of identifying the factors manually.

Carrying out a quick test examination, observing that there is recognition and identification of the indicated objects, even when a very basic analysis was made (few images, little time):
![16](https://user-images.githubusercontent.com/89156254/135973262-1a1415cf-4784-452d-a034-b03ebf5734c1.png)![17](https://user-images.githubusercontent.com/89156254/135973264-02da76ee-84e6-40be-8611-d6f76a060070.png)![18](https://user-images.githubusercontent.com/89156254/135973266-81899664-a5c0-48a8-899a-762327fde246.png)![19](https://user-images.githubusercontent.com/89156254/135973267-d23e6a94-552d-4c75-8524-ca5721ed1579.png)

### Ending result
Once the different aforementioned analyzes have been obtained, a final evaluation and a verification filter of the data obtained in each of the analyzes will be carried out. Correlation and verification of the data sent through the coherence of the data obtained by the mapping and the comments of the people, as well as the analysis of the images.

Taking into account that there may be errors in some process, it is proposed to expose the results on a web page, where finally the predictive sum is performed manually (through human work) and the use again of machine learning algorithms, being able to use Azure Machine Learning to give a forecast of the total sum of each of the proposed solutions.
Following the data analysis diagram:
![20](https://user-images.githubusercontent.com/89156254/135973535-32860247-bf2e-419c-953a-f2df5237958c.png)

### Expansion and Diversification of solutions

With the passage of time, the effectiveness will increase, as well as the scalability and opportunities to extrapolate resources to new spaces of experimentation, increasing the scope of timely help predicting natural landslide disasters, preceding them and relocating the living beings that they may be exposed or in danger.

A step beyond the project would be the creation of an application and emergency alarms with location, which inform residents of a possible eminent landslide, in this way greater autonomy is given to the individual, in what institutional instances are programmed for support.
### Conclusion
	
Undoubtedly, technology opens the doors for the implementation of new solutions, but it is a matter of the human being to be able to use them in the best possible way, as long as artificial intelligence does not take the domain of consciousness that humans show, it is our responsibility In charge of guiding the course of our future, software and conscience feed intelligence.

### ReferenciasReferencias 
 	National Aeronautics and Space Administration (-), Landslide Reporter, Translation: Patricia Williams, Revision: María José Viñas García, NASA.
[Web PDF retrieved 10/03/2021]
https://gpm.nasa.gov/landslides/guides/LandslideReporter_Intro_Spanish.pdf

 	United Nations Organization (2000), Office for Outer Space Affairs UN-SPIDER Knowledge Portal: Data Application of the Month: Landslides, UN.
[Retrieved via the web on 10/03/2021]
 https://www.un-spider.org/es/enlaces-y-recursos/fuentos-de-datos/daotm-deslizamientos-tierra

 	National Coordination of Civil Protection (2016), Course: Causes that promote landslides and prevention measures, Mexico, CENAPRED - SEGOB.
[PDF web retrieved on 10/03/2021]
http://www.cenapred.gob.mx/es/documentosWeb/Enaproc/IdentiDeslizamientos.pdf

 	Centers for Disease Control and Prevention (2018), Natural Disasters and Severe Weather: Landslides and Mud Avalanches, CDC.
[Retrieved via web on 10/03/2021]
 https://www.cdc.gov/es/disasters/landslides.html

 	United Nations Mexico (2020), Latin America and the Caribbean: the second region most prone to natural disasters, News, Mexico.
[Retrieved via web on 10/03/2021]
https://www.onu.org.mx/america-latina-y-el-caribe-la-segunda-region-mas-propensa-a-los-desastres-naturales/

 	National Polytechnic Institute (2017), Cracking, SEGOB, IPN.
[Retrieved via web on 10/03/2021]
https://www.esiatic.ipn.mx/geofenomenos/agrietamientos/agrietamientos.html

 	José Jesús Guzmán Eusebio (2021), Internship: Course on Artificial Intelligence and use of Azure, Virtual Innovation, Microsoft Azure.
 	ROYAL ACADEMIA ESPAÑOLA: Dictionary of the Spanish language, 23rd ed., [Version 23.4 online]. <https://dle.rae.es> [02-03 / 102021].
	
###### 30 second video for NASA
https://user-images.githubusercontent.com/89156254/135974233-409f5a71-cb70-4efb-a62d-d28f6ebfd452.mp4

###### SPACE APPS CHALLENGE AND AZURESPACE APPS CHALLENGE AND AZURE
https://user-images.githubusercontent.com/89156254/135974345-22834e91-247a-4405-8b39-574d20063ad1.mp4

###### SPACE APPS CHALLENGE AND AZURESPACE APPS CHALLENGE AND AZURE EXTENDED SPEECH (SPANISH) VIDEO VERSION
https://user-images.githubusercontent.com/89156254/135974357-3d0e4571-fed7-4778-b230-d69499f7f586.mp4
	
#### About me
###### 20-year-old Mexican student, Mechatronics Engineering at IPN
###### Preparing in VIRTUAL INOVACTION for the Exam AZ-900: Microsoft Azure Fundamentals (Course focus on AI)
![7](https://user-images.githubusercontent.com/89156254/135973777-97f6eff0-a67c-454b-b335-19b0cb61dbac.png)

<p align="center">
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
</p>
