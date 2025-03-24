Auto-Scaling in Google Cloud Platform (GCP) 🚀
Overview
This project demonstrates auto-scaling in GCP based on local CPU utilization. It uses a Flask application running on a local VM (VirtualBox) that monitors CPU usage and automatically triggers GCP instance creation when the utilization exceeds a predefined threshold.

Project Structure
📌 app.py → Runs a local Flask server, monitors CPU usage, and triggers instance creation.

📌 create_gcp_vm.py → Defines the startup script and launches a GCP Managed Instance Group with autoscaling.

📌 Report.pdf → Step-by-step setup guide, system architecture, and implementation details.