# Digital Golf Range Finder

`Note: Code was created in 2022, but was held privately until now. `

Welcome everyone to my attempt at creating a golf rangefinder using just an image! My name is Sergio Quijano, and I was a Division 1 golf athlete. Funny enough, my freshman year of college, I came to the US to play golf competitively at Mount St. Mary's University. Unfortunately, I had to endure my first year of college golf without a rangefinder. Now, I know it's not mandatory, but it's definitely a handy tool. At that time, I was just starting my Computer Science major and knew absolutely nothing about coding.

Fast forward a couple of years (with a rangefinder in hand!), and towards the end of my junior year, I decided to put my skills to the test and try to build something similar to a rangefinder using only a photo taken from your phone. This project was born out of that ambition. Spoiler alert: There's a good reason why golf rangefinders and GPS apps exist. However, the process was very fun and if anyone is curious enough can look at the code and see what I did. 

`Note: I will not share publicly the data (images) I used for training my models. However, after data augmentation processes I can say that it was in the ballpark of around 20,000 - 30,000 images.`

## Initial Plan

I don't know if this is the right way of accomplishing this task but this is the train of thought that I had while creating this project:
- Take an image from a given phone
- Identify if the image contained a golf flag in it or not
- If the image contained a flag then try to detect in what section of the image it was
- Once detected, try and piece a square that calcualated the scale and position of the flag
- Finally, with the given scale and position, try to come with an equation that allowed me to calculate the distance from where the image was taken to where the flag was physically

#### Where did I get to?
Given the significant learning curve I had to overcome to get there, I wasn't able to calculate the distance. However, I was able to succesfully identify if a given image contained a flag or not. Additionally, I was able to detect (with a given threshold) where in the image was the given flag. Hopefully, in a few years with more experience I can go back to this project and try it again!

`Note: Here I am in 2024 and giving it another try!`

## Project Summary

From the information above, we can see that there are two major takeaways from this project at the moment:
- Golf Flag classification within an image
- Golf Flag detection within an image

Important to notice the difference within these bullet points. Classification is desginated to identifying if the image contains a flag or not, whereas detection describes where in the image that contains a flag is the actual flag.

### Image Classification Model


### Object Detection Model
