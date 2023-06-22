# Yee Long's iOS Shortcut Catalog

I enjoy making my life a little easier by setting up shortcut applications and automations that improve my workflow.

Feel free to download these shortcuts and add them to your **Shortcuts App** (only available on iOS) and have fun!

### 🗂 **Applications**

> Listed are applications which I use frequently

⭐️⭐️⭐️: Worthy to check out first

1. [Scheduler](#scheduler)
2. [Last Parked](#last-parked)
3. [Movement Report](#movement-report)
4. [Running Track Distance Calculator](#running-track-distance-calculator)
5. [Where Should I Eat For Lunch?](#where-should-i-eat-for-lunch)
6. [Get Battery](#get-battery)
7. [Workout Planner](#workout-planner)
8. [Time To Location](#time-to-location)
9. [Per Day Spending](#per-day-spending)
10. [Change Case](#change-case)
11. [Sleeping Routine ⭐️⭐️⭐️](#sleeping-routine)
12. [Holiday Expense Trackers ⭐️⭐️⭐️](#holiday-expense-trackers)

### 🗂 **Automations**

> These are automations that make my everyday life easier

1. [When iPhone or iPad Is Charged Above 85% ⭐️⭐️⭐️](#when-iphone-or-ipad-is-charged-above-85)
2. [Auto Rotate Lock](#auto-rotate-lock)

### 🗂 **Supporting shortcuts**

> These are shortcuts which I made to improve my workflow of making shortcuts

1. [Read or Write Json File](#read-or-write-json-file)
2. [Encode or Decode Audio](#encode-or-decode-audio)

---

---

## Scheduler

> **Motivation:** I found adding events into calendars a bit of a hassle as there are too many options and a lot of time, I just want to type in the key information about an event I'd like to log.

### Solution:

A simple application that lives as a widget on my devices that prompts me for the key information about an event.

### Demo:

![Screenshot 2023-06-22 at 3 41 32 PM](https://github.com/siahyeelong/iOS-shortcuts-catalogue/assets/100999280/13980b9b-5e7f-401b-90de-e909ac2ea6ca)

---

## Last Parked

> **Motivation:** I tend to forget where I last parked my bike, and especially so when I am going to leave my bike there for some time before I ride it back.

### Solution:

A simple application that checks for my current location, and if it is near where I usually park, prompts me to log the specific location of where I will be parking my bike. Otherwise, it will just log the foreign location into a text file stored on iCloud. When I can't recall my last parked location, the app will pinpoint the exact location of where I last parked.

### Demo:

---

## Movement Report

> **Motivation:** When I was an IC in OCS, I had to send a lengthy standardised text into a WhatsApp chat group to document where we are heading, who is coming, and the purpose of movement.

### Solution:

To overcome the hassle of copying and pasting the past text and potentially missing out on updating certain fields, I created an application that prompts me for the necessary blanks to fill in, and settles the time stamp for me in 24H format.

### Demo:

---

## Running Track Distance Calculator

> **Motivation:** During COVID, you could only run on a specific lane in the public running track to prevent crowding in a lane. Considering that every lane has a different distance, it is difficult to determine the number of rounds you had to run to accomplish a certain distance.

### Solution:

I created a simple application that calculates the number of rounds one has to run to cover a specified distance.

### Demo:

---

## Where Should I Eat For Lunch?

> **Motivation:** My girlfriend can never make up her mind about where she'd want to eat for lunch. It was somehow my responsibility to then suggest a unique option every time she whined about it. To be fair, I do this sometimes due to the paradox of choice.

### Solution:

I filtered out the possible choices that she would deem worthy, then made a randomiser that picks out a random place to eat.

### Demo:

---

## Get Battery

> **Motivation:** Whenever I am charging my phone at the gym, I only had access to my apple watch. There is currently no feature to check on my phone's battery percentage through my apple watch, so I'd have to walk all the way to the locker and potentially having someone take my bench while I check on my battery level.

### Solution:

I created a shortcut that saves a request into an iCloud file, trigger a Focus event, which syncs with my iPhone. When the Focus event gets triggered on my iPhone, an automation reads the iCloud file, processes the request, gets the current battery state, and sets it as a reminder which syncs up with my watch to show me the battery level.

Very inefficient, but it's the only way out so far.

### Demo:

---

## Workout Planner

> **Motivation:** I follow a strict workout routine (Upper-Lower split, 2 types each) and can forget which split I last did in the gym. I also realised I had no way of tracking the past exercises I did and the weights I last did. Sometimes, there are deviations from the plan and I need to log it somewhere too.

### Solution:

A simple application that cycles through the split types (Upper 1, Lower 1, Upper 2, Lower 2) and prints out a standard note in my notes app for me to log. It also saves the gym location and time stamp.

### Demo:

---

## Time To Location

> **Motivation:** Whenever I am trying to time how long it takes to reach a destination, I tend to forget to stop my stopwatch.

### Solution:

I created 2 shortcuts that (1) logs my time of departure, and (2) show the elapsed time. This application is usually paired with an automation such that the automation is triggered when my GPS location is within the determined destination.

This currently works terribly as iOS shortcuts merely prompts you to run the automation rather than running it automatically.

### Demo:

---

## Per Day Spending

> **Motivation:** Although I track every cent I spend, the app that I use currently does not have a feature that allows me to see how much money I am left with to spend on an average daily basis till the end of a year (or a predefined time) according to a pre-set budget.

### Solution:

A simple application that calculates the time left till the end of the year and displays the amount I am left with to spend per day to fit within my budget.

### Demo:

---

## Change Case

> **Motivation:** Whenever I try to alter the case of a sentence / block of text, I would have to do this by character manually - and this is a terrible experience especially on my phone.

### Solution:

A simple application that prompts the type of case change, and transforms the clipboard item and saves the output back into the clipboard.

### Demo:

---

## Sleeping Routine ⭐️⭐️⭐️

> **Motivation:** Just before I sleep, I would have to switch off the lights and run towards my bed before the light goes out and the monsters get to me. I could just tell Siri to turn off the lights but it takes a few tries for Siri to recognise the command while I shout across the room. On days where I really can't wake up, I tend to shut off my alarm on accident and continue sleeping, which has resulted in disastrous outcomes. (Woke up to my flight instructor asking if I was going to fly the first wave; almost missed an exam; etc.)

### Solution:

An application that debriefs me on:

- alarms set
- time left till I have to wake up
- whether my backup wake-up system is activated
  - switches on my lights if I haven't woken up by a certain timing to shock me awake

while I take my time to get to bed before the Lights Off command gets triggered.

Additional feature: the application detects my location so that it turns off either the lights at home or in my hall respectively.

### Demo:

---

## Holiday Expense Trackers ⭐️⭐️⭐️

> **Motivation:** As an obsessive-compulsive expense-tracking maniac, I couldn't stand the idea of keying in dirty data into my money tracking app. What's worse is the "how much do I owe you ah" at the end of every trip because I NEED TO KNOW THE EXACT AMOUNT TO THE NEAREST CENT how much I owe or people owe me.

### Solution:

I created a Google Form which acts as the medium for collecting expense data, which can then be synced to a Google Sheet where I can do some basic data visualisation.
This shortcut then acts as a user-friendly no-internet-required front for my girlfriend and I to use. During poor internet connectivity, the shortcut saves the row of data into a local file on your iPhone, and updates each line of data into Google Forms accordingly when there is stable internet connection.

Google Sheets features:

- automatic conversion of currency if data is logged after the start date of the trip
- shows proportion of expenditure
- shows how much X owes Y at that point of time

Bonus feature: has a "Transfer" function (mechanism is on Google Sheets) to handle those "I just pay you back for this first" scenarios.

Room for improvement:

- multi-user support (currently only suitable for couples)
- currently requires users to manually set up every thing for a new trip

### Demo:

---

## When iPhone or iPad Is Charged Above 85% ⭐️⭐️⭐️

> **Motivation:** The best way to preserve battery life is to keep your device's battery charge between 20% to 80%. I often forget to unplug my phone since I may be busy at times, and would be afraid of leaving my phone to charge overnight.

### Solution:

This shortcut prompts the user to choose the desired action upon charging up the device past 85% (or any predefined amount). Once the device charges past 85%, the chosen action will be executed through the automation. The choices available are:

- Control another device's option instead
  - so that I can control my iPad's charging action from my MacBook or iPhone, and vice versa
- Charger off
  - runs the Charger Off shortcut to switch off the power at the smart plug
- Announce
  - plays a sound to notify me that my phone is charged
- Notification
  - sets a reminder where it is synced across my devices (useful during meetings)
- Buzz
  - simply vibrates the phone (I almost never use this)

Other battery-related shortcuts:

- Send a reminder whenever the battery drops below 20%
- Set volume to max and announce critically low battery below 10%

### Demo:

---

## Auto Rotate Lock

> **Motivation:** I like having my phone's rotation to be on lock whenever I am using it vertically except when I am trying to take a picture, watch a video, or show someone my photos. It becomes a hassle to turn off and on the rotation lock sometimes.

### Solution:

Based on the defined list of apps, the rotation lock will turn off when I am using these apps, and the rotation lock will turn on back when I exit from those apps.

### Demo:

---

## Read or Write Json File

> **Motivation:**

### Solution:

### Demo:

---

## Encode or Decode Audio

> **Motivation:**

### Solution:

### Demo:
