# ✈️ Flight Management System

An OOP-focused application simulating flight reservations, passenger booking management, schedules, and flight manifests.

## 🛠️ Features

- **Passenger Logging:** Handles passengers dynamically inside flight profiles.
- **Flight Manifests:** Tracks routes, destinations, flight numbers, and passenger listings.
- **Time Representation:** Implements custom hours/minutes time representation for precision itinerary definitions.

---

## 🏗️ Structure Overview

- **`Flight`**: Core business entity encapsulating schedule, passenger lists, and metadata.
- **`Passenger`**: Details individual customer information.
- **`Time`**: Custom time formatter mapping departure and arrival schedules.
- **`Flightmanagement`**: Pre-configured execution sequence running sample schedules.

---

## 🚀 How to Run

1. Open your terminal in this directory:
   ```bash
   cd "Flight Management System"
   ```

2. Compile all files:
   ```bash
   javac *.java
   ```

3. Run the driver class:
   ```bash
   java Flightmanagement
   ```
