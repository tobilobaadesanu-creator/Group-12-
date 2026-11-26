# PRODUCT REQUIREMENTS DOCUMENT (PRD)
## Campus Tricycle Dispatch & Checkpoint Scheduling System

## 1. Executive Summary
Campus mobility relies heavily on commercial tricycles (Keke) to transport students between hostels, lecture halls, administrative blocks, and campus gates. Currently the system operates on a physical hailing model whereby Students stand along roadsides and manually flag down passing
tricycles, leading to severe delays during peak lecture hours, unpredictable wait times, and frequent tardiness to classes.

This document outlines the requirements for a Checkpoint-Based Tricycle Dispatch Application to solve the problem.
Rather than an open-ended, on-demand door-to-door model (which may create unnecessary campus traffic congestion), the proposed solution assigns students to specific, verified campus tricycle drivers at designated Rendezvous Checkpoints for scheduled time slots. The primary objective of the Minimum Viable Product (MVP) is to eliminate physical hailing uncertainty and ensure students arrive at their lectures on time.

## 2. Problem Statement 
Students may experience the following challenges:
* Unpredictable waiting times: Students do not know when the next tricycle will arrive.
* Roadside hailing: Students must wave at passing tricycles to get a driver's attention.
* Missed lectures: Delays in securing transportation can cause students to arrive late.
* Uncertainty about availability: Students may not know whether a tricycle has available seats.
* Poor coordination: Drivers may pass through areas where few passengers are waiting while other checkpoints have long queues.
* Congestion: Several students may gather around the same pickup point without knowing when transportation will be available.

### 2.1 The Core Problem
The current campus tricycle transportation system is fundamentally unreliable because it depends entirely on visual proximity and manual hailing. A student cannot know if a tricycle is available, full, or heading in their direction until the vehicle is physically within sight. During peak periods (e.g., 7:00 AM - 9:00 AM morning rush, or 12:00 PM - 2:00 PM lecture transitions), demand drastically outstrips visible supply at hostel zones, resulting in unproductive scrambling, wasted time, and missed classes.

## 3. Deep Research
A decision was made to conduct a research based on physical evaluation was conducted on random on campus students, tricycle(keke) drivers and off campus students who may be facing the project problem to pinpoint where current methods are lacking and how the application can help fill those loope-holes.

### 3.1 Who Has the Problem? (Target Personas)
* Primary persona-The time constrained student who may be staying at a far away hostel(RIDER).
* Secondary persona-The campus registered tricycle driver who may be looking for passengers during off-peack hours(DRIVER).

## 4. Research & Field Findings
​To understand the problem properly, we observed campus transit points during peak lecture hours and spoke with 15 on-campus students, 1 off-campus studemt and 5 campus tricycle drivers.

### 4.1 How people cope today and why existing solutions fall short
* Leaving hostel early to avoid taking tricycle(keke) altogether. WHY IT FALLS SHORT: Wastes alot of rest time and if the lecture hall is far students may still be unable to get there on time. 
* Roadside hailing. WHY IT FALLS SHORT: Wastes time if tricycles are unavailable at that point in time, and favours those who get in the tricycle first or whose destinations are closer. It's also causes unpleasant to the drivers stoping reapeatedly by the side of the road causing unpleasant and sudden traffic disruptions.

### 4.2 Key Interview Takeaways
* ​Most students said they have been late to class at least once a week because they could not flag down a tricycle in time.
* Drivers confirmed they prefer picking up waiting passengers at known campus stops rather than stopping repeatedly along the road.

## 5. Proposed Solution
Our solution is a simple mobile/web scheduling app that replaces random roadside flagging with scheduled checkpoint pickups.

HOW IT WORKS
 
1. RENDEZVOUS CHECKPOINT: Instead of waving down tricycles anywhere on the road, the campus uses fixed, well-known pickup points.
2. TIME-SLOT BOOKING: A student opens the app, selects their pickup checkpoint, destination checkpoint, and departure time slot (e.g., 7:00 AM).
3. DIRECT DRIVER ASSIGNMENT: The system matches the student with a specific available tricycle driver scheduled to be at that exact rendezvous checkpoint at that time, displaying the driver's name, tricycle ID/plate number, and pickup time.
4. RELIABLE ARRIVAL: Both the student and the assigned driver meet at the checkpoint at the agreed time, removing the guesswork of waiting by the road and helping students get to classes on time.

