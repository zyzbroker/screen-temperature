# Screen Temperature Adjustment

Long-time reading document on the screen irritates your eyes very quickly. Most screen monitor allows you to adjust brightnesss and contract. But that is not enough. The default screen temperature 5600 from the manufacture has too many blue light, hurting your eyes.


## Reshift

https://github.com/jonls/redshift

This software will help you to adjust your screen temperature very efficiently. You can adjust temperature based on your need without depending the OS provider to give your boolean choice, in other words, either light or night. Why not between.


## Ubuntu OS

Here is the steps to install this software

- sudo apt-get install redshift redshift-gtk
- mkdir ~/.config/redshift
- cd ~/.config/redshift
- vim redshift.conf

Type in the following configuration

```
[redshift]
; Set the day and night screen temperatures
temp-day=3400
temp-night=3400
location-provider=manual

[manual]
lat={your location latitude}
lon={your location longitude}
```

**Note:**
- temp-day and temp-night value ranges are 1900 to 5500. The lower, the tougher to see clearly. The higher, the more irritating to eyes.

My advice is to see your eye doctore to get a eye glass with blue light protection. Then set the value to 3400. That is my comfortable zone for my eye. 
