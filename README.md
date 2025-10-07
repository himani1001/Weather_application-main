# Weather App

🌐 **Live:** [https://himani-weatherapp.netlify.app/](https://himani-weatherapp.netlify.app/)

---

## 1. Project Description
A simple Weather Application built with React that allows users to search for any city and view current weather conditions, wind speed, humidity, heat index, and a 6-day forecast. The app also remembers the last searched city using localStorage.

---

## 2. Setup & Run Locally

### Prerequisites
- Node.js installed (v16+ recommended)
- npm installed

### Steps
1. Clone the repository:
   ```bash
   git clone git@github.com:himani1001/Weather_application-main.git

2. Navigate into the project directory:
    ```bash
   cd Weather_application-main

3. Install dependencies:
    ```bash
   npm install

4. Run the development server:
    ```bash
   npm run dev

## 3. Running Test Cases

Currently, this project does not include automated test cases.

You can manually test the app by:

- Searching for different cities in the search bar.

- Verifying the **last searched city persists** after page refresh.

- Checking that **weather data updates correctly** for different locations.

- Ensuring **weather icons correspond** to the current weather conditions.

- Confirming that **a clear error message** is displayed when an invalid city name is entered.

- Verifying the **6-day forecast view** is displayed and accurate.

- Checking that the design remains **responsive and user-friendly** on all devices.

## 4. Assumptions & Design Choices

- The app fetches weather data using the **Visual Crossing Weather API** through **RapidAPI**.

- The app assumes valid city names are provided by the user.

- **Axios** is used for making API requests.

- **React Context API** is used to manage global state, including weather data and loading/error states.

- Tailwind CSS is used for styling.

- Weather icons (sun, rain, cloud, etc.) are used to visually represent the forecast.

- A **6-day forecast** is displayed below the current weather.