## 6. PRODUCT VISION AND OBJECTIVES
Product vision
To create a more reliable, accessible, and organised campus transportation system that helps students reach their destinations on time.

### Primary objectives
* Reduce the time students spend waiting for campus tricycles.
* Reduce the need for roadside hailing.
* Improve student punctuality.
* Introduce organised pickup and drop-off checkpoints.
* Help drivers identify areas with high passenger demand.
* Improve communication between students and transport operators.
* Provide students with better information for planning their journeys.

## 7.  Campus transport management application
Where applicable, campus transport coordinators will oversee the operation of the system.

They may need to:
* Approve designated checkpoints.
* Register participating drivers.
* Monitor service performance.
* Address complaints.
* Review demand patterns.
* Promote safe and orderly pickup practices.

## 8. Designated checkpoints
The university will identify approved pickup and drop-off locations across campus.
Examples could include:
* Student hostels.
* Main lecture areas.
* The university library.
* Cafeterias.
* Administrative buildings.
* Other approved high-demand locations.
* Students will select a checkpoint instead of standing anywhere along the road to hail a tricycle.
* Each checkpoint will have a clear name and location within the app.

## 9. THE SCHEDULE CHECKPOINT SYSTEM

The schedule checkpoint system is the central feature of CampusRide.It combines designated pickup points with expected departure or arrival times. Rather than allowing every student to search randomly for a passing tricycle, the system directs students to recognised checkpoints where transport availability is communicated in advance.

How it works

Step 1: Establish checkpoints

The university identifies suitable pickup locations based on student movement patterns and transport access.

Step 2: Set operating schedules

Participating drivers or transport coordinators establish service windows for each checkpoint.

Step 3: Students select their journeys

Students choose their pickup checkpoint, destination, and preferred departure time.

Step 4: The system checks availability

The app displays the next expected service and allows the student to request a seat when available.

Step 5: The driver receives the request

The driver receives the relevant pickup information and confirms the booking where confirmation is required.

Step 6: The student receives an update

The app notifies the student of the booking status and any significant changes to the estimated pickup time.

Step 7: The trip is completed

The student boards at the designated checkpoint and travels to the selected destination.

Important operational principle

The schedule should not be treated as a guarantee that a tricycle will arrive at an exact minute.

Travel times may change because of traffic, passenger loading, weather, or unexpected delays. CampusRide should therefore display estimated arrival windows and promptly communicate disruptions.

## 10. USER JOURNEY AND APP WORKFLOW

The application should provide a straightforward user experience.

Student journey

The student downloads CampusRide.

The student registers using an approved student identification method.

The student opens the app.

The home screen displays available checkpoints.

The student selects a pickup location.

The student chooses a destination.

The app displays available trips and estimated pickup times.

The student requests or reserves a seat.

The student receives a booking confirmation.

The student proceeds to the designated checkpoint.

The student boards the assigned tricycle.

The trip is completed, and the student can provide feedback.

Driver journey

The driver logs into the driver interface.

The driver views the assigned service schedule.

The driver checks passenger requests.

The driver confirms available seats.

The driver travels to the designated checkpoint.

Passengers board according to the confirmed bookings.

The driver completes the trip.

The system updates availability for subsequent trips.

The aim is to minimise unnecessary steps so that students and drivers can use the system without extensive training.

## 11. MINIMUM VIABLE PRODUCT (MVP)

An MVP is the simplest functional version of a product that can be tested with real users.

CampusRide should not begin with every possible feature. Instead, the first version should focus on proving that scheduled checkpoints can improve the student transportation experience.

Features for the first release

### Student registration.

A list of designated checkpoints.

A list of approved destinations.

Published pickup schedules.

Seat requests and booking confirmations.

A basic driver dashboard.

Booking status updates.

Delay and cancellation notifications.

A simple feedback system.

Features to postpone

Complex route optimisation.

Automated fare splitting.

Multiple payment integrations.

Advanced demand prediction.

Extensive live tracking.

Expansion to every transport category on campus.

### Recommended pilot

Start with:

One university campus.

Three to five checkpoints.

A small group of participating tricycle operators.

A limited number of student volunteers.

A short testing period, such as two to four weeks.

This pilot would help the team identify operational problems before expanding the service.
