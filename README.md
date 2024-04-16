# ADR

Architectural Decision Record for Weather Application
Introduction
This Architectural Decision Record (ADR) captures the architectural decisions made for the development of our personalized weather application. The decisions herein are the result of collaborative discussions, requirement analyses, and a thorough review of technological options in the context of the project's objectives.

Background
The project aims to deliver accurate and personalized weather forecasts through a user-friendly mobile application. A primary goal is to leverage robust and efficient technologies that align with our current skill set and future scalability needs.

Architectural Decisions: Native

UI Framework: NativeWind
NativeWind offers a seamless way to apply TailwindCSS styles in a React Native environment, which aligns with our team's familiarity with TailwindCSS on the web.


Backend Language: JavaScript/Node.js
Our team's proficiency with JavaScript and the seamless integration with React Native make Node.js an optimal choice for our backend services.

Permissions:Location Services
Essential for providing personalized weather information based on the user’s current location.

Data Storage: React Native Async Storage
Allows secure and efficient storage of user preferences and data locally on the device, promoting a better offline experience and reducing dependency on network connectivity.

Additional Frameworks/Technology Stacks: React Navigation, React Native Heroicons, React-native-progress, Weather API
These libraries and services provide essential functionality for navigation, iconography, progress indication, and weather data retrieval, respectively, with strong community support and ease of integration.

Dependencies
NativeWind: Utilized for applying TailwindCSS styles within the application.
React Navigation: React Navigation is chosen for managing the app's stack navigation strategy.
React Native Heroicons: Integration of React Native Heroicons provides a wide range of icons for a better user interface.
React-native-progress: The React-native-progress library is incorporated for visual progress indicators during data loading.
React Native Async Storage: React Native Async Storage is used for local data storage capabilities.
Weather API: The Weather API provides reliable and detailed weather data necessary for the app's core functionality.

