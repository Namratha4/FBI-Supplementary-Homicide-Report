# FBI-Supplementary-Homicide-Report
# Dashboard 1:

![image](https://user-images.githubusercontent.com/61535156/149589532-af4bc61f-5017-4d69-8d30-6beb280c7bd5.png)


# Dashboard 2: Trend over 30 years (1980-2014):

![image](https://user-images.githubusercontent.com/61535156/149589561-e160ee5e-8b86-41ae-b685-4fde8b3385fc.png)


# Visualization 1:Bar Graph Side-by-Side for agencies with highest % of crimes solved

The purpose of this graph is to visualize crimes solved by various agencies based on the weapons used for committing the crime. The end-user of this visualization can be the government agency that has the responsibility to allocate crimes to an agency. After knowing which weapon was used to commit the crime in a particular region, they can see different agencies and their percentage of successful crimes solved. With this data, they can assign the criminal case to the agency which has the highest crime solve ratio in that region and for that particular weapon.

![image](https://user-images.githubusercontent.com/61535156/149589680-1136bc80-ec33-4a11-9f9a-e028f4f9e640.png)

For example- When they know the crime is committed by the use of a shotgun and it took place in the Midwest Region of the United States. They would be able to filter accordingly and then observe that Tribal Police has the highest crime-solving success rate when shotgun crimes are handed over to them in the Midwest region. The government agencies can also see the average percentage of crimes solved for a particular region and a particular weapon.
By doing so, they will be able to increase the crime-solving percentage of each region over the years, as they would be repeatedly handing over the crimes to agencies who have a high crime-solving rate. 

# Visualization 2: Bullet Graph for Perpetrator Age Vs Victims Age

The purpose of this visualization is to find out the relationship between the perpetrator's age and the victim's age based on their gender and race. After creating few calculated fields we calculate the average age of perpetrators and group them according to different age groups (teens 9-18, Young adults 18-35, adults- 35-60, senior 60-100 years). Based on these perpetrators' age groups the length of bars in the chart represent the average age of groups from a particular race of a particular gender and the black line represents an average of victims age killed by that category of the perpetrator. Through this, we can observe if an age group of a race and gender commits a crime on people younger or older to them.

![image](https://user-images.githubusercontent.com/61535156/149589738-f4c3b09c-6b64-48b3-a208-e3b3c5ce1e84.png)

For example, we can observe that in general criminals who are teens tend to commit crimes on people who are way older than them, whereas young adult and adult age group criminals tend to kill people similar to their age group, and senior-aged criminals usually commit crimes on young people. Through this we can also observe trends by gender and race, for instance, we can see that all age groups of Asian females criminals commit crimes on people younger than them. Taking another example, we can see that senior male  American criminals tend to commit a crime on much younger citizens (with an average age difference of 16 years between perpetrator and victim).

# Visualization 3: Bubble Chart for relationship between Victim & Perpetrator
The purpose of this visualization is to analyze the types of weapons used by the perpetrator and their relationship with the victim. For this visualization, we will use a bubble chart, where the number of crimes done is calculated by counting the record ids. This quantitative value is depicted using the size of the bubble. The colors of the bubble are used to distinguish between the weapons of choice which is a qualitative attribute.

![image](https://user-images.githubusercontent.com/61535156/149589841-1e1c4904-dc53-403d-821f-0b930d037100.png)

We have used filters for both weapon and relationship. This visualization can be used by agencies to find the prime suspects in a case. The bigger the size of the bubble the more chances the prime suspect should be interrogated. For example in above chart, for drugs as weapon, Aquaintances has more number of records so the prime suspect should be acquaintances of victim. And second prime suspect should be Friends of victim. Also for analysis purpose we can select all weapons and single relationship to see how victims relations are committing crimes using different weapons.

# Visualization 4: Line graph for top 10 states with more crimes
The purpose of this visualization is to analyze top 10 states with more number of crimes over the years from 1976 to 2014. In this we have used years attribute in filters to make it a animated dashboard.  

![image](https://user-images.githubusercontent.com/61535156/149589873-daf4a293-62b6-4634-a45b-bf38f2f8c2ca.png)
 
In the above figure, we can see that California in the west region has highest number of crimes and ranks one among top 10. Lets see if we can infer anything why these states are in top ten. Aggregate percentage of crimes solved over the years for top ten states with most number of crimes is shown below.

![image](https://user-images.githubusercontent.com/61535156/149589906-b3a4366c-63c3-4d9a-a3d6-be3dbc6223ad.png)

We can see that there’s downtrend in number of crimes being solved by 2014. This can be a major reason why crimes are increasing in these states. Since cases are not being solved criminals are not scared to commit a crime resulting in the increase in total number of crimes.

![image](https://user-images.githubusercontent.com/61535156/149589940-ac1a848d-06a9-4059-8fdf-70477bb81bb8.png)

# Visualization 5: Line graph for bottom 10 states with more crimes
The purpose of this visualization is to analyze bottom 10 states in united staes with more number of crimes over the years from 1976 to 2014. In this we have used years attribute in filters to make it a animated dashboard.  

![image](https://user-images.githubusercontent.com/61535156/149589976-96528de2-1aea-4255-8c64-eeaef9142804.png)

In the above figure, we can see that Vermont in the NorthEast region has least number of crimes and ranks one among bottom 10. Lets see if we can infer anything why these states are in bottom ten. Aggregate percentage of crimes solved over the years for bottom ten states with least number of crimes is shown below.

![image](https://user-images.githubusercontent.com/61535156/149590015-b1926a2e-e75d-4147-b2c8-71f33609180c.png)

We can see that there’s uptrend in number of crimes being solved by 2014. This can be a major reason why crimes are decreasing in these states. Since cases are being solved with high accuracy criminals are scared to commit a crime resulting in the decrease in total number of crimes.
