# World Cities and Countries Management

An Angular application for managing cities and countries. This application provides functionalities to view, add, edit, and delete cities and countries. It includes components for listing and editing cities and countries and uses Angular's Reactive Forms for handling form data.
API:https://github.com/SayedImtiaj/WorldCitiesAPI.git
## Features

- **City Management:** Add, edit, and delete cities. View cities and their associated countries.
- **Country Management:** Add, edit, and delete countries. View a list of countries.
- **Reactive Forms:** Utilizes Angular's Reactive Forms for managing form inputs and validations.
- **REST API Integration:** Interacts with REST APIs for fetching, creating, updating, and deleting data.

## Project Structure

- **`src/app/city-list/city-list.component.ts`**: Manages and displays a list of cities. Includes functionality for adding, editing, and deleting cities.
- **`src/app/country-list/country-list.component.ts`**: Manages and displays a list of countries. Includes functionality for adding, editing, and deleting countries.
- **`src/app/services/city.service.ts`**: Service for interacting with the cities API.
- **`src/app/services/country.service.ts`**: Service for interacting with the countries API.
- **`src/app/models/city.ts`**: TypeScript model for city data.
- **`src/app/models/country.ts`**: TypeScript model for country data.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/world-cities-countries-management.git
   cd world-cities-countries-management
