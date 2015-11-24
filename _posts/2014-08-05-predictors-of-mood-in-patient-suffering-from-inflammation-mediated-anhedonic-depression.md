---
ID: 5965
post_title: 'Study: Predictors of Mood in Patient Suffering from Inflammation-Mediated Anhedonic Depression'
author: Daniel Feinberg
post_date: 2014-08-05 02:38:12
post_excerpt: >
  Using the Quantimodo self-tracking data
  integration platform to identify factors
  predictive of mood in an anhedonic
  subject.
layout: post
permalink: >
  https://quantimo.do/predictors-of-mood-in-patient-suffering-from-inflammation-mediated-anhedonic-depression/
published: true
ninja_forms_form:
  - "0"
  - "0"
vibe_subtitle:
  - ' '
vibe_author:
  - H
vibe_select_featured:
  - "0"
vibe_template:
  - ""
vibe_sidebar:
  - mainsidebar
vibe_title:
  - S
vibe_breadcrumbs:
  - S
vibe_prev_next:
  - H
slide_template:
  - default
sbg_selected_sidebar:
  - 'a:1:{i:0;s:1:"0";}'
sbg_selected_sidebar_replacement:
  - 'a:1:{i:0;s:1:"0";}'
---
## Variable of Interest Overall Mood 

## Research Question What factors are most predictive of mood in a subject suffering from inflammation-mediated anhedonic depression? 

## Answer The most significant predictor of elevated mood was sleep efficiency. 

## Participants This participant was a 34 year old caucasian male who has suffered from anhedonic depression for the last 20 years.  Additionally, this individual experiences chronic inflammation resulting in muscular pain, psoriasis, and acne. This individual tracked his mood, diet, sleep, physical activity, blood pressure, medication intake, and symptoms for 24 months. 

## Results This analysis determined that the factors most predictive of positive mood: 

*   Deep Sleep 
    *   Pearson Correlation: 0.6552
    *   1452 data points
    *   Parameters 
        *   Assumed Onset Delay = 0 Hours
        *   Assumed Duration of Action  = 24 Hours
        *   Basis of Correlational Analysis: Absolute Value
        *   Method of Aggregation: Average
*   Systolic Blood Pressure 
    *   Pearson Correlation: 0.4645
    *   108 data points
    *   Parameters 
        *   Assumed Onset Delay = 0 Hours
        *   Assumed Duration of Action  = 1 Hour
        *   Basis of Correlational Analysis: Absolute Value
        *   Method of Aggregation: Average
*   Calories Burned 
    *   Pearson Correlation: 0.5261
    *   1170 data points
    *   Parameters 
        *   Assumed Onset Delay = 0 Hours
        *   Assumed Duration of Action  = 24 Hours
        *   Basis of Correlational Analysis: Absolute Value
        *   Method of Aggregation: Average
*   Carbohydrate Intake 
    *   Pearson Correlation: 0.5227
    *   460 data points
    *   Parameters 
        *   Assumed Onset Delay = 0 Hours
        *   Assumed Duration of Action  = 24 Hours
        *   Basis of Correlational Analysis: Absolute Value
        *   Method of Aggregation: Average
*   PureLife Energy Boost (Supplement)
*   Vegetable Skillet Consumption     

[<img class="alignnone wp-image-18832 size-full" src="http://res.cloudinary.com/hmj5zmqze/image/upload/v1447369913/TSriDoP_zmaedz.png" alt="TSriDoP" width="1370" height="868" />][1]   
##  Participants

*   Subject 1 
    *   User ID: 230
    *   Age: 34
    *   IQ:17
    *   Average Mood (PANAS): 41%
    *   Sex: Male
    *   Groups 
        *   Inflammatory-mediated anhedonic depression
        *   Caucasian
        *   Acne
        *   ADD
        *   Depression

## Data Collection Methods

*   Sleep duration, schedule, and efficiency was tracked using: 
    *   The “Sleep as Android” mobile application
    *   A Fitbit device
    *   A BodyMedia armband
*   Diet was tracked using: 
    *   MyFitnessPal mobile and web application
    *   MyNetDiary mobile
    *   QuantiModo for Android
    *   The QuantiModo Chrome extension
