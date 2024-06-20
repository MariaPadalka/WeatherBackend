### Weather App Server

This is the server-side component of a weather application that provides weather data by interfacing with the OpenWeather API. The server is built using Node.js and Express.

---

## Table of Contents

- [Requirements](#requirements)
- [Setup](#setup)
  - [Configuration](#configuration)
  - [Installation](#installation)
- [Running the Server](#running-the-server)

---

## Requirements

- Node.js (version 14 or higher)
- NPM (Node Package Manager)

---

## Setup

### Configuration

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/MariaPadalka/WeatherBackend.git
   cd weather-app-server
   ```

2. **Environment Variables**:

   There is a file named `.env.example` provided in the root of the project. This file contains the template for the necessary environment variables:

   ```bash
   API_KEY=
   PORT=5000
   ```

   - **API_KEY**: The API key for the OpenWeather API. You can obtain your key by signing up at [OpenWeather API Keys](https://home.openweathermap.org/api_keys).
   - **PORT**: The port on which the server will run. The default is set to `5000`.

   To configure the environment variables:

   - **Create a new `.env` file**:

     ```bash
     cp .env.example .env
     ```

   - **Edit the `.env` file** and add your OpenWeather API key:
     ```bash
     API_KEY=your_openweather_api_key
     PORT=5000
     ```

### Installation

1. **Install Dependencies**:

   Make sure you are in the root directory of the project and run:

   ```bash
   npm install
   ```

   This command will install all the necessary dependencies specified in the `package.json` file.

---

## Running the Server

To start the server, run:

```bash
npm start
```
