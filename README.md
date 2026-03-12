# AI RPG Assistant

## Overview
The AI RPG Assistant is a comprehensive tool designed to enhance the experience of role-playing games (RPGs) by leveraging advanced AI capabilities. Built with Spring Boot, this application integrates large language model (LLM) retrieval-augmented generation (RAG) functionalities to provide real-time assistance during gameplay.

## Features
- **Interactive Game Assistance**: Provides suggestions and information relevant to ongoing gameplay.
- **Character Creation Tools**: Assists users in developing unique characters with various attributes.
- **World-Building Resources**: Offers tools and templates for creating immersive game worlds.
- **Quest Management**: Helps track and manage quests and storylines.
- **Rule Reference**: Quick access to rules and mechanics of various RPG systems.

## Technology Stack
- **Backend**: Spring Boot
- **AI Model**: Large Language Model with RAG capabilities
- **Database**: PostgreSQL or any preferred database
- **Frontend**: Can be integrated with any JS framework (React, Angular, etc.) for a complete user interface.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Jblast94/rpg-maker-assistant.git
   cd rpg-maker-assistant
   ```
2. Ensure you have JDK 11+ and Maven installed.
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```

## Usage
- Access the application at `http://localhost:8080` in your web browser. 
- Follow the on-screen instructions to use the various features of the AI RPG Assistant.

## Docker Deployment
1. Build the Docker image:
   ```bash
   docker build -t ai-rpg-assistant .
   ```
2. Run the Docker container:
   ```bash
   docker run -p 8080:8080 ai-rpg-assistant
   ```
3. Access the application at `http://localhost:8080`.

## Contributing
We welcome contributions from the community! Here’s how you can help:
- **Report Bugs**: Open an issue on GitHub.
- **Feature Requests**: Suggest new features via issues.
- **Pull Requests**: Feel free to submit a pull request for any enhancements or bug fixes. Make sure to follow the coding standards.

For more details, refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file in the repository.