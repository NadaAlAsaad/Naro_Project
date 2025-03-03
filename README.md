NARO - Daily Dose of Inspiration
NARO is an interactive web project designed to uplift users with a daily dose of humor and inspiration. The site fetches random jokes and fun quotes from external APIs, allowing users to enjoy and even save their favorite bits of inspiration.

Features
Responsive Design: Built with Bootstrap 5, ensuring the site looks great on any device.
Random Jokes and Fun Quotes: Utilizes third-party APIs to fetch fresh, humorous content.
Local Storage: Users can save their favorite jokes and quotes for later viewing.
Preloader Animation: A preloader is displayed until the page resources are fully loaded.
Interactive Navigation: A fixed navbar that provides quick access to different sections of the site.
User-Friendly Interface: Clean layout with custom styling and engaging typography using Google Fonts.
Technologies Used
HTML5 & CSS3: Structure and styling of the web pages.
JavaScript (ES6): Interactivity, API fetching, and local storage management.
Bootstrap 5: Responsive design and layout components.
Google Fonts:
Henny Penny for a playful look.
Arsenal SC for bold and elegant text styles.
APIs:
JokeAPI for fetching random jokes.
Chuck Norris API for fun and quirky quotes.
Installation & Setup
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/naro-daily-dose.git
Navigate to the Project Directory:

bash
Copy
Edit
cd naro-daily-dose
Open the Project:

Since this is a static website, simply open the index.html (or any other HTML file) in your preferred web browser. No additional server setup is required.

How to Use
Homepage: The site loads with a preloader and a fixed navigation bar. The main page welcomes you with a heading and provides access to the content sections.
Jokes Section:
Click the "Get a Joke" button to fetch a random joke.
Use the "Save Joke" button to store your favorite joke locally.
Use the "Show Saved Joke" button to display your saved joke.
Fun Quotes Section:
Click the "Get a Fun Quote" button to fetch a random fun quote.
Use the "Save Quote" button to store your favorite quote.
Use the "Show Saved Quote" button to display your saved quote.
Navigation: Use the navbar links to switch between Home, About Us, and Naro pages.
Preloader: A preloader is visible until the page has fully loaded.
Customization
Styling: Modify the CSS within the <style> tags to change colors, fonts, or layout.
API Endpoints: If desired, replace the current API endpoints in the JavaScript functions with other services.
Local Storage: The current implementation uses the browser's local storage for saving favorites. This can be expanded or integrated with a backend for more persistent storage.
Future Improvements
Backend Integration: Implement a server-side component for handling contact form submissions and user data.
User Authentication: Allow users to create accounts and securely manage their saved favorites.
Enhanced Content: Add more content types (e.g., inspirational images, videos) and expand API support.
UI/UX Enhancements: Refine the design and add animations for a more engaging user experience.

Acknowledgements
Thanks to the JokeAPI and Chuck Norris API for providing the humorous content.
Special thanks to Bootstrap for the responsive framework.
Google Fonts for the beautiful typography.