*   Mood was recorded using: 
    *   The MoodiModo app for Android - Positive Affect Negative Affect Schedule (PANAS)
    *   The MoodiModo Chrome extension - 5 face rating
    *   Good Day Journal for Android - 5 star rating
    *   MoodScope.com - Daily 20 Question Positive Affect Negative Affect Schedule (PANAS)
    *   QuantiModo for Android
    *   The QuantiModo Chrome extension
*   Physical Activity was tracked using: 
    *   A Fitbit device
    *   A BodyMedia armband
    *   A Jawbone UP bracelet
    *   Accupedo for Android
*   Medications were tracked using the 
    *   The Medhelper mobile app
    *   The Medisafe mobile app
    *   QuantiModo for Android
    *   The QuantiModo Chrome extension
*   Social activity was quantified using: 
    *   Number of Facebook Likes
    *   Call Recorder for Android
*   Productivity was quantified using: 
    *   Github code commits
    *   Rescuetime for Windows, Chrome, and Android
*   Weight was tracked automatically using: 
    *   The Withings Wifi Scale
*   Blood Pressure was tracked using: 
    *   The iOS-Compatible Withings Blood Pressure Monitor
*   Heart Rate was tracked using: 
    *   Zephyr HXM Chest Strap Bluetooth Heart Rate Monitor in conjunction with the Android app SportsTrackerPro
    *   The iOS-Compatible Withings Blood Pressure Monitor
    *   CardioGraph for Android (using camera)
*   Weather data including precipitation, atmospheric pressure, cloud cover, and temperature was imported from: 
    *   World Weather Online
*   Environmental conditions such as room temperature and room CO2 levels were tracked with 
    *   The Withings Wifi Scale
*   Computer activity such as number of keystrokes and mouse clicks were automatically tracked with: 
    *   WhatPulse
*   Core body temperature was tracked and recorded using: 
    *   QuantiModo for Android
    *   The QuantiModo Chrome extension
*   Symptom severity was tracked using: 
    *   DataHabit for Android
    *   QuantiModo for Android
    *   The QuantiModo Chrome extension
*   Mobile application usage was tracked using: 
    *   AppTracker for Android
    *   Rescuetime for Android

## Data Integration

*   The *QuantiModo PHP Connector Framework* was used to import data from: 
    *   Fitbit
    *   MyFitnessPal
    *   MyNetDiary
    *   Rescuetime
    *   Withings
    *   Github
    *   World Weather Online
    *   MoodPanda
    *   Runkeeper
    *   Jawbone UP
    *   Facebook
*   The *QuantiModo Sync *Android application was used to import data from: 
    *   Good Day Journal
    *   MyFitnessPal
    *   Call Recorder
    *   Cardiograph
    *   DataHabit
    *   How Are You Feeling
    *   MedHelper
    *   Medisafe
    *   Sleep as Android
    *   T2 Mood Tracker
    *   Accupedo
    *   Zombies, Run!
*   The *QuantiModo REST PHP API* accepted data directly from the following client applications and extensions: 
    *   MoodiModo for Android
    *   App Tracker
    *   The MoodiModo Chrome extension
    *   The QuantiModo Chrome extension
    *   QuantiModo for Android

## Data Storage Data was stored in a MySQL relational database. 

## Data Analysis

1.  Filtering - Time series measurements of hypothetical “cause” variables are filtered to remove erroneous values outside the minimum and maximum reasonable daily values defined by the user (or the default crowdsourced average user setting).
2.  Time Shifting -  Mood data is shifted forward in time to compensate for  the estimated onset delay.
3.  Aggregation - “Effect” measurements are aggregated (averaged or summed) over the estimated duration of action
4.  Filling - For discretely tracked events such as medication intake, null values from missing data must be substituted with 0 values.
5.  Pairing - These aggregated “effect” measurements are paired with the “cause” measurements to produce an array.
6.  Correlational Analysis - The correlation coefficient is determined for that pair array to identify which factors are most predictive of mood.

<img class="aligncenter wp-image-6237 size-large" src="https://qm.wp.uploads.s3.amazonaws.com/uploads/2014/07/Flow-Chart-for-Correlations-Analysis-Optimal-Daily-Values-1024x898.png" alt="Flow Chart for Correlations Analysis Optimal Daily Values" width="1024" height="898" />  

 [1]: http://res.cloudinary.com/hmj5zmqze/image/upload/v1447369913/TSriDoP_zmaedz.png