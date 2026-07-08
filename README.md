# ride-dashboard
CycloSense Desktop Application

## 1. Access & Authentication

To ensure the highest level of security and data privacy, Ride Dashboard does not provide public registration.

* **Whitelist Access**: Access is restricted to authorized email addresses.
* **Requesting Access**: Contact your administrator to add your email address to the whitelist. Please specify the appropriate role:

    * **OBSERVER** – Monitor rides for designated team members or friends.
    * **USER** – View and manage your own rides and ride history.
* **Login Method**: The system uses **passwordless one-time passcodes (OTP)**. Enter your authorized email address to receive a six-digit verification code for secure access.

---

## 2. User Guide

### 2.1 Dashboard Layout

The dashboard consists of two main areas:

1. **Left Sidebar (Control Panel)** – Displays and manages ride lists.

    * **Active**: Shows rides currently in progress (`RIDING`) or requiring attention (`ALERT`). The list updates automatically.
    * **All**: Displays a paginated history of completed rides.

2. **Right Panel (Map)** – Provides a high-resolution map for real-time ride monitoring.

---

### 2.2 Live Monitoring

* **Selecting a Rider**: Click any ride card in the sidebar. The map automatically centers on and follows the selected rider.
* **Viewport-Based Streaming**: Live data connections are established only for rides currently visible in the map viewport. This minimizes network usage, improves overall performance, and keeps tracking responsive for the rides you are actively monitoring.

> **Note:** The system limits the number of simultaneous live connections.

---

### 2.3 Reviewing Ride History

1. Select a ride with the status `FINISHED` from the **All** tab.
2. The dashboard loads the complete ride track.
3. Replay the ride and review the recorded route, speed, timestamps, and GPS coordinates throughout the journey.

---
Official Website:
https://rg-page.aimellivora.com/
