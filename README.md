# Habit App Tracker
This is an app i built using Python. The purpose of the app is to help end users build good habits and stay consistent in those habits by allowing them to create the habits, and mark them as completed so to track their progress over time.
This app runs in the terminal and saves everything in a JSON File, so your habits will not dissappear.

## What can the APP do for you?

This habit tracker enables you to:
- add any new habits (from meditation, drinking water and to readingthe bible)
- choose if the habit frequency will be weekly or daily
- view all your habits over time
- save your habits so it stays available even if you restart the app
- Mark completed habits

## How does this app work?

### STEP 1 : Run the program
When you start the app, it open a simple menu where you can choose what you want to do (adding habits, complete habits and view your progress)

### STEP 2: The app loads saved habits 
Before showing anything, the app checks if there’s already a file called habits.json.
- If the file exists, it loads your saved habits
- If the file doesn’t exist yet, it starts fresh with an empty tracker
This makes the app feel like a real habit tracker, because your progress is always there.

### Step  3: Add your Habits
When you choose *Add Habit* the app asks you for:
- The name of your habit
- The habit frequency (*Weekly* or *Daily*)
The habit is the added on your habits list 

### Step 4: Viewing your habits
If you choose *View Habits*, the app shows you a list of habits you've created, including their frequency and how many times you've completed them. You own habit dashboard

### Step 5: Complete a Habit
When you choose Complete Habit, you select which habit you’ve done for the day/week.
Once you complete it:
- The app records the date and time
- It saves it as part of that habit’s completion history
This is what helps the app measure progress and streaks.

### How to view Progress
Through the following:
- total completions
- current streaks 
- past completion history



