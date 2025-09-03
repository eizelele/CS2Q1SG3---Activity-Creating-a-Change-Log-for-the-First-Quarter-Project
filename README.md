# CS2Q1SG3-Activity-Creating-a-Change-Log-for-the-First-Quarter-Project
This is a simple program that helps Filipino households struggle to manage daily tasks, schedules, and responsibilities.

## Features
Shared Family Calendar – synchronize events, deadlines, and appointments.
Synced Grocery List – real-time updating for collaborative shopping.
Bill Tracker with Reminders – avoid missed or late payments.
Pantry Tracking & Expiration Monitoring – prevent food waste.
Chore & Repair Reminders – assign and track household responsibilities.

## How To Run:
1. User Login → Select Family Group
2. Input Data (events, chores, bills, groceries, etc.)
3. System Processes inputs → syncs across family devices.
4. System Generates Outputs (reminders, recipe suggestions, task updates).
5. Users Receive Notifications/Updates → complete tasks → progress tracked.

## Output
START

 DISPLAY Main Menu:
        1. Manage Calendar
        2. Manage Grocery List
        3. Track Bills
        4. Pantry & Expiration
        5. Chores & Repairs
        6. Exit

    GET user choice

    CASE user choice OF
        1: 
            INPUT event/task details
            SAVE to shared calendar
            SEND notification to family members
        2: 
            INPUT grocery item
            UPDATE synced grocery list
            DISPLAY updated list
        3:
            INPUT bill details (due date, amount)
            SAVE to bill tracker
            SET reminder notification
        4: 
            INPUT pantry item + expiration date
            STORE data
            IF item nearing expiration THEN
                NOTIFY user
            END IF
        5:
            INPUT chore or repair task
            ASSIGN to family member
            SET reminder notification
        
        6:
            DISPLAY "Thank you for using FamiLynk"
            EXIT program
   END CASE
EXIT LOOP

END


## Contributors
1. Romero, Samantha B. (Features)
2. Martinez, Eizel Faye C. (How to run, Output)

