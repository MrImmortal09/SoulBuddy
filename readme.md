# SoulBuddy

Welcome to **SoulBuddy**, a comprehensive platform designed to provide users with spiritual insurance services. This project encompasses both backend and frontend components, offering a holistic approach to spiritual well-being. The platform is built using cutting-edge technologies, ensuring a seamless and engaging user experience.

## Table of Contents

- [SoulBuddy Introduction](#soulbuddy-introduction)
- [Backend](#backend)
- [Frontend](#frontend)
- [License](#license)
- [Contact](#contact)

## SoulBuddy Introduction

SoulBuddy is a web application designed to provide users with spiritual insurance services. It serves as the client-side interface for the SoulBuddy platform, allowing users to access various spiritual services, including Kundali, Horoscope, and Spiritual Content. This project is built using React and Next.js, ensuring a responsive and dynamic user experience.

## Backend

### ALL ACTIVE APIs DEPLOYED ON AWS WITH THE HELP OF DOCKER.

### API Chat

Welcome to **API Chat**, a cutting-edge Python-based chat application designed to facilitate seamless communication through a RESTful API. This project provides a robust foundation for building chat functionalities, enabling users to send and receive messages efficiently. The application leverages advanced technologies to offer a unique blend of traditional chat features and innovative astrology integration.

#### Features

- **Message Sending**: Allows users to send messages to the chat server, ensuring efficient communication.
- **Message Retrieval**: Enables users to retrieve messages from the chat server, facilitating easy access to conversation history.
- **User Management**: Supports functionalities for user registration and authentication, ensuring a secure and personalized experience.
- **Astrology Integration**: Provides features for generating horoscopes, Advices, Recommendations, Sleep Schedules, birth charts, gemstone recommendations and much more based on user input, offering a unique and engaging experience.

#### Tech Stack

- **Python**: The primary programming language used for developing the application, ensuring a robust and scalable foundation.
- **Flask**: A lightweight WSGI web application framework used for building the RESTful API, providing a flexible and modular architecture.
- **Docker**: Utilized for containerizing the application to ensure consistency across different environments, simplifying deployment and management.
- **FastAPI**: Used for building the astrology integration features, offering a fast and efficient way to handle complex calculations and data processing.
- **Groq**: Utilized for generating AI-enhanced predictions and advice, providing users with personalized insights and guidance.
- **OpenCage Geocoder**: Used for geocoding locations for astrology calculations, ensuring accurate and reliable data processing.
- **Swisseph**: Utilized for calculating planetary positions and generating birth charts, offering a comprehensive and accurate astrology integration.
- **AWS**: Hosted on AWS, ensuring high availability and scalability.

#### Folder Structure

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

#### Getting Started

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

### Langflow

![WhatsApp Image 2025-01-19 at 10 35 26_ed736962](https://github.com/user-attachments/assets/7e5ff80d-230e-4bdf-ae9a-3b5ebdbbe786)

![WhatsApp Image 2025-01-19 at 10 35 56_d4ba9d28](https://github.com/user-attachments/assets/64cbe681-eeaf-43a4-a999-4526bff5210e)

![WhatsApp Image 2025-01-19 at 10 36 29_83052ebd](https://github.com/user-attachments/assets/a4212fd5-bccc-4c76-8a34-0c585831eed5)


## Frontend

### Description
SoulBuddy is a web application designed to provide users with spiritual insurance services. It serves as the client-side interface for the SoulBuddy platform, allowing users to access various spiritual services, including Kundali, Horoscope, and Spiritual Content. This project is built using React and Next.js, ensuring a responsive and dynamic user experience.

### Features
- **User-Friendly Interface**: Intuitive navigation and layout for easy access to services.
- **Dynamic Content**: Fetches and displays real-time data from the backend.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Interactive Components**: Utilizes Framer Motion for smooth animations and transitions.
- **State Management**: Efficiently manages application state with React hooks.

### Installation

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

### Usage
- Navigate through the app to explore the services.
- Receive personalized spiritual insights through forms.

## License
This project is licensed under the MIT License.

## Contact
For more details, refer to the GitHub Repository.
