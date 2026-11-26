# PRODUCT REQUIREMENTS DOCUMENT (PRD)
## Campus Tricycle Dispatch & Checkpoint Scheduling System

## 1. Executive Summary
Campus mobility relies heavily on commercial tricycles (Keke) to transport students between hostels, lecture halls, administrative blocks, and campus gates. Currently the system operates on a physical hailing model whereby Students stand along roadsides and manually flag down passing
tricycles, leading to severe delays during peak lecture hours, unpredictable wait times, and frequent tardiness to classes.

This document outlines the requirements for a Checkpoint-Based Tricycle Dispatch Application to solve the problem.
Rather than an open-ended, on-demand door-to-door model (which may create unnecessary campus traffic congestion), the proposed solution assigns students to specific, verified campus tricycle drivers at designated Rendezvous Checkpoints for scheduled time slots. The primary objective of the Minimum Viable Product (MVP) is to eliminate physical hailing uncertainty and ensure students arrive at their lectures on time.

## 2. Problem Statement & Deep Research

### 2.1 The Core Problem
The current campus tricycle transportation system is fundamentally unreliable because it depends entirely on visual proximity and manual hailing. A student cannot know if a tricycle is available, full, or heading in their direction until the vehicle is physically within sight. During peak periods (e.g., 7:00 AM - 9:00 AM morning rush, or 12:00 PM - 2:00 PM lecture transitions), demand drastically outstrips visible supply at hostel zones, resulting in unproductive scrambling, wasted time, and missed classes.

### 2.2 Who Has the Problem? (Target Personas)
* Primary persona-The time constrained student who may be staying at a far away hostel(RIDER).
* Secondary persona-The campus registered tricycle driver who may be looking for passengers during off-peack hours(DRIVER).

## 3. Research & Field Findings
​To understand the problem properly, we observed campus transit points during peak lecture hours and spoke with 15 on-campus students, 1 off-campus studemt and 5 campus tricycle drivers.

### 3.1 How people cope today and why existing solutions fall short
* Leaving hostel early to avoid taking tricycle(keke) altogether. WHY IT FALLS SHORT: Wastes alot of rest time and if the lecture hall is far students may still be unable to get there on time. 
* Roadside hailing. WHY IT FALLS SHORT: Wastes time if tricycles are unavailable at that point in time, and favours those who get in the tricycle first or whose destinations are closer. It's also causes unpleasant to the drivers stoping reapeatedly by the side of the road causing unpleasant and sudden traffic disruptions.

### 3.2 Key Interview Takeaways
* ​Most students said they have been late to class at least once a week because they could not flag down a tricycle in time.
* Drivers confirmed they prefer picking up waiting passengers at known campus stops rather than stopping repeatedly along the road.

## 4. Proposed Solution
Our solution is a simple mobile/web scheduling app that replaces random roadside flagging with scheduled checkpoint pickups.

HOW IT WORKS
 
1. RENDEZVOUS CHECKPOINT: Instead of waving down tricycles anywhere on the road, the campus uses fixed, well-known pickup points (e.g., Hostel Gate, Main Library, Science Complex, Main Gate).
2. TIME-SLOT BOOKING: A student opens the app, selects their pickup checkpoint, destination checkpoint, and departure time slot (e.g., 7:00 AM).
3. DIRECT DRIVER ASSIGNMENT: The system matches the student with a specific available tricycle driver scheduled to be at that exact rendezvous checkpoint at that time, displaying the driver's name, tricycle ID/plate number, and pickup time.
4. RELIABLE ARRIVAL: Both the student and the assigned driver meet at the checkpoint at the agreed time, removing the guesswork of waiting by the road and helping students get to classes on time.
