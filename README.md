# Business_Location_Prediction
Using a clustering ML algorithm to predict the best neighbourhoods for a new business investment. 

![image](https://user-images.githubusercontent.com/105684729/187290588-78e748dc-0883-4620-8113-f15e3aa48eaa.png)


## OPTIMAL AREA FOR A NEW GYM BUSINESS 
### Project Introduction
### Business Problem - 
An enterpreneur would like to launch a gym in central Toronto, Canada. S/he is not sure which neihgborhoods are profitable for this type of business. 
The solution requires several types of data about neighborhood. It would be easier to decide if the investor knew the percentage of population that falls within their target audience, crime rates, total population, competition level, income level of the neighborhoods. However even then it would be hard to compare the neighborhoods since there are more than 100 different neighborhoods. Therefore the investor needs an agency to make calculations for them.

### Purpose- 
This project aims to give a list of district names in Toronto, Canada. The list shall be composed of the neighborhoods that hold the highest business opportunities for an enterpreneur who would like to start a gym business. 

### Structure- 
The project is divided into different parts due to its length and each part is segmented by subtitles to increase the readability.

### Roadmap -
- Collect information about the different aspects of districts

![image](https://user-images.githubusercontent.com/105684729/187066378-d1e2eebf-7034-47ed-80f6-cdadaf986d24.png)



- Clean, process and merge the tables coming from different sources.

![image](https://user-images.githubusercontent.com/105684729/187152488-09053451-9678-4b3f-bc38-67b2f8972db8.png)


- Optimize the data and supply it to the machine learning model.
![image](https://user-images.githubusercontent.com/105684729/187066417-2180747a-c781-458d-ac81-01b83ff1337c.png)

- Visualize the results 


[![image](https://user-images.githubusercontent.com/105684729/187288823-b5bc2b15-253b-45d4-bb1e-fffc2a0fa1aa.png)](https://public.tableau.com/views/Book1_16617773505490/Story1?:language=en-GB&:display_count=n&:origin=viz_share_link)

[**Tabelau Link for dashboards**](https://public.tableau.com/views/Book1_16617773505490/Story1?:language=en-GB&:display_count=n&:origin=viz_share_link)


### Required Data list :
- Income per neighborhood *
- % of the target audience *
- Population *
- Number of gyms*
- Number/size of green parks *
- Crime rate

In case you would like to get the data quickly, I attached the data collected from APIs.


### Disclaimer - 
Most of the data is outdated, it is risky to take new decisions according to the results of this work. However, the important things is the implementation and logic,  the same process can be applied once access to fresh data is achieved.

## References
- [financesonline.com](financesonline.com) - I used the insights provided in this website to make decisions in regards to the data collection. I was able to create a list for the required data only with the information gathered from this website. The website gave me a good understanding about the features of gym subscribers by giving statistical data.

- [Medium Post](https://medium.com/mlearning-ai/end-to-end-data-science-project-beginner-version-part-1-96e59bdfbc5b) My work is originated from this medium post. I was fascinated by the idea and I wanted to do a similar project. Thanks to the author of this post, I learned a lot through this project.

- [open.toronto.ca](open.toronto.ca) - This database offers APIs and static data in the form of xls,xslx,csv etc. Most of the data is pulled from this database. It includes guides for developers as well. I used this API to collect demographic information like income level and age; also for geographical information like neighborhood coordination data and infrastructure locations.

- [developer.foursquare.com](developer.foursquare.com) - Foursquare has an amazing API infrastructure. The guides are clear and concise. The interface is very user friendly and easy-to-understand. The data quality of free account is satisfying for personal use. This API is used to collect data about locations of gyms in specific areas and other specifications like rating and popularity.



