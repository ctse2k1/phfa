# 📄 MVP Use Cases

## Personal Health Feedback App

### **Version: v1.2**

***

# 1. 🎯 Purpose

Define MVP user interactions clearly for development.

***

# 2. 👤 Primary User

*   Beginner/intermediate fasting user
*   Needs structure + motivation

***

# 3. 🔑 MVP Scope

*   Fasting goal (intent-based)
*   Fasting tracking
*   Configurable reminders
*   Ketone logging
*   Charts
*   Basic insights

***

# 🧩 4. Use Cases

***

# ✅ Use Case 1: Start Fasting

*   Tap “Start Fasting”
*   System tracks time and shows progress

***

# ✅ Use Case 2: Fasting Reminder (Optional & Configurable)

## Behavior:

*   Default:
        Reminder Time = 24h – Fasting Goal
*   Example:
    *   16h fasting → reminder after \~8h eating window

## Notification:

    Time to start fasting
    [Start Now]

✅ Can be disabled  
✅ Non-intrusive

***

# ✅ Use Case 3: End Fasting

*   Tap “End Fasting”
*   System shows duration and feedback

***

# ✅ Use Case 4: View Fasting History

*   Chart + daily durations
*   Simple consistency insight

***

# ✅ Use Case 5: Log Ketone

*   Input value + method (urine/blood)
*   Fast entry (<5 sec)

***

# ✅ Use Case 6: View Ketone Trends

*   Chart
*   Trend indicator

***

# ✅ Use Case 7: Basic Correlation

*   Compare fasting vs ketones
*   Simple rule-based insights

***

# ✅ Use Case 8: View Current Status

Display:

    Fasting ⏳
    Elapsed: X
    Remaining: Y
    Goal: 16h

***

# ✅ Use Case 9: Completion Notification

    You reached your goal ✅

***

# ✅ Use Case 10: Basic Insights

*   “Consistency improving”
*   “Fasting longer this week”
*   “Ketones increasing”

***

# ✅ Use Case 11: Set Fasting Goal (Intent-Based)

*   Input fasting duration (default: 16h)
*   No schedule required
*   No strict enforcement

Behavior:

*   Flexible start/end daily
*   Encouraging feedback

***

# ✅ Use Case 12: Configure Fasting Reminder

***

## Options:

### OFF

*   No reminders

***

### DEFAULT (Recommended)

*   Auto = 24h – goal

***

### CUSTOM (Advanced)

*   User defines reminder timing

Example:

*   Goal: 16h
*   Reminder: 6h eating window

👉 Enables challenge mode

***

## UI Example:

    Fasting Reminder:
    ( ) Off
    (•) Default
    ( ) Custom: [ 6h ]

***

# 🧠 5. System Summary

***

## Inputs

*   Fasting start/end
*   Goal
*   Ketones
*   Reminder settings

***

## Outputs

*   Timer & state
*   Charts
*   Insights
*   Notifications

***

# ⚠️ 6. Out of Scope

*   Energy tracking
*   BP monitoring
*   Pattern engine
*   Social features

***

# ✅ 7. Success Criteria

*   Daily usage ✅
*   Habit formation ✅
*   Visible progress ✅
*   User motivation ✅

***

# 🧭 8. Product Principles

***

✅ Intent over control  
✅ Flexible execution  
✅ Encourage, don’t punish  
✅ Always show progress

***

# ✅ 9. Version Notes

### v1.1

*   Introduced intent-based fasting goal

### v1.2 (Current)

*   Added configurable reminder system
*   Added challenge-mode behavior
*   Improved habit-based philosophy

***
