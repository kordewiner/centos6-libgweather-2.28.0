# centos6-libgweather-2.28.0
All Mate and GNOME apps are no longer able to display weather forecasts 
on CentOS release 6.8, because National Oceanic and Atmospheric Administration 
of the United States (NOAA) has discontinued one of their APIs in August 2016, 
one that libgweather-2.28 uses. So we stop using the broken 
http://weather.noaa.gov/cgi-bin/mgetmetar.pl (National Weather Service) script 
and use http://aviationweather.gov/metar/data (Aviation Weather Center) instead.
The idea was stolen at:
https://github.com/mate-desktop/libmateweather/commit/835055e0d0b950d3f66ad236de7e40942f6f7d8e
