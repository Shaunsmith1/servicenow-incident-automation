# ServiceNow Incident Automation (Zurich Release)

## Overview
This project demonstrates an automated incident-routing workflow built using ServiceNow Flow Designer in a Zurich Personal Developer Instance (PDI).

## Business Problem
Security-related incidents were manually triaged, leading to delayed response times and inconsistent assignment.

## Solution
- Implemented keyword-based logic to identify security-related incidents
- Automated assignment to the Security Operations group
- Automatically updated incident state using Flow Designer
- Built using upgrade-safe, no-script configuration

## How It Works
1. A new Incident record is created
2. Flow Designer checks the incident short description for security-related keywords (e.g., phishing)
3. Matching incidents are automatically assigned to the Security Operations group
4. Incident state is updated and a work note is added

## Technologies Used
- ServiceNow Zurich
- Flow Designer
- Incident Management

## Notes
Due to licensing restrictions in ServiceNow Personal Developer Instances, this solution demonstrates security incident handling using out-of-box Incident Management and Flow Designer automation.
