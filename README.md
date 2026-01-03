# API-INTEGRATION
A responsive webpage that fetches and displays data from the REST Countries API.

**World Countries Directory**

A modern, responsive web application that fetches and displays real-time global data using the REST Countries API. This project demonstrates dynamic data integration, API handling, and responsive UI design.

**📌 Project Overview:**

This application provides users with an interactive interface to explore information about every country in the world. By leveraging the Fetch API, it pulls data dynamically, ensuring the information is always up-to-date without requiring a local database.

**🎯 Deliverables Met:**

**API Integration**: Successfully fetches data from a public REST API.

**Dynamic Content**: UI updates instantly based on search and filter criteria.

**Responsive Design:** Fully optimized for mobile, tablet, and desktop using Tailwind CSS.

**Error Handling:** Includes loading states and connection failure alerts.


## 🚀 Features
- **Live API Integration:** Fetches data dynamically from [REST Countries](https://restcountries.com/).
- **Search Functionality:** Filter countries by name in real-time.
- **Region Filtering:** Sort countries by continent/region.
- **Fully Responsive:** Optimized for mobile, tablet, and desktop views.
- **Optimized Performance:** Uses API field filtering to minimize data payload.

**🛠️ Tech Stack**
Technology           purpose
HTML5                Structural foundation
Tailwind CSS         Modern styling and responsive utility classes
Vanilla JavaScript   Asynchronous API fetching and DOM manipulation
FontAwesome          Professional iconography
Google Fonts         Typography (Poppins)

**⚙️ How It Works**
The application follows a standard Fetch-Filter-Display logic:

**Fetch**: On page load, fetchCountries() calls the REST API.

**State Management**: The data is stored in a global allCountries array to allow for instant filtering without repeated API calls.

**Filter**: Event listeners on the search input and dropdown menu trigger a filter function that matches user input against the country data.

**Display**: The createCountryCard function dynamically generates HTML components for each result.


  
