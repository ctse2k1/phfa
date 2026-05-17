***

# 📄 MVP Use Cases

## Personal Health Feedback App

### **Version: v1.3 (Updated)**

***

# 1. 🎯 Purpose

Define clear user interactions to guide MVP development.

***

# 2. 👤 Primary User

*   New or intermediate fasting users
*   Seeking structure + feedback
*   Different experience levels

***

# 3. 🔑 MVP Scope

*   Fasting goal (intent-based)
*   Fasting tracking
*   Configurable reminders
*   Ketone tracking (3 modes)
*   Charts & insights

***

# 🧩 4. Use Cases

***

# ✅ Use Case 1: Start Fasting

*   User taps “Start Fasting”
*   Timer begins
*   State displayed

***

# ✅ Use Case 2: Fasting Reminder (Optional & Configurable)

*   OFF / Default / Custom
*   Default:
        Reminder = 24h – fasting goal
*   Supports challenge mode (shorter eating window)

***

***

# ✅ Use Case 3: End Fasting

*   User taps “End Fasting”
*   Duration calculated
*   Encouraging feedback shown

***

***

# ✅ Use Case 4: View Fasting History

*   Daily durations
*   Basic trend chart
*   Simple insights

***

***

# ✅ Use Case 5: Log Ketone Measurement (Multi-Mode)

***

## 🎯 Goal

Enable fast, stage-appropriate ketone tracking.

***

## Step 1: Select Method (one-time)

    ( ) Urine Test
    ( ) Blood Test
    ( ) Physical Signs

***

## Step 2: Daily Logging

***

### 🔵 Urine Test

Input:

    [ Negative ]
    [ Trace ]
    [ Small ]
    [ Moderate ]
    [ Large ]

***

### 🔴 Blood Test

Input:

    [ 1.2 mmol/L ]

***

### 🟢 Physical Signs

Input:

    [ ] Keto Breath
    [ ] Appetite Suppression
    [ ] Increased Energy & Focus
    [ ] Keto Flu
    [ ] Increased Thirst

***

## ✅ System Behavior

*   Auto-save method
*   Record timestamp
*   Allow multiple entries daily

***

## 💡 Key Design

*   Fast input (<5s)
*   Method persistence
*   Supports all user stages

***

***

# ✅ Use Case 6: View Ketone Trends (Method-Aware)

***

### 🔵 Urine Mode

*   Categorical trends
*   Insight:
    *   “Levels increasing”

***

### 🔴 Blood Mode

*   Numeric trends
*   Insight:
    *   “Stable in ketosis range”

***

### 🟢 Physical Signs Mode

*   Signal frequency
*   Insight:
    *   “More ketosis signals detected”

***

***

# ✅ Use Case 7: Basic Correlation (Method-Aware)

***

### 🔵 Urine

*   Fasting vs level category

***

### 🔴 Blood

*   Fasting vs mmol/L

***

### 🟢 Physical

*   Fasting vs signal frequency

***

***

# ✅ Use Case 8: View Current Status

    Fasting ⏳
    Elapsed: X
    Remaining: Y
    Goal: 16h

***

***

# ✅ Use Case 9: Completion Notification

    You reached your goal ✅

***

***

# ✅ Use Case 10: Insights

*   “Consistency improving”
*   “Longer fasting → better results”

***

***

# ✅ Use Case 11: Set Fasting Goal (Intent-Based)

*   Input fasting duration only
*   No schedule
*   Flexible daily behavior

***

***

# ✅ Use Case 12: Configure Reminder

Options:

*   OFF
*   Default
*   Custom

Supports:

*   Habit formation
*   Challenge progression

***

***

# 🧠 5. System Summary

## Inputs

*   Fasting start/end
*   Goal
*   Ketone data
*   Reminder settings

***

## Outputs

*   Timer
*   Charts
*   Insights
*   Notifications

***

***

# ⚠️ 6. Out of Scope (MVP)

*   Energy tracking
*   BP
*   Advanced analytics
*   Social features

***

***

# ✅ 7. Success Criteria

*   Daily usage ✅
*   Habit formation ✅
*   Continued engagement ✅

***

***

# ✅ 8. Version Notes

### v1.2

*   Reminder system introduced

### v1.3 (Current)

*   Multi-mode ketone tracking
*   Method-aware insights
*   User progression model added

***

