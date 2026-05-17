***

# 📄 MVP Use Cases

## Personal Health Feedback App

### **Version: v1.1**

***

# 1. 🎯 Purpose of This Document

This document defines the **MVP (Phase 1) user use cases**, providing:

*   Clear user interaction flows
*   Expected system behavior
*   Product direction aligned with habit formation and real-world usage

***

# 2. 👤 Primary User

*   Individuals with metabolic health concerns (e.g., fatty liver, prediabetes)
*   Interested in intermittent fasting
*   Need:
    *   Simple routine guidance
    *   Feedback from real signals
    *   Motivation without pressure

***

# 3. 🔑 MVP Feature Scope

Included:

*   Fasting goal (intent-based)
*   Fasting tracking (manual start/stop)
*   Basic fasting reminders
*   Ketone tracking (urine/blood)
*   Basic visualization
*   Simple insights (rule-based)

***

# 🧩 4. Use Cases

***

# ✅ Use Case 1: Start Daily Fasting

### 🎯 Goal

User starts fasting with minimal effort.

***

### 🪜 Steps

1.  User opens app
2.  Taps **“Start Fasting”**

***

### ✅ System Behavior

*   Record start time
*   Display:
        Fasting in Progress ⏳
        Elapsed: 0h 00m
        Goal: 16h

***

### 💡 UX Principle

*   1-tap action
*   Immediate visual feedback

***

***

# ✅ Use Case 2: Receive Fasting Start Reminder

### 🎯 Goal

Help user build a consistent routine.

***

### 🪜 Steps

1.  Preferred reminder time is reached

***

### ✅ System Behavior

Notification:

    Time to start fasting
    [Start Now]

***

### 💡 Notes

*   Friendly tone
*   No pressure

***

***

# ✅ Use Case 3: End Fasting

### 🎯 Goal

User completes or stops fasting.

***

### 🪜 Steps

1.  User taps **“End Fasting”**

***

### ✅ System Behavior

*   Record end time
*   Calculate duration

Example:

    Fasting Completed ✅
    Duration: 13h 20m
    Goal: 16h

***

### 💡 Feedback Logic

If below goal:

*   “Good progress — building consistency”

If meeting/exceeding goal:

*   “You reached your goal ✅”

***

***

# ✅ Use Case 4: View Fasting History

### 🎯 Goal

User sees consistency over time.

***

### ✅ System Behavior

Display:

*   Daily fasting durations
*   Simple chart (7–14 days)

***

### ✅ Insight

*   “You fasted over 14h on 4 of last 7 days”

***

***

# ✅ Use Case 5: Log Ketone Measurement

### 🎯 Goal

User records metabolic data.

***

### 🪜 Steps

1.  Tap “Log Ketone”
2.  Input:
    *   value
    *   method (urine / blood)

***

### ✅ System Behavior

*   Save timestamp + method
*   Update chart

***

### 💡 UX Principle

*   Fast (<5 seconds)
*   Default last-used method

***

***

# ✅ Use Case 6: View Ketone Trend

### 🎯 Goal

User understands metabolic changes.

***

### ✅ System Behavior

Display:

*   Ketone chart
*   Trend:
    *   ↑ increasing
    *   ↓ decreasing
    *   → stable

***

### ✅ Insight

*   “Ketone levels trending upward”

***

***

# ✅ Use Case 7: Basic Correlation Awareness

### 🎯 Goal

Help user connect fasting behavior with ketones.

***

### ✅ System Behavior

Display:

*   Fasting duration + ketone readings

***

### ✅ Insight

*   “Higher ketones observed on longer fasting days”

***

⚠️ Simple rule-based only (MVP)

***

***

# ✅ Use Case 8: View Current Status

### 🎯 Goal

User instantly sees current state.

***

### ✅ System Behavior

Display:

    Status: Fasting ⏳

    Elapsed: 11h 10m
    Remaining to goal: 4h 50m

    Goal: 16h

***

### 💡 Importance

This is the **main screen users check frequently**

***

***

# ✅ Use Case 9: Fasting Completion Notification

### 🎯 Goal

Reinforce positive behavior.

***

### ✅ System Behavior

Notification:

    You reached your 16h goal ✅

***

### ✅ Optional message

*   “You may be entering fat-burning state”

***

***

# ✅ Use Case 10: View Basic Insights

### 🎯 Goal

Turn data into simple meaning.

***

### ✅ System Behavior

Messages like:

*   “Your fasting consistency is improving”
*   “You fasted longer this week”
*   “Ketone levels are increasing”

***

***

# ✅ Use Case 11: Set Fasting Goal (Intent-Based)

### 🎯 Goal

User defines a **simple fasting intent** to guide behavior.

***

### 🪜 Steps

1.  User opens **Fasting Settings**
2.  Selects fasting duration
    *   Default: **16 hours**
3.  Taps **“Save”**

***

### ✅ System Behavior

#### 1. Store Goal

*   Save fasting duration only

***

#### 2. No Fixed Schedule

*   No required start time
*   No defined eating window

***

#### 3. Use Goal as Guidance

Display:

    Fasting Goal: 16h

Show real-time progress:

    Elapsed: 12h 30m
    3h 30m to goal

***

#### 4. Allow Flexible Daily Behavior

*   User decides when to:
    *   start fasting
    *   stop fasting

***

#### 5. Handle Imperfection Gracefully

If goal not met:

*   “You fasted 12h today — good progress”

If goal exceeded:

*   “Great job — you exceeded your goal ✅”

***

### 💡 UX Principles

✅ Intent, not enforcement  
✅ Flexible daily execution  
✅ Encourage consistency over perfection  
✅ Minimal setup (1 input only)

***

***

# 🧠 5. System Behavior Summary

***

## ✅ Inputs

*   Fasting start / end
*   Fasting goal
*   Ketone values + method
*   Time triggers

***

## ✅ Outputs

*   Current state (fasting/eating)
*   Timer and progress
*   Charts
*   Simple insights
*   Notifications

***

***

# ⚠️ 6. Out of Scope (MVP Boundary)

Do NOT include yet:

*   Energy level tracking
*   Ketosis state engine
*   Pattern detection
*   Blood pressure
*   Exercise recommendations
*   Adaptive system
*   Condition dashboards
*   Social / sharing features

***

👉 Prevent scope creep

***

# ✅ 7. MVP Success Criteria

MVP succeeds if:

*   Users track fasting daily ✅
*   Users log ketones regularly ✅
*   Users see progress trends ✅
*   Users feel encouraged to continue ✅

***

# 🧭 8. Product Principles

***

## ✅ 1. Intent Over Control

User sets goal, not strict rules

***

## ✅ 2. Simplicity First

Fast interactions, minimal inputs

***

## ✅ 3. Encourage, Don’t Penalize

No “failure” states

***

## ✅ 4. Visibility Always

User can instantly see:

*   current state
*   progress

***

## ✅ 5. Real-World Flexibility

App adapts to user life, not vice versa

***

***

# ✅ 9. Version Notes

## v1.0

*   Initial MVP definition

## v1.1 (Current)

*   Added **intent-based fasting goal**
*   Aligned entire system to:
    *   flexible routine
    *   habit-building philosophy
    *   non-strict UX

***

# 👍 Final Summary

This MVP delivers:

✅ A **simple fasting habit system**  
✅ A **basic metabolic tracking tool**  
✅ A **low-pressure, sustainable user experience**

***

## 🚀 What Developers Should Understand

You are building:

> NOT a strict fasting scheduler  
> BUT a **supportive habit-building system**

***
