# Team Enigma Meeting Summary

*Mar 27, 2021*



## Overview

This is the second meeting of Team Enigma. Following a quiet online term, the Enigmatists decided to make an impactful start ahead of summer.

Major points raised included:

* [Improving publicity](#improving-publicity)
* [The EcoProject](#the-ecoproject)
* [Lectures](#lectures)

A [to-do](#to-do) list can be found at the bottom of this document.



## Funds

The general consensus was that realistically, funds should be taken from Computer Science Society. A budget of £100 was thought to be within reason.



## Improving Publicity

Easy, hassle-free participation was felt to be a major factor, as well as maintaining a media outlet. A number of possibilities were raised, but the ultimately accepted ones were:

* **Daily 'outlook' survey**

  This involves collecting boys' emotional responses to the day: whether they are tired, energetic, happy, or upset, etc...

  Together with the EcoProject, it could give interesting insight into whether environmental factors have a correlation with human emotions.

* **Harrovian publications**

  This involves Team Enigma members writing a brief snippet about the team's work / AI in general on each issue of the Harrovian.

  Data collected from the EcoProject may also be summarised and displayed on the back of the Harrovian (a bit like charts and figures from the Economist).

* **Other media outlets**

  A number of other ways to spread news of the group was suggested, although subject to a mixed reception. Key ideas were:

  * A *Team Enigma* *website*
  * A *social media page* (e.g. Instagram)
  * A *discord server*
  * A *newsletter*




## The EcoProject

Following the earlier discussion on improving publicity, much of which was centred on the EcoProject, the group continued to raise the following EcoProject key ideas:

* **Overview the EcoProject**
  * Multiple sensor stations located around the campus
    * Run on Arduinos / Raspberry PIs
    * Powered by solar cells
    * Measure temperature, humidity, PM2.5 concentration, volatile organic compounds (VOC), etc.
  * Sensor stations stream data periodically to database / server via Wi-Fi
  * Data transferred to high-end PC for AI training every few days
  * Results of training + current and past data available on public frontend
  * Boys will be encouraged to interact with this frontend as much as possible
  
* **Goals**
  * Promote environmental awareness
  * Monitor environmental changes on the Hill
  * Train AI to predict environmental conditions
  * At the end of term, combine daily environmental data with boys' emotional data to find interesting correlations
  
* **Foreseeable Problems**
  
  * *Where to host database?*
      * Use a custom AWS server 
          * Offers full low-level control over database and server code
          * Bigger storage
          * Needs £3 /month
      * Use Firebase
          * Simple to set up
          * Lots of REST APIs - integrate easily with Arduino / RPi / web without writing server code
          * Less storage
          * Free
  
  * *Location of sensor stations?*
      * Physics schools?
      * House gardens?
      * Top of St Mary's?
  



## Lectures

Regarding lectures, the general feeling was that *boy lectures at Harrow are too basic* with little to take away that couldn't be found quickly online.

It was suggested Team Enigma should drive to change this by putting more substance into its own lectures. The following key points were raised:

* **Make lectures more meaningful and engaging**
  * *Practicality should be a huge emphasis*
  * Boys should take away some completed project of their own from each lecture
  * Inviting famous YouTubers or scientists?
    * Tom Scott?
    * Posters should be well-designed in the fashion of a 'clickbait'
* **An AI lecture series**
  * A series of 4 lectures: AI Basics, NLP, Computer Vision, RL
  * After every session, boys should **walk away with a working AI system** (to show off)
  * There should be a challenge to work on every week based on the lecture
  * Boys with most attendance awarded little prizes
    * Attendance tracked by fancy methods: A Blockchain? 😂



## To-Do

### Over Easter

***Team Theory*** - Aakash and Vincent:

* The 'written stuff'
* Create an AI baseline model for the EcoProject
* Start preparing for the AI lecture series



***Team Hardware*** - David and Dylan:

* Find appropriate hardware for the EcoProject (boards, sensors, etc)
* Find appropriate method of data storage and transfer



### After Easter

* Finish one working prototype of the sensor station, server infrastructure and AI training loop
* Set up lecture series
* Drive for publicity