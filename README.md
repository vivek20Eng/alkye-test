# Alkye Test Web Application

## Project Overview

This project is a multi-page web application developed as part of the Alkye Test assignment. It demonstrates the ability to create a responsive web application with a sign-up process and a dashboard, integrating with provided API endpoints.

### Key Features

- Two-step sign-up process
- User authentication
- Dashboard displaying articles fetched from an API
- Responsive design adhering to provided Figma specifications

## Technologies Used

- React
- Next.js
- Axios for API requests
- Tailwind CSS for styling (to be implemented)

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

## Setup and Installation

1. Clone the repository:

git clone [repository-url]
cd alkye-test
2. Install dependencies:

3. Create a `.env.local` file in the root directory and add any necessary environment variables:

3. Create a `.env.local` file in the root directory and add any necessary environment variables:

4. Run the development server:

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Project Structure

- `/pages`: Contains the main pages of the application
- `/components`: Reusable React components
- `/lib`: Utility functions and API calls
- `/context`: React context for state management
- `/styles`: Global styles and Tailwind CSS configuration
- `/public`: Static assets

## API Integration

The application integrates with the following API endpoints:

- Login: `POST /api/login/`
- Get Customer List: `GET /api/customer-list/`
- Get Articles: `GET /api`

Refer to the API documentation for more details on request/response formats.

## Deployment

The application can be deployed using Vercel or any other Next.js-compatible hosting platform.

To build the application for production:

npm run build

## Testing

(To be implemented)

Run tests with:

npm test
## Performance Considerations

- The application aims for a page load speed of less than 500ms.
- Image optimization is implemented using Next.js Image component.
- Server-side rendering is utilized where appropriate for improved initial load times.

## Responsive Design

The application is designed to be fully responsive, adhering to the layouts specified in the Figma design across various device sizes.

## Contributing

This project is part of an assignment and is not open for external contributions.

## License

This project is private and not licensed for public use or distribution.

## Contact

vivekanandans2017@gmail.com