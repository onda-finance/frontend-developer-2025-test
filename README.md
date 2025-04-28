
📱 React Native Front-End Developer Test - Onda Finance

Objective:
Create a single-screen mobile app using React Native and NativeWind that replicates a basic version of the XE.com app style (see XE Benchmark here).

Requirements:
1. Design:
* Match the clean style of the https://XE.com app (minimalist, professional, mobile-first).
* Layout:
    * Top Section: Marketing Card (image background, title, and description).
    * Bottom Section: Scrollable horizontal Currency Cards.
2. Features:
* Marketing Card (Top):
    * Full-width card with:
        * Background Image.
        * Dark overlay (to ensure text readability without text opacity blending with the image).
        * Title (e.g., "Stay Ahead with Live Rates").
        * Description (e.g., "Get the most updated currency quotations in real-time.").
* Currency Cards (Bottom):
    * Fetch and display different currency rates (e.g., USD, EUR, GBP, ARS, etc.).
    * Each card should take about half the screen width and scroll horizontally.
    * Show:
        * Currency name (e.g., "USD - US Dollar").
        * Exchange rate compared to BRL.
        * Last update time (optional for extra points).
    * API to use: 👉 AwesomeAPI - Moedas (https://docs.awesomeapi.com.br/api-de-moedas)

Technical Requirements:
* Framework: React Native
* Styling: NativeWind (TailwindCSS for React Native) (https://nativewindui.com/)
* Data: AwesomeAPI (REST API) (https://docs.awesomeapi.com.br/api-de-moedas) 
* Responsiveness: Focus on mobile usability.

Bonus Points (Optional):
* Skeleton Loading when fetching the rates.
* Error Handling if API fails.
* Pretty Animation on card scroll.

Submission:
* Deliver the project as a GitHub repository.
* Include a simple README explaining how to run it locally.

Notes:
* Keep it simple, clean, and professional.
* Focus on code quality, UI/UX, and good practices.
