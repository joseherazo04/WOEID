# WOEID

## Description

A WOEID (Where On Earth IDentifier) is a unique 32-bit reference identifier, originally defined by GeoPlanet and now assigned by Yahoo!, that identifies any feature on Earth. (from [Wikipedia](https://en.wikipedia.org/wiki/WOEID))

It is used by Twitter to group trends by places, so it'll be useful if you are going to collect Twitter trends from different places using the API.

## How to use it?

If you want to **find a woeid** from a place just call ```get_woeid('a_place')``` and you'll receive its woeid. Example:
```get_woeid('Worldwide')``` returns ```1```

Otherwise, if you want to **find the name of a place or country**, and you already know its woeid, call ```get_place('a_woeid')```. Example 
```get_place(23424919)``` will return ```'Peru'```.

Aditionally, if a want the complete dictionary, you can use the function ```get_all()```.
