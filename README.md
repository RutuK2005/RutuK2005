# Rutuparn Kulkarni

I'm a Data Science student at DY Patil International University, graduating in 2027. Most of what I build is Python that sits between systems: pulling data out of APIs, cleaning it up, and sending it somewhere useful.

Since early 2025 I've been doing that for real clients. I co-founded AutomateIQ, a small automation agency, where I built n8n workflows and API integrations and plugged LLMs into client systems. Since February 2026 I've also been freelancing for clinics, automating how they collect and follow up on leads.

In college hackathons, our team's driving simulator won the internal round of Smart India Hackathon 2025. I worked on the Python side that read telemetry off the rig over serial. At an ISRO hackathon I prepared satellite images for a super-resolution model.

### Projects

- [lead-router](https://github.com/RutuK2005/lead-router): receives leads from ad and website forms, checks the webhook signature, cleans up phone numbers, drops duplicates, scores each lead with Claude (or simple rules if there's no API key) and forwards it to a CRM or n8n. It's a tidier version of the kind of thing I build for clients.
- [india-air-quality-etl](https://github.com/RutuK2005/india-air-quality-etl): pulls hourly weather and air-quality data for 8 Indian cities from Open-Meteo into DuckDB. Re-running it doesn't duplicate rows, and it only fetches days it hasn't loaded yet.
- [sim-telemetry](https://github.com/RutuK2005/sim-telemetry): a standalone rebuild of the telemetry part of the SIH simulator. Binary packets with a CRC, a parser that recovers from garbage bytes, and a live dashboard. There's a simulated car, so you can run it without the hardware.
- [satellite-tile-prep](https://github.com/RutuK2005/satellite-tile-prep): cuts big satellite images into overlapping tiles, normalises them and makes low-res/high-res pairs for training super-resolution models. It can stitch the tiles back together too.

On the side I'm building an Android-to-Windows photo backup app in C#/.NET. The code is private, but there's a [showcase repo](https://github.com/RutuK2005/phone-backup-showcase).

### What I use

Python (pandas, NumPy, requests, FastAPI, OpenCV, PySerial), SQL, DuckDB, n8n, REST APIs and webhooks, Docker, GitHub Actions. I've done Coursera courses on data pipelines/Spark and Power BI.

Outside of that I mentor at the Code Decode coding club (mostly teaching Python), mess around with electronics, and run marathons.

[LinkedIn](https://www.linkedin.com/in/rutuparn-kulkarni-a994a4373)
