<h1>Air Quality in the city of Bogota</h1>
<b>In this project I will show the design and implimantation process of air quality analysis for city of Bogota. Before this step I have completed the explore phase which includes the problem we are trying to solve, the engagment of stakeholders, and if AI adds value in solving this problem. In this case, our problem definition could be something like public health professionals working with the city of Bogota need to be able to provide real-time estimates of air quality throughout the city so that citizens can be aware of any health risks due to poor air quality and plan their outdoor activities accordingly. Stakeholders are city officials, citizens and health care professionals. Air pollution can come from many different sources and indeed, there are both man-made and natural sources of air pollution. And these include what's called particulate matter which just means really tiny bits of stuff often only a few microns in size as well as other things like ozone, lead, and oxides of nitrogen, sulfur, and carbon. Among all of these pollutants, the most common and the one that causes the most deaths globally is particulate matter. Specifically, particulate matter that is less than 2.5 microns in diameter, or PM 2.5 for short. the Data used has been collected by Bogota Air Quality Monitering Network(RMCAB) in 2021. They deployed scientific grade Sensors in 20 different strategic locations in the city, monitoring different types of pollutants including PM 2.5.The sensors transmitted reliable data, data normalization, visualization, correlation done.</b>
  <h2>Design and Implementation process</h2>
  
  
- <b>Import Python packages</b>
<b>I will use specific utility functions written for this project</b>
<img width="695" alt="image" src="https://github.com/user-attachments/assets/06a6f3fa-f50f-42f5-b9af-0dee6448a71b">

- <b>Load the dataset with missing values filled in</b>
<img width="729" alt="image" src="https://github.com/user-attachments/assets/15ec9d57-0218-4d12-af59-32cbe4d91e2e">

- <b>Use the nearest neighbor method to make a map of PM2.5 in Bogotá</b>
 <b>I used the nearest neighbor method to estimate the values of pollutants at the points between the stations, so I can create a nice visual map of pollution.</b>
 <img width="721" alt="image" src="https://github.com/user-attachments/assets/49360cde-f80d-46e1-a2e1-58fed1530076">

 <img width="683" alt="image" src="https://github.com/user-attachments/assets/ea174ce4-cb7e-46a3-acde-1dd3a4763417">

- <b>Test different values of k for the nearest neighbor method</b>
- <b>Use the best value of k to make a map of PM2.5 in Bogotá</b>
- <b>Construct a map animation of PM2.5 in Bogotá</b>
- <b>Display your map animation# City-Air-Quality</b>
