Jard-Lak | Security AI & Smart Inventory MVP

📌 Project Overview

Jard-Lak is an AI-driven smart inventory and logic-based security system designed to modernize warehouse management. This repository contains the Minimal Viable Product (MVP) dashboard built to simulate our core functionalities.

Our system replaces traditional manual inventory checks with automated tracking (simulating RFID technology). It not only tracks items but implements intelligent time-based security logic to differentiate between normal item movement and actual theft or loss.

✨ Core Features (MVP)

Real-time Polling Simulation: A built-in interval mechanism that mimics hardware RFID antenna sweeps every 30 seconds.

Intelligent Security Timers:

🟡 Soft Reminder: Items missing for > 15 minutes trigger a yellow warning.

🔴 Critical Alert: Items missing for > 1 hour trigger a pulsing red security alarm for immediate intervention.

Automated Logistics Queue: Items marked as "Sold" or permanently lost are automatically routed to a pending restock list to streamline supply chain operations.

Live Inventory Tracking: A dynamic, searchable data table displaying the exact status and physical location (simulated) of every tagged item.

💻 Tech Stack

HTML5 / CSS3

Vanilla JavaScript (ES6+): For handling the mock database, time-logic calculations, and DOM manipulation without the need for a complex backend during the MVP phase.

Tailwind CSS (via CDN): Used for rapid UI prototyping and achieving a clean, modern "SaaS" dark-mode aesthetic.

Lucide Icons: For scalable, consistent vector iconography.

🚀 How to Run Locally

Because this MVP is built with a single-file architecture for easy demonstration, running it requires zero setup or server installations.

Clone or download this repository to your local machine.

Locate the index.html file.

Double-click the file to open it in any modern web browser (Google Chrome, Microsoft Edge, Safari, etc.).

📁 Repository Structure

JardLak-MVP/
│
├── index.html        # The main application file (UI + Logic)
├── README.md         # Project documentation (You are here)
└── (Optional screenshots or wireframe assets can be added here)


 Academic Context

This project was developed as part of a university project. The implementation provided here specifically fulfills Part 10: Implementation & Demo requirements, showcasing a functional prototype managed via version control.
