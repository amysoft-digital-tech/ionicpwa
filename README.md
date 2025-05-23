# Ionic PWA Application

## Overview
This project is a Progressive Web Application (PWA) built with Ionic and Angular 18. It leverages the Ionic framework for mobile-first UI components and Angular for robust application architecture. The app includes features like user authentication, data services, and a feed page, designed to work seamlessly across web and mobile platforms.

## Project Structure
- **src/app/**: Core application logic, including components, pages, and services.
  - **ui/pages/**: Contains page components like Feed and Login.
  - **services/**: Includes services for authentication and data management.
- **src/assets/**: Static assets such as icons and SVGs.
- **src/environments/**: Configuration files for different environments (development, production).
- **src/theme/**: Custom styling variables for the Ionic theme.
- **src/global.scss**: Global stylesheets importing Ionic's core CSS and utilities.
- **src/main.ts**: Entry point for the Angular application, bootstrapping the app with Ionic configurations.

## Prerequisites
- Node.js (version 18 or higher)
- Angular CLI (version 18)
- Ionic CLI (version 7 or higher)

## Installation
1. Clone the repository to your local machine.
2. Navigate to the project directory:
   ```bash
   cd ionicpwa
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application
- Start the development server:
  ```bash
  npm start
  ```
  or
  ```bash
  ionic serve
  ```
- Open your browser and navigate to `http://localhost:4200` to see the app in action.

## Building for Production
- Build the application for production:
  ```bash
  npm run build
  ```
  or
  ```bash
  ionic build --prod
  ```
- The output will be in the `www/` directory, ready for deployment as a PWA.

## Testing
- Run unit tests with Jest:
  ```bash
  npm test
  ```
- The project uses Karma for test configuration, with test files located alongside components and services.

## Features
- **Progressive Web App**: Works offline and can be installed on mobile devices.
- **Dark Mode**: Supports system-based dark mode for better user experience.
- **Authentication**: Includes a login page and authentication service.
- **Responsive Design**: Built with Ionic's mobile-first approach, ensuring compatibility across devices.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with descriptive messages.
4. Push your branch to the forked repository.
5. Open a pull request to the main repository.

## License
This project is licensed under the MIT License - see the LICENSE file for details (if applicable, or add one if needed).

## Contact
For any inquiries or issues, please open an issue on the repository or contact the project maintainers.