# Final Project 
> ## Description 
> In this project we are monitoring a bustling intersection with two roads one being a highway and the other a country road . There are three sensors that are used to control two traffic lights which only have two options : green light for 'GO' and red light for 'STOP'. The first sensor is a counting sensor that counts the amount of cars passing by in either direction , second is a weather sensor that detects whether it's snowing or not and last a sensor enable . Having my inputs being the the two sensors and two lights and the output being how many cars have passed to change the lights .
> Since the highway is typically going to be busier then the country road for every  8 cars on the highway the passes by the lights will change and for every 4 cars that pass on the country road the light will change  . When the weather sensor changes the counting sensor will cease until it stops snowing .
>
>##  State Diagram 
> 
> ## Summary
> Some considerations i took into account while implementing my state diagram was having 4 bits that can be either 1 or 0.  And building around that idea to construct and system that can manage the flow of traffic and take into account the difference between a country road and a highway . I chose to use that states as cars to find a way to keep track the amount of cars going through each road and having the counter being the main driving force between each and every state . Other states were labeled as the delay to signify both traffic lights turning red to avoid any accidents before changing either light to green or entering another section of the diagram .Snowing was another state that ceased counting and kept track of the counter before it was disabled .
