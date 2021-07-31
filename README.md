# Blue Waters
- *Website*: [click to view](https://bluewaters.s3.eu-de.cloud-object-storage.appdomain.cloud/index.html)
- *Dashboard*: [click to view](https://bluewaterss.eu-gb.mybluemix.net/ui/)

## What is Blue Waters

BlueWaters is a Node Red Application that will provide user(community users, water analysts) with insights and information on monitoring water sources.
Our water sources lack basic protections
from such, this vulnerability renders them susceptible to pollution and contamination.
Improvement of water quality is a pivotal part of the UN Sustainable Development Goals (SGDs),
data collection and sharing has been centred as an important step for reaching water quality targets.
Access to reliable water quality data is critical for increased understanding of water issues and for
developing efficient management strategies of major water sources in Botswana. To support
scientific progression in Botswana and an efficient hub for systematic data collection, utilization
& monitoring of water quality in major water sources (dams & rivers) is very pivotal as such
monitoring systems need to be adopted that will give timely and up to date information regarding
water sources in Botswana.

## Contents
1. [How We Identified the problem](https://github.com/Tlotlo-pat/bluewaters/blob/main/README.md#how-we-identified-the-problem)
2. [Short Description](https://github.com/Tlotlo-pat/bluewaters/blob/main/README.md#short-description)
3. [Demo Video](https://github.com/Tlotlo-pat/bluewaters/blob/main/README.md#demo-video)
4. [How it Works](https://github.com/Tlotlo-pat/bluewaters/blob/main/README.md#how-it-works)
5. [Roadmap](https://github.com/Tlotlo-pat/bluewaters/blob/main/README.md#roadmap)
6. [IBM Cloud Services](https://github.com/Tlotlo-pat/bluewaters/blob/main/README.md#ibm-cloud-services)
7. [Authors](https://github.com/Tlotlo-pat/bluewaters/blob/main/README.md#authors)

## How We Identified the Problem
![design](https://user-images.githubusercontent.com/51744364/127749932-1a4e9fcd-e6a8-4f29-bff9-bff3543cbf95.jpg)

Through design thinking process , we were able to brainstorm and come up with different ideas to tackle climate change
in Clean Water and Sanitation Category. The screenshot above shows some of the ideas we had to fight climate change using cutting ede
technology.
Information sharing and or Monitoring of our climate is a factor that may help in creating a better world for the future generations to come.
We decided to work on a solution to build a platform where information about our water sources will be shared and analysed.
Much of the emphasis in water resource management has revolved around ensuring that users
should have not only enough water but desirable water quality too. The issue of water quality can
play a dominant role when the available water gets scarce and scarce. Water availability is only as
good as the quality of that water. Therefore, both quantity and quality need to be considered in
detail and they can no longer be managed in isolation of each other. 
 
## Short Description
### The Problem
Dirty water is the world’s biggest health risk. Water that flows into rivers picks up toxic chemicals,
dirt, trash and disease carrying organisms along the way. Our water sources lack basic protections
from such, this vulnerability renders them susceptible to pollution and contamination. 
Also, strengthening water security is essential for preventing and combatting covid-19 as the
world is facing this pandemic. Measures to suppress the Covid-19 pandemic, including handwashing, self-isolating and lockdowns assume that societies, communities and households have
sustainable access to acceptable amounts of adequate quality water. However, across rural areas
in Botswana, water insecurity is increasing, with the poorest and most vulnerable particularly at
risk. As the Covid-19 pandemic is still unfolding, it is not clear what the impact on developing
countries or their water security will be. Consequently, there is a need to monitor how the pandemic
unfolds and assimilate lessons learned. Therefore by measuring the toxicity of water in dams would
ensure that quality water reaches appropriate stakeholders for use to tackle covid-19 also for
healthy living as water is used on different needs of our daily lives.

*Learn more about the problem*:[Our Story](https://l.facebook.com/l.php?u=https%3A%2F%2Fstorymaps.arcgis.com%2Fstories%2Ff0752b39d7074adba1351b51dfbe713a%3Ffbclid%3DIwAR0H-9MmwnMYXnBxZ2V4Pf5JDACoCTZKqJ72tlOMAshqJNsrO2tl95KP2II&h=AT1rxklmTwShkDPLo9L0KrX2RLvkLZceV57HJpZYi3xmKN5Q3rBv3UIMiaHCGV9ZB05raLktANHv8jDfzlxUU467MUAcWw-1IWoyYssaWbAZNXy72ZCb5yq1A4QpnysGjmQY85Kf-bLuwO8)

### How technology can help
- Provide water quality reports of our dams
- Weather monitoring
- Idfentifying health risks brought by contaminants that may be found on water
- Providing information through real time chat about water related issues  including waste water management.

Since ecosystems can function at various levels of integrity and the need to protect water
ecosystems, this makes room for the need to develop a monitoring system that influences decision
making in respect to water resources.
The application is built using Node Red, an IBM cloud service and The Weather Company
technologies, the platform will provide water quality of streams or rivers that flow into Botswana
Dams, also the platform provides a solution to tackle climate change by ensuring that we aware
of the quality of water in our dams to understand the risks that may be brought by the water
toxins found on our rivers. The toxins may affect the lives of humans and aquatic plants and
animals. Weather forecast is featured in the platform, since temperature is one of the factors
contributing to water quality it is imperative to forecast temperatures daily or weekly.

### Innovation
![innovation](https://user-images.githubusercontent.com/51744364/127751944-38222250-b7bc-451e-b8c4-c151bc635fee.jpg)
The dasboard will provide water quality in dams and rivers, a map will show the dam or river accessed.The report will provide insights on toxins that may be found in water and take relevant decisions wether is safe for drinking.Also identify health risks associated with contaminants found in water, this will help in ensuring diseases 
affecting a group of people in that particular region are identified and treated well in time.

## Demo Video
[![video](https://user-images.githubusercontent.com/51744364/127750135-4020be23-c750-44f7-a29e-72894979c0a3.PNG)](https://www.youtube.com/watch?v=_2jatHHtkWI)

## How it Works
![blue waters architecture (2)](https://user-images.githubusercontent.com/51744364/127750268-e8c30b46-67ca-45fa-b376-68d519362fd7.png)
1. The website will be available online to provide information about Water management. [*View Website*](https://bluewaters.s3.eu-de.cloud-object-storage.appdomain.cloud/index.html)
2. Web chat will provide assistant to users about questions and queries about water management .
3. Water ana;ysts will be able to access the dashboard online. Which consists of 4 components; maps,dam level info, water quality insights and weather forecasts.
4. The Esri map is connected with arcgis map api.
5. The dam capacity information is stored in IBM Cloudant and displayed on the dashboard.
6. The water quality api is integrated  with the dashboard to provide water quality reports of dams and rivers.
7. Weather forecasts will provide forecasts for the user, The Weather Company API are integrated with the dashboard.
8. The Web chat is liased with IBM Watson assistant to provide users with efficient user experience by providing answers regarding Clean Water, Water managemnet, Waster water.

*Dashboard*:[Click to view](https://bluewaterss.eu-gb.mybluemix.net/ui/)

## Roadmap
![Roadmap](https://user-images.githubusercontent.com/51744364/127750236-c7868e19-88f4-41d3-b6df-7e25cd3e9d93.PNG)

 
## IBM Cloud Services
1. Node Red
2. IBM Cloudant
3. IBM Watson
4. The Weather Company

## Authors
- Tlotlo Patriot Kgotlafela; Software Developer [*See Linkedin*](https://www.linkedin.com/in/tlotlopkgotlafela/)
- Pako Daniel Moatshe; Project Management [*See Linkedin*](https://www.linkedin.com/in/pako-moatshe-94b93216a/)
- Kago Vincent Tshotlane; Web Developer [*See Linkedin*](https://www.linkedin.com/in/kago-vincent-tshotlane-943b89218/)
