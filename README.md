# Cortex_core-
Safe-Route: AI-Powered Night Navigation System

 Track

### Track 2 – Safe-Route (AI/ML, GenAI, NLP)

 ### Problem Statement

Navigating safely at night is a major concern, especially in urban and semi-urban areas. Traditional navigation systems like Google Maps optimize for shortest or fastest routes but may direct users through empty, poorly lit, or unsafe roads during nighttime.

Safe-Route addresses this issue by detecting traffic presence at night and intentionally routing users through well-populated, well-lit, and active roads, even if they are slightly longer—thus prioritizing user safety over speed.



 ### Objective

To build an AI-driven navigation system that:
	•	Identifies safe routes at night
	•	Avoids isolated and empty roads
	•	Prefers routes with active traffic, lighting, and human presence
	•	Enhances personal safety during night travel



 ### Key Idea

More traffic at night = more safety

Instead of avoiding traffic, Safe-Route uses traffic density, lighting data, and historical safety patterns to recommend safer paths.



 ### System Architecture / Flow
	1.	User Input
	•	Source & destination
	•	Time (night mode auto-enabled)
	2.	Multi-Channel Data Input
	•	Real-time traffic data
	•	GPS data
	•	Historical crime data (optional)
	•	Street lighting & POI density
	•	User reports
	3.	AI / NLP Processing
	•	Parses user intent
	•	Understands safety preferences
	•	Analyzes contextual night data
	4.	Triage & Prioritization Engine
	•	Scores routes based on:
	•	Traffic presence
	•	Lighting availability
	•	Area activity
	•	Historical safety
	5.	Safe-Route Generation
	•	Avoids empty roads
	•	Selects populated & monitored routes
	6.	User Output
	•	Safe navigation path
	•	Live status updates
	•	Alerts if entering low-activity zones



 ### AI & ML Components
	•	Traffic Density Analysis
	•	Night-time Risk Scoring Model
	•	Route Safety Scoring Algorithm
	•	NLP Parser for user intent & feedback
	•	Weighted Decision Model (Safety > Distance > Time)



 ### Tech Stack (Proposed)
	•	Frontend: React / Flutter
	•	Backend: Python (FastAPI / Flask)
	•	AI/ML: Scikit-learn, TensorFlow / PyTorch, Redis 
	•	Maps: Google Maps API / OpenStreetMap
	•	Data Sources: Traffic APIs, public safety dataset
	•	Database: PostgreSQL / Firebase/ Mongo DB/ Docker.com 
	



 ### Safety Parameters Considered
	•	Real-time traffic presence
	•	Road illumination (street lights)
	•	Nearby open shops / POIs
	•	Historical crime heatmaps
	•	Crowd density
	•	Emergency access availability



 ### Example Use Case

A user traveling at 11:30 PM selects a route:
	•	Traditional map → shorter but empty road ❌
	•	Safe-Route → slightly longer but busy & well-lit road ✅



 ### Future Enhancements
	•	SOS integration
	•	Live police & emergency station proximity
	•	Community safety ratings
	•	Women-specific safety mode
	•	AI-based anomaly detection



 Target Users
	•	Night commuters
	•	Women travelers
	•	Cab drivers
	•	Delivery personnel
	•	Students & night-shift workers
	•	Smart City Ready 
	
	



### Contributors Name of this Project/ Problem  Statement  
1. Saud Rana
2. Aanya Pal
3. Bhumuika Singh
4. Nirvish Soni
5. Heman Darji
6. Nirvish Soni
   

 ### Conclusion
Safe-Route redefines navigation by prioritizing human safety over speed, leveraging AI, real-time data, and intelligent decision-making to make night travel safer for everyone.

Safe-Route redefines navigation by prioritizing human safety over speed, leveraging AI, real-time data, and intelligent decision-making to make night travel safer for everyone.
