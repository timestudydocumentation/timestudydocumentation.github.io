Overview of the study
=========================
.. _publications:

The **Temporal Influences on Movement and Exercise (TIME) Study** uses mobile and wearable technologies to measure moment-to-moment experiences that shape our health behaviors and decision making. The goal is to study how different contextual and situational factors explain the adoption and maintenance of health behaviors. We are using a combination of phone-based experience sampling, wearable-based micro-EMA, and passive sensing to build predictive models of health behavior at the individual and group levels. We conducted a within-subject case-crossover observational study across a 12-month period among ethnically-diverse, emerging adults (ages 18-29). Interested researchers are suggested to read the two :ref:`protocol paper <publications>` to find more details about the study.

Participant Recruitment
------------------------
N=250 young adults (18-29) with personal Android smartphone who engage in recommended levels of physical activity (PA) or intend to within the next 12 months.

Study design
------------
Up to 12 months of data collection via online questionnaires, EMA&uEMA, and passive sensing on smartwatch and smartphone

- Online questionnaires at baseline, 6 months, and 12 months into the study

- Continuous smartwatch wear (~23 hours/day every day including during sleep)

- Signal Contingent EMA questions on smartphone and smartwatch

  - Phone End of day EMA survey (1-2 min) -> every night delivered 3 hours before self-reported sleep time

  - Phone Burst survey (1-2 min) -> 4-day smartphone survey bursts twice a month at least 7 days apart. Each burst period consists of 2 weekends and 2 weekdays. Survey is delivered once an hour during participant’s self-reported waking hours.

  - Phone Wake/Sleep survey (1 min)-> every 6-8 hours to confirm or establish previous/next sleep/wake time

  - Smartwatch survey (2-4 seconds) -> single questions that mirror EMA measures, validate sensor measurements, or test data validity. Up to 6 an hour during self-reported waking hours.

- Context-Sensitive EMA (contingent on events/exposures detected by built-in smartphone/smartwatch sensors) to improve utility of sensor data

  - Location, social context, posture/ambulation, watch wear/non-wear, sleep duration


Online Questionnaire Measures
-----------------------------

- General Health Questions

- Physical Activity (IPAQ)

- Usual Level of Lifestyle Physical Activities

- Team Sports/Classes

- Stage of Change for PA

- Sedentary Behavior (SB)

- Digital Media Use

- Technology Use

- Stage of Change for SB

- Munich Chronotype

- Sleep problems

- Insomnia, snoring, restless leg syndrome

- Stage of Change for Sufficient sleep

- Dietary Screener

- Disordered eating

- Substance use

- Watch wear

- Country of origin

- Acculturation

- Demographics

- TIPI (Big 5 Personality)

- Self-esteem

- Life Satisfaction

- Perceived Stress

- Stressful Life Events

- Depression

- Trait Anxiety

- BIS/BAS

- Self-control

- Habit (PA, SB, Sleep)

- PA Identity

- Attitudes (PA, SB, Sleep)

- Enjoyment (PA)

- Intrinsic/Extrinsic motivation (PA)

- Preference/Tolerance (PA)

- Self-efficacy (PA, SB, Sleep)

- Regulatory effort (PA)

- Intentions (PA, SB, Sleep)

EMA Measures on Mobile Devices
------------------------------
Find detailed item description `here <https://docs.google.com/document/d/1XQEkHa7GiSVnc8vuuiiKmHqnqYE_6eqA/edit?usp=share_link&ouid=114892255827597694084&rtpof=true&sd=true>`_.

.. image:: /images/measurements.png
  :width: 600

.. image:: /images/ema_schedule.png
  :width: 800

Passive Sensing on Mobile Devices
----------------------------------------------
Passive sensing data were collected continuously from user's own **Android smartphones** and **Fossil Gen 4/5 smartwatches** given by researchers. More information about these data can be found in the codebooks. The tables below show the types of sensor data we collected and different formats data are processed and stored in.

- Raw log file: the most raw data logged directly from the mobile devices (example file)

- Minute-level file: minute-level aggregation of raw logs (example file)

- Hour-level file: hour-level aggregation of minute-level file (example file)

- Day-level file: day-level aggregation of hour-level file (example file)

**Physical activity and location**

All motion summary measurements were computed based on accelerometer data from smartwatches. Location data were collected through Android API on the smartphones.

- MIMS (Monitor Independent Movement Summary unit): a type of measurement of motion summary that features harmonizing the processing of accelerometer data from different devices

- AUC (area under curve): a type of measurement of area under the rectified curve of the raw accelerometer signal

- SWaN (v1.0): an algorithm to distinguish between sleep-wear, wake-wear, and non-wear of smartwatch

- Phone detected activity: detection of activity and confidence levels using Android Activity Recognition API, including in vehicle, on bike, on foot, running, still, tilting, walking and unknown

- Step count: steps of the last hour returned from Android API

- Location: latitude, longitude returned from Android API

- Location cluster semantic labels: semantic labels collected from self-reported surveys and OpenStreetMap databases on the location clusters detected by density-based clustering algorithm

.. image:: /images/ps_activity.png
  :width: 600

**Smartphone state and usage**

- Screen states: power state (on/off) of the phone screen

- Wi-Fi states: wifi state (on/off) of the phone

- App use: use of app package

- Notification: time and app package of posted phone notifications

- Ringer mode: ringer mode of the phone

- Battery and charging: phone battery level and charging states (on/off)

.. image:: /images/ps_phone.png
  :width: 600

**Smartwatch state and usage**

- Battery and charging: watch battery level and charging states (on/off)

- Accelerometer missing: information on causes of minute-level watch accelerometer data being missing

- Do not disturb: whether watch was in DND mode

.. image:: /images/ps_watch.png
  :width: 600



