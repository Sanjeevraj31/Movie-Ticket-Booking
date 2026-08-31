# 🎬 Movie Ticket Booking Management System (Pega Infinity)

A comprehensive workflow automation and case management application built on the **Pega Infinity Platform**. This application streamlines the end-to-end movie ticket booking process, managing request collection, queue assignment, cost calculation, SLA enforcement, and automated resolution confirmation.

---

## 📌 Project Overview

The **Movie Ticket Booking Management** case type (`Booking Management`) manages the entire lifecycle of a customer booking from initial intake to automated confirmation and exception/escalation handling.

### ✨ Key Features

- **Booking Intake & Collection**: Dynamic UI forms to capture user preferences, movie showtimes, seat selections, and availability checks.
- **Dynamic Pricing Engine**: Automated calculation of ticket pricing and discounts using decision tables (`SetTicketPrice`).
- **Smart Queue Routing & Subprocesses**: Intelligent assignment, background ticket provisioning, and dependency-based wait logic.
- **SLA Enforcement & Progress Monitoring**: Proactive service-level agreements (SLAs) tracking ticket status and managing escalation reviews.
- **Resolution & Notifications**: Automated email acknowledgments, AI-assisted booking summaries, and confirmation updates.

---

## 🏗️ Case Lifecycle Architecture

The application is structured into the following primary stages:
