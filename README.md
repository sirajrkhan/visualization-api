visualization-api - Heatmap
=================

{This is an older post}

IE7 (even IE6) complatible Map API

I was trying to create a heatmap which shows the energy consumption graph of different States / Counties in US. The sample code was working fine with 'world' view but when zoomed-in, it was showing me only New York in colored, however displayed all the counties... as usual not much help on relevant topic :(

Finally, after lot of trial and error I came to know that: the example provided at documentation is bit misleading... it simply uses "New York" while it should follow "US-NY" pattern... this way it was able to recognize "New York" somehow, but when I write "Miami" or "South Dakota" it didnt color the region.
