# Hack A Thing 1 - Chris Cheng

## What I attempted to build
Following up on my idea interview, I decided to try to build the front-end of a personal finance app for recent college graduates. The app would help you manage your expenses as well as offer automated insights and analyses to help young professionals track their spending and budget responsibly.

## What I learned
I learned that a good designer is worth their weight in gold! This was my first time ever working with Xcode and Swift to build an iOS app and it was really challenging for me to shift from the back-end Python work I've been doing for the majority of my college career in CS to this front-end stuff. I had to get used to establishing constraints for EVERYTHING, from buttons to labels to images... And I also learned how to edit and implement images to show up as nice buttons. Overall, I would say it was a successful first stab at the design of the app, but the devil is in the details. I learned from this first-hand experience that the front-end shenanigans for iOS apps are already hard enough without even thinking about the back-end and how to connect the two of those. 

My interviewee who suggested the personal finance idea did say the front-end would be the main challenge for an app like this, which is fair enough - all the back-end would need to do is store information, generate graphs, etc. The front-end has to facilitate all that and look nice as well. In other words, during this process, I learned the different moving parts of an iOS app that we take for granted when we scroll through our smartphones each day.

## What didn’t work
When I first skimmed the tutorials I did, I thought that Apple had made coding an app as simple as drag-and-drop. Not so. I tried a bunch of different looks in the app that didn't make it through to the final version. I tried implementing TableView for the button options to add and check expenses and check analyses, but that didn't shake out. I found out that the design I coded didn't work for iPhone 8s due to their smaller screen size, and definitely didn't look too pretty (in terms of the launch screen) when I was firing it up there. It's impossible to list everything that didn't work because I would say 90% of my time spent on this project was doing things that didn't work and hitting road blocks. That's 9 hours worth. One of the biggest issues I ran into was passing data between my ViewControllers, which took forever to figure out. 

In some cases, I wasn't able to figure code out. Specifically, the code for PickerView. The tutorial from iOS Academy on Youtube wasn't totally reliable in this instance, so I had to do some bootstrapping on my own. I was able to create the PickerView on the main page (which shows up kind of messily when you run it now) but not on the extended ViewController that shows up when you click the Add Expense button. Still trying to figure it out.

## Tutorials
* [CodeWithChris on YouTube](https://www.youtube.com/watch?v=09TeUXjzpKs)
* [iOS Academy on YouTube](https://www.youtube.com/watch?v=EsheQe6U_WE)
