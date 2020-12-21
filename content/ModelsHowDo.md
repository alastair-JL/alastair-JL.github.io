---
title: "Models: How Do?"
date: 2019-08-29T17:42:36+02:00
draft: true
--- 
In the last episode of this rambling bloggy blog, I explained that the core idea of applied mathematics revolved around building Mathematical models (little pictures of the world).

I did not however get into the rather more finnickety bussiness of how on earth to do that.

![your_img](/Images/EarthPhotoVsPainting.png#center)

So, let's be clear- I'm not *going* to explain how to make a mathematical model in just one page. For now, I'm going to explain a few of the basic questions that act as good starting places for a model, and then throughout the rest of this Blog we can go into more detail and depth on some particular models.

So, lets get started:


**Step 1: What am I modelling? What am I trying to answer?**

This one may seem silly, but its important. Figuring out what you are trying to draw a picture of and knowing what details *matter* is important. If you are trying to draw a map, you need to know which city its a map of, and also who is going to use it and why. If it's a map to show tourists around the town, maybe you will only focus on the main streets and attractions. If its for locals, you need more detail. If you just want to guide your friend Alex from the airport to your house, then you probably only need the names of a few roads, and can leave the rest of the map blank. 

Decide what you're modelling. Decide what your question is. Or decide that you don't know your question yet - that's fine too.

**Step 2: What are the questions I can ask about my system? Can I turn these into variables?**
If you are trying to make a model about a race car, there are lots of questions you might want to ask. Where is the car? How fast is it moving? Which way are the wheels pointed? What *temperature* are the wheels? 

For every one of these questions, if the question is useful and relevant, you should make a variable and give it a name:
	*Position: P
	*Velocity: v
	*Wheel angle: \theta
	*Wheel temperature: T

You should then decide what kind of values you expect each variable to have. Position probably needs to say how far north/south the car is, and also how far east/west. Those should probably be measured in Meters. Maybe Kilometers. Do we need to know the cars height, or do we trust the car to stay on the ground? Where would the care be if it was at position (0.0m,0.0m)?

How about Velocity?

Not all variables have to be numbers. A switch might be ``on/off''. If we ask who is acting as the character 'Neo', then the answer would be 'Keanu Reeves'.

You might also want to think about how accurate you need to be. If you are planning a dinner, its probably enough to know ''There will be 10ish people''. If you are planning a chemistry experiment, you might need to know ''the temperature will be 303.584 degrees Kelvin''. 


**Step 3: How do my variables relate to one another? Can I turn this into equations?**
If I am planning a fishing trip, I might care how high the water is, or which direction the tide is moving. This depends on time, so I might say there is a relationship between the depth of the water, and the time:
d= 5m + 1.4m x sin(t/6)

Sometimes the value of one variable will tell you how another variable is going to *change* as time passes. For example, the position of a rocket changes based on its velocity.
P'= V

Sometimes you know two things are related, but you don't know *how* they are related, so you might stick in a ''unknown function'' connecting them. For example, if I think dinosaurs die when they get cold, but I don't know *how* cold then I might say:
\skull_\dino = f(T)


