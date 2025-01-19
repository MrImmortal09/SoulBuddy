
# Introduction
SoulBuddy is a web application designed to provide users with spiritual insurance services. It serves as the client-side interface for the SoulBuddy platform, allowing users to access various spiritual services, including Kundali, Horoscope, and Spiritual Content. This project is built using React and Next.js, ensuring a responsive and dynamic user experience.

## Backend

Welcome to **API Chat**, a cutting-edge Python-based chat application designed to facilitate seamless communication through a RESTful API. This project provides a robust foundation for building chat functionalities, enabling users to send and receive messages efficiently. The application leverages advanced technologies to offer a unique blend of traditional chat features and innovative astrology integration.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Deployement](#deployement)
- [License](#license)
- [Contact](#contact)

## Features

- **Message Sending**: Allows users to send messages to the chat server, ensuring efficient communication.
- **Message Retrieval**: Enables users to retrieve messages from the chat server, facilitating easy access to conversation history.
- **User Management**: Supports functionalities for user registration and authentication, ensuring a secure and personalized experience.
- **Astrology Integration**: Provides features for generating horoscopes, Advices, Recommendations, Sleep Schedules, birth charts, gemstone recommendations and much more based on user input, offering a unique and engaging experience.

## Tech Stack

- **Python**: The primary programming language used for developing the application, ensuring a robust and scalable foundation.
- **Flask**: A lightweight WSGI web application framework used for building the RESTful API, providing a flexible and modular architecture.
- **Docker**: Utilized for containerizing the application to ensure consistency across different environments, simplifying deployment and management.
- **FastAPI**: Used for building the astrology integration features, offering a fast and efficient way to handle complex calculations and data processing.
- **Groq**: Utilized for generating AI-enhanced predictions and advice, providing users with personalized insights and guidance.
- **OpenCage Geocoder**: Used for geocoding locations for astrology calculations, ensuring accurate and reliable data processing.
- **Swisseph**: Utilized for calculating planetary positions and generating birth charts, offering a comprehensive and accurate astrology integration.
- **AWS**: Hosted on AWS, ensuring high availability and scalability.

## Folder Structure

```
api-chat/
├── components/
│   ├── BirthTransit.py
│   ├── FindHoroscope.py
│   ├── Prediction.py
│   └── CurrentTransit.py
│   └── Kundli.py
├── assets/
│   ├── Images
├── Horoscope/
│   ├── Cache
├── main.py
├── gems.py
├── DockerFile
├── requirements.txt
├── LICENSE
└── README.md
```

## Getting Started

### Prerequisites

- **Python 3.x**: Ensure that Python is installed on your system, as it is the primary language used for the application.
- **Docker**: Required for containerizing and running the application, ensuring a consistent and reliable environment.

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/NeonKazuha/api-chat.git
   cd api-chat
   ```

2. **Install Dependencies**:

   It's recommended to use a virtual environment to manage dependencies, ensuring a clean and isolated environment for the application.

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. **Run the Application**:

   ```bash
   python main.py
   ```

   The application will start, and you can access the API endpoints at `http://localhost:8000`.

### Docker Setup

To run the application using Docker:

1. **Build the Docker Image**:

   ```bash
   docker build -t api-chat .
   ```

2. **Run the Docker Container**:

   ```bash
   docker run -p 8000:8000 api-chat
   ```

   The API will be accessible at `http://localhost:8000`.

   Additionally, to run the gemstone recommendations service, use the following command:

   ```bash
   docker run -p 4000:4000 api-chat-gems
   ```

   The gemstone recommendations service will be accessible at `http://localhost:4000`.

## API Endpoints

- **`POST /horoscope/`**: Endpoint to generate horoscope data, offering users personalized astrology insights.
- **`POST /gemstones/`**: Endpoint to get gemstone recommendations based on location, providing users with unique and personalized suggestions.
  
## Deployement

http://13.203.67.150:4000/gemstones

![Screenshot 2025-01-19 072527](https://github.com/user-attachments/assets/c315ca4c-42a6-4e6c-949e-3595f5f4de2c)

http://13.203.67.150/horoscope

![Screenshot 2025-01-19 072737](https://github.com/user-attachments/assets/61addf94-cf62-4155-81fe-6d9b9e12cbca)
![Screenshot 2025-01-19 072802](https://github.com/user-attachments/assets/4d5bbc3a-8006-422b-9908-da2e59e5df1a)
![Screenshot 2025-01-19 072813](https://github.com/user-attachments/assets/ade14706-4fab-4227-99af-d477d8a97188)

## Langflow
![WhatsApp Image 2025-01-19 at 10 35 26_ed736962](https://github.com/user-attachments/assets/3f8149df-b6c2-4db9-a599-c5e5399d401c)
![WhatsApp Image 2025-01-19 at 10 35 56_d4ba9d28](https://github.com/user-attachments/assets/d34d73ad-b0e2-410e-80b5-6ba4219ba28c)
![WhatsApp Image 2025-01-19 at 10 36 29_83052ebd](https://github.com/user-attachments/assets/c360206a-ecaf-4c9c-9879-07b5f7608872)


# Frontend

## Description
SoulBuddy is a web application designed to provide users with spiritual insurance services. It serves as the client-side interface for the SoulBuddy platform, allowing users to access various spiritual services, including Kundali, Horoscope, and Spiritual Content. This project is built using React and Next.js, ensuring a responsive and dynamic user experience.

## Features
- **User-Friendly Interface**: Intuitive navigation and layout for easy access to services.
- **Dynamic Content**: Fetches and displays real-time data from the backend.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Interactive Components**: Utilizes Framer Motion for smooth animations and transitions.
- **State Management**: Efficiently manages application state with React hooks.

## Installation

### Prerequisites   
- Node.js (version 14 or higher)
- npm (Node Package Manager)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/MrImmortal09/soul-frontend.git
   cd soul-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:8000`.

## Interface
![IMG-20250119-WA0046](https://github.com/user-attachments/assets/dd65941b-a1c0-4fdf-883c-046749a26e4d)
![IMG-20250119-WA0047](https://github.com/user-attachments/assets/53721a8f-3c0b-4ed7-92ed-1a3b142ae56c)
![IMG-20250119-WA0048](https://github.com/user-attachments/assets/86e5a991-6652-42ac-92a1-1e4abd2795b3)
![IMG-20250119-WA0049](https://github.com/user-attachments/assets/b2f9ddb4-9b62-44b9-893f-8a4e0e6c5968)
![WhatsApp Image 2025-01-19 at 10 22 02_9d460cb4](https://github.com/user-attachments/assets/31bf3493-872b-438d-8b4c-048c72246550)

![IMG-20250119-WA0050](https://github.com/user-attachments/assets/77f034fc-6779-4f5a-9bea-e6e89475418a)
![IMG-20250119-WA0051](https://github.com/user-attachments/assets/923e6d5f-58d1-43ae-8e7c-522ee2761b83)
![IMG-20250119-WA0052](https://github.com/user-attachments/assets/bb7c14fc-0dba-4ce9-ad71-cbab61eb339e)



## Usage
- Navigate through the app to explore the services.
- Receive personalized spiritual insights through forms.

## License
This project is licensed under the MIT License.

## Contact
For more details, refer to the GitHub Repository.
