# Promptopia Documentation

## Introduction

Promptopia is a web application designed for sharing prompts used with ChatGPT and other AI models. Users can search for prompts, usernames, or tags. The application provides registration and login options via Google, and it stores data in a MongoDB database. Promptopia is a platform that simplifies the process of sharing and discovering prompts for AI-driven conversations.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

Promptopia offers a range of features to enhance the sharing and exploration of AI prompts:

- **Search**: Users can easily search for prompts, usernames, or tags, making it simple to discover relevant content.

- **Google Authentication**: Promptopia supports Google-based registration and login for user convenience and security.

- **Data Storage**: All prompt data is stored in a MongoDB database, ensuring scalability and data integrity.

- **User-Friendly Interface**: The web application provides an intuitive and user-friendly interface for a seamless experience.

## Getting Started

### Prerequisites

Before getting started with Promptopia, ensure you have the following prerequisites:

- Node.js and npm installed on your system.
- A MongoDB database instance to store prompt data.
- A Google API project set up to enable Google authentication.

### Installation

Follow these steps to set up Promptopia on your system:

1. Clone the repository from GitHub:

   ```bash
   git clone https://github.com/your-username/promptopia.git
   ```

2. Navigate to the project directory:

   ```bash
   cd promptopia
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Configure the application by creating a `.env` file and specifying the necessary environment variables, such as database connection details and Google API credentials.

5. Start the application:

   ```bash
   npm run start
   ```

The application will be accessible at `http://localhost:3000`.

## Usage

Promptopia is a versatile tool for sharing and discovering prompts. Here are some common use cases:

- **Sharing Prompts**: Registered users can share their prompts with the community by submitting them through the web application.

- **Searching for Prompts**: Users can search for prompts based on keywords, usernames, or tags.

- **Registering and Logging In**: New users can create accounts using Google authentication, while existing users can log in to access additional features.

- **Exploring Shared Prompts**: Users can explore and engage with prompts shared by others to enhance their AI conversations.

## Contributing

We welcome contributions to Promptopia from the open-source community. If you'd like to contribute, please follow these guidelines:

1. Fork the repository on GitHub.

2. Create a new branch for your feature or bug fix.

3. Make your changes and ensure the code follows the project's coding standards.

4. Write tests for your code if applicable.

5. Submit a pull request, providing a clear description of the changes and their purpose.

## License

Promptopia is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own projects.