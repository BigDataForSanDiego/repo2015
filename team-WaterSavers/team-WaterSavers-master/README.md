![alt tag](https://github.com/BigDataForSanDiego/team-WaterSavers/blob/master/banner.jpg)
# team-Water Savers

## Presentation:
https://docs.google.com/presentation/d/1FT-aMhEsqp1w7CufP-LSdlwNqMz5kDXmFFV_4VepCuU/edit#slide=id.p

## Team Members :

Utsav Parikh
Arpit Satia
Rutvij Kothari
Nirav Nayani
Tyler Rogers
Sol Manuel Garza

## Inspiration :

We are passionate about California's drought and it's implications on citizens. The new water restrictions have made many residents aware that they may have to change their water consumption, especially because there are fines involved. However, many residents do not know if they are using too much water or what they should do to conserve. In our app we want to give people a clear sense of how much water they are using relative to other users and and what they should be doing to conserve.

## What it does :

This is a mobile app that meant to educate San Diego County residents about how to conserve water and understand why conserving water is essential to our quality of life. The app asks the user a number of questions about how much water they consume and then ranks them relative to other residents in the county. Based on the users inputs, the app also generates a short list of water saving tips.

User-Supplied Data -- Questions that the user will answer in order (user inputs):

Location (zipped or auto-generated by app)
How many people live in your house? (this should be used to generate flushes, meals, showers)
How many showers do members of your household take each day? How long are your showers?
Do you have a low-flow shower head?
Do you have a lawn? How big is your lawn?
Do you use a dishwasher, a washer and a drier? If so, how often do you use them? -----This will generate the Per Capita current water usage of the user.

Comparison Data:

Per Capita Water Use Data for California: http://waterdata.usgs.gov/ca/nwis/wu (used to create the comparison)
Per Capita Water use in San Diego. Source Equinox Project /San Diego Regional Water Authority : http://www.equinoxcenter.org/regional-dashboard/interactive-dashboard/water-consumption.html (used to create the comparison)
Information on lawn requirements. Taken from railbird website. This will generate an estimate of water used on a lawn.
Information on appliances: How much water do the appliances use? These will be estimates based on when the appliances were made.
Shower Output (Older Showers v. Low-flow shower heads). Estimates based on when shower heads were installed. -------This comparison data will be compared to the user's per capita usage to generate a score.
Outputs:

Water usage compared with other people in the same area. How much water can be saved by making changes (landscape/lifestyle changes). Strategies for saving water.

## How I built it :

We are planning on using hybrid app development frameworks and arcGIS.


## Challenges I ran into :

No APIs available, so we had to reformat data. Our original idea needed to be paired down based on what data was available.


## Accomplishments that I'm proud of :

Finding sources with relevant water data. There was a lot of broad water data that was not relevant to our app. Additionally, It was good to come up with a flow for the user interface that was simple and provided us with enough data to give an accurate ranking.

## What I learned :

Sources of water use data are very disparate.

## What's next for Water Savers :

We think think this could be used to suggest alternate landscaping options and/or appliances.

## Built With :

* iOS Framework (iOS 9)
* XCode
* RESTFul APIs

