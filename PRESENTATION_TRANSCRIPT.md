# EXPLORE AND VISUALIZE YELP

## Cover Slide (Slide 1)

- Project title: Explore And Visualize Yelp
- Group name: Jings'
- Team names: 

| Name | USC username | email |
| ------------- | ----------- | ----------- |
| Jing Ouyang | jingo | jingo@usc.edu |
| Jing Zhou | zhou510 | zhou510@usc.edu |
| Tong Wu | twu665 | twu665@usc.edu |

## About (Slide 2)

- Explore and visualize Yelp restaurant dataset
- Who: Those interested in the food culture in different cities
- Why: Stories and features for each city based on its restaurants data

## Who Did What (Slide 3)

| Name | Coding |
| ------------- | ----------- |
| Jing Ouyang | Charts, Maps, Stories |
| Jing Zhou | Coxcomb, Layout, Styles |
| Tong Wu | Light Map, Integration, Test |

## Data and Topic Needed (Slide 4)

- Basic concepts about the cities in the U.S. and Canada
- Basic understanding of Yelp

## Research (Slide 5)

- Other kernels in Kaggle using the same dataset

## Why Original (Slide 6)

### Others did not:

- focus on restaurants
- focus on specific cities
- arrange and tell the story in a sensible way

## Story (Slide 7)

- To dig out the features behind the restaurants data for each city
- To build a character upon the features

## Choice of Forms (Slide 8)

- Features of city --> The unique points --> Bar chart/Stacked bar chart
- Story of cuisine --> Rating and counts of cuisines --> Coxcomb chart
- Busy time of city --> Restaurants open and closing time --> Light map

## Design Process (Slide 9)

- Choosing a Bootstrap template layout
- Creating maps, charts, graphs and contexts and fit into the layout
- Modify and adjusting the layout and style
- Use specific tools(Arc map) to create light maps

## What We Built1 (Slide 10)

### Overview Page

- project information and introduction
- Entry of city stories
- ABOUT

## What We Built2 (Slide 11)

### For Each City:

- City character (text)
- Bar chart/Stacked bar chart (d3 bar chart, python)
- Dot map with all restaurants in the city (d3 map, d3 transitions: zoom in & out)

## What We Built3 (Slide 12)

### For Each City:

- Coxcomb chart to show cuisine/counts/rating (d3 coxcomb chart, d3 transitions, d3 stack layout)
- Light map (ArcGIS)
- Beautiful layout with Bootstrap!

## User Interaction (Slide 13)

- City choice on the main page
- Zoom in and out on the map for interested restaurant
- Hover on dot to view restaurant detail
- Choice of cuisine on coxcomb chart

## Others (Slide 14)

- ALL the element are responsive and phone-friendly
- The project was completed by angular.js
- Used Git to increment changes

## Details1 (Slide 15)

- The charts and maps are drawn by calling encapsulated functions
- The size of dots on the city map would respond to the extent of zoom in & out

## Details2 (Slide 16)

- The coxcomb chart axis would zoom in & out if the change of data range is not too small or too big, and would be redrawn otherwise
- Have to choose at least two cuisine types to draw the coxcomb chart

## Could Have Done Better (Slide 17)

- The dot maps of Madison and Charlotte are missing because didn't find geojson
- Some cities have only 1 feature
- We found more insights, but have limited time to visualize