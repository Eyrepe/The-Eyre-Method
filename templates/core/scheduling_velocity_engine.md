# The Scheduling and Velocity Engine
System Component: Core Mathematical Framework

This component defines the exact mathematical rules governing the timing, pacing, and attention management of the system. By publishing these algorithms, we provide open-source developers with the logic needed to build automated legacy transmission applications.

---

## 📅 Part 1: The 12-Day Rolling Interval Algorithm

### 1.1 The Mathematical Problem with Calendars
Human cognitive architecture naturally acclimates to rigid cyclical schedules. When an asset is delivered on a standard weekly or monthly cadence (e.g., every Sunday at 7:00 PM), the recipient’s brain categorizes it as a routine occurrence or expected clutter. This creates an immediate drop in text velocity and triggers a passive reading response.

### 1.2 The 12-Day Disruption Formula
To systematically eliminate cognitive habituation, the scheduling engine decouples the transmission interval from the traditional 7-day Gregorian calendar week by enforcing a strict operational window of exactly twelve fractional or whole diurnal cycles (288 hours) between subsequent payloads.

Because 12 and 7 share no common natural factors, the delivery timestamp dynamically shifts across the recipient's personal weekly matrix:

Timestamp_(n+1) = Timestamp_n + 12 days

### 1.3 The Fluid Rotation Pattern
This mathematical pacing guarantees that over a standard sequence, transmissions fluidly cycle across varying morning, afternoon, and evening windows, as well as alternating weekdays and weekend periods. 

An open-source implementation of this rolling schedule produces a highly unpredictable, spontaneous arrival sequence. Over a standard calendar year, this rhythm outputs exactly 30 high-yield text packages.
