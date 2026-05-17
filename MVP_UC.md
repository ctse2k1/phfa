***

# 📄 MVP Use Cases

## Personal Health Feedback App

### **Version: v1.0**

***

# 1. 🎯 Purpose of This Document

This document defines **key user use cases for Phase 1 (MVP)** so that:

*   Developers can understand expected product behavior
*   Product intent is clearly communicated
*   Implementation stays aligned with real user needs

***

# 2. 👤 Primary User

*   Individual with metabolic health concerns  
    (e.g., fatty liver, prediabetes)
*   Interested in intermittent fasting
*   Needs:
    *   structure (routine)
    *   feedback (data)
    *   motivation (progress signals)

***

# 3. 🔑 MVP Feature Scope

Included in this version:

*   Fasting tracking
*   Fasting reminders (basic routine support)
*   Ketone tracking (multi-method input)
*   Basic visualizations
*   Basic insights (rule-based)

***

# 🧩 4. Use Cases

***

# ✅ Use Case 1: Start Daily Fasting

### 🎯 Goal

User begins a fasting session easily and consistently.

***

### 👤 Scenario

User finishes eating and wants to begin fasting.

***

### 🪜 Steps

1.  User opens app
2.  User taps **“Start Fasting”**

***

### ✅ System Behavior

*   Record start timestamp
*   Change state to:
    → ⏳ *Fasting in progress*
*   Display:
    *   elapsed time (starts immediately)
    *   target fasting goal (e.g., 16h)

***

### 💡 UX Notes

*   Must be 1-tap interaction
*   Immediate visual feedback is critical

***

***

# ✅ Use Case 2: Receive Fasting Start Reminder

### 🎯 Goal

Help user establish consistent fasting routine.

***

### 👤 Scenario

User has defined preferred fasting start time (e.g., 8pm)

***

### 🪜 Steps

1.  Scheduled time reached
2.  App sends notification

***

### ✅ System Behavior

Notification:

    Time to start fasting
    [Start Now]

***

### 💡 UX Notes

*   Non-intrusive tone
*   Optional snooze (future enhancement)

***

***

# ✅ Use Case 3: End Fasting

### 🎯 Goal

User logs completion of fasting window.

***

### 👤 Scenario

User is ready to eat again

***

### 🪜 Steps

1.  User opens app
2.  Taps **“End Fasting”**

***

### ✅ System Behavior

*   Record end timestamp
*   Calculate fasting duration
*   Display summary:

Example:

    Fasting Completed ✅
    Duration: 15h 40m

***

### 💡 Motivation Feedback

*   “Great job maintaining your routine”
*   “Close to your 16h goal”

***

***

# ✅ Use Case 4: View Fasting History

### 🎯 Goal

User understands consistency and recent behavior.

***

### 🪜 Steps

1.  User opens dashboard / history screen

***

### ✅ System Behavior

Show:

*   Daily fasting durations
*   Simple trend chart (last 7–14 days)

***

### ✅ Basic Insight

*   “You fasted >14h on 5 of last 7 days”

***

***

# ✅ Use Case 5: Log Ketone Measurement

### 🎯 Goal

User records metabolic signal from home test.

***

### 👤 Scenario

User performs ketone measurement (urine or blood)

***

### 🪜 Steps

1.  User taps “Log Ketone”
2.  Inputs:
    *   Value (e.g., 1.2)
    *   Method:
        *   Urine
        *   Blood

***

### ✅ System Behavior

*   Save reading with timestamp
*   Store measurement method
*   Update chart

***

### 💡 UX Notes

*   Fast entry (<5 sec)
*   Default previous method

***

***

# ✅ Use Case 6: View Ketone Trends

### 🎯 Goal

User visualizes metabolic changes over time.

***

### 🪜 Steps

1.  User opens dashboard

***

### ✅ System Behavior

Display:

*   Ketone level chart
*   Simple trend indicator:
    *   ↑ increasing
    *   ↓ decreasing
    *   → stable

***

### ✅ Insight Example

*   “Ketone levels trending upward this week”

***

***

# ✅ Use Case 7: Basic Correlation Awareness

### 🎯 Goal

Help user observe relationship between fasting and ketones.

***

### 🪜 Steps

1.  User views combined summary

***

### ✅ System Behavior

Display:

*   Fasting duration and ketone values (basic comparison)

***

### ✅ Insight Example

*   “Higher ketone readings tend to occur after longer fasts”

***

⚠️ Note:

*   Simple rule-based observation only (no complex analysis yet)

***

***

# ✅ Use Case 8: View Current Fasting Status

### 🎯 Goal

Provide immediate visibility of current state.

***

### 🪜 Steps

1.  User opens app home screen

***

### ✅ System Behavior

Display:

#### Current State

*   🍽 Eating
*   ⏳ Fasting

***

#### Timing Info

    Elapsed: 10h 20m
    Remaining: 5h 40m

***

### 💡 Importance

This is the **most frequently viewed screen**

***

***

# ✅ Use Case 9: Fasting Completion Notification

### 🎯 Goal

Reinforce behavior completion (motivation).

***

### 🪜 Steps

1.  Fasting duration reaches target

***

### ✅ System Behavior

Notification:

    You completed 16h fasting ✅

***

### ✅ Optional Message

*   “You may be entering fat-burning state”

***

***

# ✅ Use Case 10: View Basic Insights

### 🎯 Goal

Turn data into simple meaning.

***

### 🪜 Steps

1.  User opens insights section

***

### ✅ System Behavior

Display simple messages:

*   “Your fasting consistency is improving”
*   “You fasted longer this week vs last week”
*   “Ketone levels are increasing”

***

***

# 🧠 5. System Behavior Summary

***

## ✅ Inputs (MVP)

*   Fasting start / end times
*   Ketone values + method
*   Time-based triggers

***

## ✅ Outputs (MVP)

*   Timer / state display
*   Charts
*   Basic insights
*   Notifications

***

***

# ⚠️ 6. Out of Scope (Explicit for Developers)

Do NOT include yet:

*   Energy tracking
*   Blood pressure
*   Ketosis state engine
*   Pattern detection
*   Adaptive system
*   Exercise guidance
*   Condition dashboards
*   Social sharing

***

👉 Prevents scope creep

***

***

# ✅ 7. MVP Success Criteria

MVP is successful if:

*   Users log fasting daily ✅
*   Users log ketone data consistently ✅
*   Users can see simple trends ✅
*   Users feel more motivated ✅

***

# 🧭 8. Product Principles (For Development)

***

## ✅ 1. Speed > Complexity

All inputs must be fast

***

## ✅ 2. Always Show State

User should always know:

*   Am I fasting?
*   How long?
*   What’s next?

***

## ✅ 3. Immediate Feedback

Every action updates UI instantly

***

## ✅ 4. Low Friction

Avoid:

*   multiple steps
*   unnecessary inputs

***

***

# ✅ 9. Versioning Note

*   **v1.0** = Initial MVP definition aligned with Phase 1 roadmap
*   Future versions will:
    *   Add energy tracking
    *   Add ketosis state engine
    *   Add pattern detection and personalization
    *   Extend into health condition modules

***

# 👍 Final Comment

This document is now:

✅ Clear enough for engineers to start building  
✅ Focused enough to avoid overengineering  
✅ Aligned with your long-term vision

***
