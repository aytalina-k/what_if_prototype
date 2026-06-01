WHAT-IF Project – WP4 Prototype Simulation Model
------------

Agent-based simulation model developed as part of Work Package 4 (WP4) of the WHAT-IF project (ERC Horizon Grant Agreement #101177574).

Contributors: Aytalina Kulichkina, Taehee Kim, Annie Waldherr, David Garcia

Overview
------------
This repository contains a prototype agent-based model implemented in NetLogo. 
The model simulates online public discourse in a two-dimensional attitude space. 
Agents represent ordinary users and committed actors positioned according to their attitudes on two configurable political dimensions (i.e. climate change and immigration).
At each time step, agents generate and share social media posts. Ordinary users integrate incoming content into memory based on a distance-weighted acceptance probability (Geschke et al., 2019). 
Committed actors influence ordinary users by systematically exposing them to content aligned with their own attitudes. 
These micro-level interactions generate macro-level dynamics such as attitude change, opinion clustering, and fragmentation. 


Requirements
------------
NetLogo 7.0.3 or later
Download from: https://ccl.northwestern.edu/netlogo/download.shtml


Running the model
-----------------
1. Install NetLogo (see link above).
2. Open NetLogo.
3. Go to File > Open and select what_if_prototype_prelim.nlogox.
4. Click 'Setup' to initialise the model
5. Click 'Go' to run the simulation

Detailed documentation of the model design, assumptions, and parameters is provided in the model’s Info tab (NetLogo interface).
