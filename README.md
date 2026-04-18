# Panorama Object Audit Tool

A browser-based utility for Palo Alto Panorama administrators 
to identify unused and duplicate address/service objects 
across Panorama XML backups — without any live API interaction.

## 🔍 Problem It Solves
Over time, Panorama configurations accumulate unused address 
objects, duplicate entries, and redundant service objects. 
These bloat the configuration, increase push times, and make 
policy management harder. Manual identification across large 
environments is impractical.

## ⚙️ How It Works
1. Export XML backup from Panorama
2. Open the tool locally in any browser
3. Upload the XML file
4. Tool scans all address and service objects
5. Flags unused and duplicate entries
6. Results displayed on screen and exported to CSV

## 🛡️ Safety First
- Runs entirely in the browser — no server, no API calls
- No live connection to Panorama at any point
- Read-only analysis — makes no changes to any configuration

## 📋 Output
- On-screen list of unused objects
- On-screen list of duplicate objects
- CSV export for bulk review and correction

## 🧰 Built With
- HTML · JavaScript · XML parsing

## 📌 Use Case
- Panorama configuration cleanup
- Pre-migration object audit
- Configuration bloat reduction
- Security policy hygiene

## 👤 Author
Abhipray Limaye — Senior Cloud & Network Security Specialist  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhipray--limaye-blue)](https://linkedin.com/in/abhipray-limaye)
