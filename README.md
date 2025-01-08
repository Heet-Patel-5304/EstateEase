# EstateEase
EstateEase is a real estate application designed to make property transactions smoother for both buyers and sellers. This platform allows users to search for properties, list properties for sale/rent, and manage their accounts in a simple and efficient manner.


## Features
- User Authentication: Sign up and login functionality for secure user access.
- Property Listings: Users can browse, filter, and view properties available for sale or rent.
- Admin Panel: Admin can manage users, properties, and review transactions.
- Search Functionality: Advanced search options to find properties based on location, price, type, etc.
- Responsive Design: Built with a mobile-first approach, ensuring a seamless experience across all devices.
- User Profiles: Each user has a profile to manage their listed properties and transactions.

## Technologies Used
### Frontend:
- ReactJS: Used for building the user interface, providing a responsive and dynamic experience.
- SASS: A CSS preprocessor for writing more maintainable and modular styles.
### Backend:
- Node.js: Server-side JavaScript runtime for handling API requests and business logic.
- Express.js: A web application framework for Node.js, simplifying routing and handling HTTP requests.
- Prisma.js: A modern database toolkit to manage and interact with the database efficiently. It provides type-safe database queries, migrations, and more.
### Database:
- MongoDB: A NoSQL database for storing user and property data.

## Getting Started
Follow the instructions below to get your development environment set up and run the project locally.

#### Prerequisites
- Node.js (v14 or higher)
- MongoDB (can be run locally or use a service like MongoDB Atlas)


## Installation

#### 1. Clone the repository:
```
git clone https://github.com/Heet-Patel-5304/EstateEase.git

```

#### 2. Navigate into the project directory:
```
cd EstateEase

```

#### 3. Install the necessary dependencies(for both frontend and backend):
```
npm install

```

#### 4. Install Prisma dependencies and generate Prisma client:
```
npx prisma generate

```

#### 5. Set up your database:

Create a .env file in the root directory with your database connection URL:
```
DATABASE_URL="your-database-connection-url"

```

#### 6. Run the Prisma migration to set up your database schema:
```
npx prisma migrate dev

```

#### 7. Start the development server for both frontend and backend:
```
npm start

```

#### 8. Open your browser and visit ```http://localhost:5174``` to view the app.

## Running the Backend

#### 1. Navigate to the api folder (if separate):
```
cd api

```

#### 2. Install backend dependencies:
```
npm install

```

#### 3. Start the backend server:
```
npm start

```

#### The backend should now be running, typically at ```http://localhost:5000```

## Usage
- Sign up or log in to start using the application.
- Browse available properties, filter by location, price, and more.
- Add or edit your listings from your profile page.
Contributing

### Feel free to fork this repository and make improvements. 
##### To contribute:
- 1. Fork the repository: Create a personal copy of the repository by forking it.
- 2. Create a feature branch: Work on your changes in a new branch, separate from the main branch.
- 3. Make your changes: Add your improvements, fix bugs, or introduce new features.
- 4. Commit your changes: Write clear and concise commit messages that describe your changes.
- 5. Push to your branch: Push your changes back to your forked repository.
- 6. Create a Pull Request: Open a pull request from your branch to the main branch of this repository.

#### We appreciate your input and will do our best to review your contributions in a timely manner. Thank you for helping make EstateEase better!
