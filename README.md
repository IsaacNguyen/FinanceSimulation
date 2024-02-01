# Stock Trading Simulator

## Overview

This project is a full-stack website that simulates stock trading using the Yahoo Finance API. Users can quote, buy, and sell stocks within a simulated environment. Real-time tracking of transactions is implemented through a dedicated history tab and a connected database.

## Features

- **Yahoo Finance API Integration:**
  - Utilized the Yahoo Finance API to fetch real-time stock information.
  
- **Stock Trading Simulation:**
  - Enabled users to quote stock prices and execute buy/sell transactions in a simulated trading environment.

- **Database Integration:**
  - Utilized a database to store transaction data for historical tracking and analysis.
 
- **Registration and Login:**
  - Users can easily register for an account and securely log in, ensuring a seamless onboarding experience.

- **Personalized Account Storage:**
  - Each user account has a dedicated space in the database, allowing for secure storage of information, personalizing their stock trading simulation experience.

## Technologies Used

- **Backend:**
  - Flask (Python web framework)

- **Frontend:**
  - HTML, CSS, JavaScript
  - [Werkzeug](https://werkzeug.palletsprojects.com/) library for security and hashing functions

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/stock-trading-simulator.git

2. Set up a virtual environment (highly recommended)
   ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux or macOS
    # or
    venv\Scripts\activate     # On Windows

3. Install dependencies
   ```bash
     pip install -r requirements.txt

4. Run the application by inputting
  ```bash
    flask run
