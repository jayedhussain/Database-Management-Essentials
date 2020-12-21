# Intercollegiate Athletic Database Schema
The Intercollegiate Athletic database supports the scheduling and operation of events.
Customers initiate event requests with the Intercollegiate Athletic Department.  
The facility and date held are recorded on the event request.  If an event request is denied, 
no additional action is taken.  If an event request is approved, one or more event plans are 
made.  Typically, event plans are made for the setup, operation, and clean up of an event.  
An employee is assigned to manage an event plan before the plan is executed.  
Initially, there may not be an assigned employee.  An event plan consists of one or more 
event plan lines.  In an event plan line, the resource, location, time, and number of resources 
(EventPlanLine.Number) are recorded.
It consists following tables:
Customer
Employee
Facility
Location
ResourceTbl
EventRequest
EventPlan
EventPlanLine
