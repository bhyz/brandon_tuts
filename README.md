README.txt
==========

## Intro:

  - __[__Pyro4_]_(https://pythonhosted.org/Pyro4/intro.html)
  - [__PyroMP__](http://pythonhosted.org/PyroMP/)

  - This Repo is to test and play around with Pyro4 and PyroMP. 
  
   - __Pyro__ (or actually Pyro4) is a very powerful library that allows you to develop 
     objects that can talk/pass messages to each other. It can take most types of parameters and return values. Individual methods can be called on each object. Objects can be distributed over a network and communication is via web-sockets.

     Pyro4 provides mechanism for registering the objects, and locating the objects when they are called.
     
     Its designed to be easy to use, works on Python3.

   - __PyroMP__ is a library, based on Pytor4 that allows the objects 
     to run in separate proccesses. These provides an easy transition from objects to services.

 - _This makes this lib ideal for doing IOT!_
   Where each IOT device is just a python object running in its own process, and can communicate with other devices or centralised servers.

   
