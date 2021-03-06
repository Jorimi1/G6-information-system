# Objective 1. Outline the objectives of the project and define the problem (Steps 1 & 2 of Design Thinking Methodology). 
## Problem Definition
* The Major Travel Company’s current in-house call management centre is not operating efficiently enough and needs to be improved

## Project Objectives
* The System (TS) provides improved call routing and dynamic call flow control for both inbound and outbound calls
* TS assists Relationship Managers (RMs) in serving end-customers (or potential customers) by matching RMs and end-customers based on the RM’s skills, performance and product knowledge and customer profiles
* TS needs Integration of the Customer Profiler Tool that creates customer profiles to provide support for objective #2
* TS needs Integration of the RM Profile and Skill Matrix tool (The RM Profiler Tool) to provide support for objective #2
* Constant updating of RM profiles based on current RM performance (Done by RM Profiler Tool)
* The Outbound Call System: For outbound calls, automatically generate a Target List (from a database) for each RM (which holds customer details and automatically dial calls)
* For inbound calls, automatically route calls to their Internal Private Call Routing Branch- the Automatic Call Distributor (which gives a score from 1- 10 to the customer) and then reroute highest numbers to best possible RM match
* For inbound calls during busy times, automatically route calls to an Interactive Voice Response Unit (which prompts customers for options and asks them questions) before automatically routing to the Automatic Call Distributor


# Objective 5. List assumptions you have made in the systems analysis. 
* The RM Profile and Skill Matrix tool is considered The RM Profiler Tool
* The Customer Profiler Tool and the RM Profiler Tool work perfectly
* The RM Profiler Tool automatically does the adjustments to an RM’s profile based on their performance
* The Outbound Call System contains the database and target list generation which is used by The System
* End Customers and Potential Customers are a singular entity customer
