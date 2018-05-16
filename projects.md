Title:  Jesse Haubrich's Projects
# Jesse Haubrich
###### Software Engineer

<div id="contact">

* [jesse.haubrich@gmail.com](mailto:jesse.haubrich@gmail.com)
* [github.com/Jhaubrich](http://github.com/jhaubrich)
* [+1 405-796-6656](tel:+14057966656)

</div>

## Projects

### MCP - Webapp to parse GEO maneuvers and notify operators

Python/redis/JavaScript/docker/Linux - I built and maintain a
production tool that interacts with the National Airspace system
allowing our operators to be notified and download a GEO satellite
maneuver takes place so they can update WAAS.

### The WAAS Brewery - 2 million data points per minute

Python, ZeroMQ, docker, Graphite RRD -- I built a real-time monitoring
 system that captures and decodes network packets on our continental
 UDP ring. It captures the raw packets and queues them to be consumed
 by workers. The final product - realtime plots in graphite or any
 beautiful custom plotting tool that can listen on a port and parse
 json.

### Ionospheric Monitoring - d3.js plotting
[waas.faa.gov/static/sog/iono](http://waas.faa.gov/static/sog/iono/)

Python Flask/JavaScript -- Live plots of ionospheric activity. It is
part of a dashboard at the FAA. It is built on the Brewery described
above, and used as an example to teach other engineers how to build
web tools on the Brewery.

### DEA Drug Busts - personal project

[github.com/jhaubrich/dea_busts](https://github.com/jhaubrich/dea_busts)

I coded this up when I was buying a house. It displays on a map where
the meth labs were. It's very simple, but people talk about it more
than anything else I've done.


<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
<link rel="stylesheet" href="my.css" >
