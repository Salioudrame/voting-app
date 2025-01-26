# Voting App

## Overview

This project is a simple voting application that allows users to vote on various topics. It is built using modern web technologies and follows best practices for DevOps.

## Features

- User authentication
- Create and manage polls
- Vote on polls
- View poll results in real-time

## Technologies Used

- Frontend: React
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT
- Containerization: Docker
- CI/CD: GitHub Actions

### Prerequisites

- Docker
- Docker Compose

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/voting-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd voting-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add the following variables:
     ```
     MONGO_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     ```

## Running the Application

1. **Start the Docker Compose Services**:

   - Ensure Docker is running on your machine.
   - Navigate to the directory containing your `compose.yaml` file.
   - Run the following command to start all the services:

     ```sh
     docker-compose up -d
     ```

2. **Access the Voting App**:

   - Open your web browser and navigate to `http://localhost:5000` to access the voting application.

3. **Access the Result App**:
   - Open your web browser and navigate to `http://localhost:5001` to view the poll results.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
