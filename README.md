# MRT Net Flow Analysis
Visualize the movement of MRT users throughout a week.</br>
The source data in this project is from MRT hourly data as explained at [_MRT_Cleaning_Visualizing_](https://github.com/ShihWen/MRT_Cleaning_Visualizing).


You can also read the related article on my Medium:
</br>
[Part 1 Explain how the city is divied](https://medium.com/@shihwenwutw/%E7%94%A8%E6%8D%B7%E9%81%8B%E8%B3%87%E6%96%99%E8%A7%80%E5%AF%9F%E4%B9%98%E5%AE%A2%E7%9A%84%E7%A7%BB%E5%8B%95%E8%BB%8C%E8%B7%A1-%E4%B8%8A-579901ca828a)
</br>
[Part 2 Visualization and analysis](https://medium.com/@shihwenwutw/%E7%94%A8%E6%8D%B7%E9%81%8B%E8%B3%87%E6%96%99%E8%A7%80%E5%AF%9F%E4%B9%98%E5%AE%A2%E7%9A%84%E7%A7%BB%E5%8B%95%E8%BB%8C%E8%B7%A1-%E4%B8%8B-22d70ea76ddb)


Steps:
1. Calculate the annual average people groupped by od, day of week and hour.
2. Sum up the result based on the map generated using Voronoi diagram.
3. Visualize as bar graph and map.
<img src="https://github.com/ShihWen/MRT_Net_Flow/blob/master/image/process_flow.png" height="300" />


Types of data:

|Raw Data|Flow by OD|Flow by Dist/Station.|
| :-------------: |:-------------:| :-----:|
|![](https://github.com/ShihWen/MRT_Cleaning_Visualizing/blob/master/images/1_raw_data.png)|![](https://github.com/ShihWen/MRT_Net_Flow/blob/master/image/flow_by_od.png)|![](https://github.com/ShihWen/MRT_Net_Flow/blob/master/image/net_flow.png)|


Present the result:


|8 a.m. on Thursday|6 p.m. on Thursday|
| :-------------: |:-------------:|
| ![](https://github.com/ShihWen/MRT_Net_Flow/blob/master/flow_graph/map_3_8.png)|![](https://github.com/ShihWen/MRT_Net_Flow/blob/master/flow_graph/map_3_18.png)|


|Top 10 Move-in Station at 8 a.m. |Top 10 Move-Out Station at 8 a.m.|
| :-------------: |:-------------:|
|![](https://github.com/ShihWen/MRT_Net_Flow/blob/master/image/Top_10_8:00.png)|![](https://github.com/ShihWen/MRT_Net_Flow/blob/master/image/Bottom_10_8:00.png)|

|Top 10 Move-in Station at 6 p.m. |Top 10 Move-Out Station at 6 p.m.|
| :-------------: |:-------------:|
|![](https://github.com/ShihWen/MRT_Net_Flow/blob/master/image/Top_10_18:00.png)|![](https://github.com/ShihWen/MRT_Net_Flow/blob/master/image/Bottom_10_18:00.png)|
