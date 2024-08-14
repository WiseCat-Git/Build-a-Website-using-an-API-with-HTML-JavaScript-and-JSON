# Build-a-Website-using-an-API-with-HTML-JavaScript-and-JSON

# Objective:

Provide Ability for Users to Look Up 7-Day Weather Forecasts: The main goal was to create a user-friendly web application that allows users to easily look up the weather forecast for the next seven days for major European cities.

# Enhance User Engagement: 

By integrating dynamic elements such as a city selection dropdown, animated Swiper components for weather details, and visually appealing design, the project aimed to keep visitors on the site longer.

# Facilitate Increased Online Bookings: 

While this objective might be more specific to a commercial website, ensuring that users can quickly access weather information could support informed decision-making for travel-related bookings.
Technologies and Tools

1. HTML: Structure and layout of the web pages.
2. CSS (including Bootstrap): Styling, layout, and responsive design. The project employed separate CSS files for the core layout (master.css), typography (typo.css), utility classes (utilities.css), and components (form.css, results.css, swiper.css, footer.css).
3. JavaScript: Logic for fetching weather data using an API, data processing, and dynamic UI updates. The main logic was consolidated into a main.js file.
4. Swiper.js: Integrated for the interactive display of weather data slides.
5. 7Timer API: External API used to retrieve weather data without requiring an API key.
6. Google Fonts and Icons: For consistent and visually pleasing typography and icons.

# Achieving Project Goals

# Data Retrieval and Processing:

City Data: A JSON file, city_coordinates.json, was used to store information about the cities, including their names, countries, and coordinates (latitude and longitude). This allowed the application to dynamically load available cities into a dropdown selector for user convenience​(city_coordinates).
Weather Data Fetching: Weather data for selected cities was fetched from the 7Timer API based on user selection. The data was then processed to provide meaningful insights like temperature, weather conditions, and formatted dates​(main).

# User Interface and Experience:

1. Dynamic Dropdown: Users could select a city from a dynamically populated dropdown, which was automatically updated based on the city_coordinates.json data​(main)​(city_coordinates).
2. Swiper Component Integration: The Swiper.js component was employed to allow users to swipe through the weather forecast for the next 7 days. This interactive element kept users engaged by providing a smooth, responsive interface​(index).
3. Responsive Design: The web application was styled with Bootstrap and custom CSS, ensuring it remained visually appealing and functional across various devices. Background images, including a dynamic .gif image, were used to enhance the visual impact of the site​(main)​(index).

# Challenges and Solutions:

Error Handling: The project handled potential API errors and provided meaningful feedback in the browser’s console. An error related to the Swiper component not being defined was fixed by ensuring that Swiper was correctly initialized before being used​(main).
Custom Styling and Structure: The application’s structure was carefully planned with separate directories for images, styles, scripts, and data files. This not only helped in keeping the project organized but also facilitated easier updates and maintenance.
