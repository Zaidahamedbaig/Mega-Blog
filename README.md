MegaBlog

MegaBlog is a modern blog application built with React and Vite, offering a seamless and efficient blogging experience.

Features

Rich Text Editor: Powered by TinyMCE for comprehensive text formatting options.

State Management: Uses Redux Toolkit for efficient state management.

Routing: Implemented with React Router for smooth navigation.

Form Handling: Integrated with React Hook Form for effortless form validation and submission.

Backend Support: Utilizes Appwrite for backend services, including authentication, database, and storage.

Installation

Prerequisites

Node.js (v16 or later)

npm or yarn

Steps

Clone the repository:

git clone <repository-url>
cd megablog

Install dependencies:

npm install

Configure environment variables:

Create a .env file in the root directory and set the following variables:

VITE_APPWRITE_URL="https://cloud.appwrite.io/v1"
VITE_APPWRITE_PROJECT_ID=""
VITE_APPWRITE_DATABASE_ID=""
VITE_APPWRITE_COLLECTION_ID=""
VITE_APPWRITE_BUCKET_ID=""

Start the development server:

npm run dev

Scripts

npm run dev: Starts the development server.

npm run build: Builds the project for production.

npm run lint: Lints the project files using ESLint.

npm run preview: Previews the production build.

Project Structure

index.html: Entry point of the application.

vite.config.js: Configuration for Vite.

.env: Environment variables configuration.

eslint.config.js: ESLint configuration file.

package.json: Project dependencies and scripts.

Technologies Used

Frontend

React

Redux Toolkit

React Router DOM

React Hook Form

Development Tools

Vite

ESLint

Tailwind CSS

Backend

Appwrite

License

This project is licensed under the MIT License. See the LICENSE file for details.

