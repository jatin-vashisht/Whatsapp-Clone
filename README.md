# WhatsApp Clone App

A real-time communication app inspired by WhatsApp, featuring voice and video calling, media sharing, and message notifications.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the WhatsApp Clone App – a modern, real-time communication platform designed to offer a seamless and feature-rich experience for users. Inspired by the popular messaging application, this project incorporates essential functionalities such as real-time voice and video calling, media sharing, and message notifications.

Whether you're looking to stay connected with friends, family, or colleagues, our app provides a familiar environment with enhanced features for a more engaging communication experience. Built using cutting-edge technologies, the WhatsApp Clone App brings together the power of Node.js, Express, Socket.IO, React, Next.js, and more, ensuring reliability and scalability.

Feel free to explore the app, contribute to its development, and make it your own. The comprehensive documentation below will guide you through installation, usage, and customization. Dive in and start building meaningful connections with the WhatsApp Clone App!


## Features

1. **Real-time Communication:**
   - Engage in instant messaging with real-time updates for a seamless communication experience.

2. **Voice and Video Calling:**
   - Make high-quality voice and video calls to stay connected with friends and family.

3. **Emojis and Stickers:**
   - Express yourself with a diverse range of emojis and stickers to add fun and emotion to your messages.

4. **Search Functionality:**
   - Quickly find messages, contacts, or media with a powerful search feature.

5. **Message Encryption:**
    - Ensure the privacy and security of your conversations with end-to-end encryption.

6. **Integration with Cloud Services:**
    - Sync messages, media, and settings across multiple devices using cloud services.

## Technologies Used

### Backend

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Prisma](https://www.prisma.io/)
- [Socket.IO](https://socket.io/)

### Frontend

- [React](https://reactjs.org/)
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Firebase](https://firebase.google.com/)
- [Zego Express Engine WebRTC](https://doc-en.zego.im/en/3268.html)


## Getting Started

1. Clone the repository.
   ```bash
   git clone https://github.com/your-username/whatsapp-clone.git
   cd whatsapp-clone
    ```
2. Install client dependencies.
    ```bash
    cd client
    npm i
    ```
3. Install server dependencies.
    ```bash
    cd server
    npm i
    ```
4. Setup client .env variables in 'next.config.js'
    ```
    NEXT_PUBLIC_ZEGO_APP_ID: ########,
    NEXT_PUBLIC_ZEGO_SERVER_ID: "######################",
    ```
5. Setup server .env variables in '.env'
    ```
    DATABASE_URL="MONGO_URI"
    PORT=3005
    ZEGO_APP_ID: ########
    ZEGO_SERVER_ID: "#####################"
    CLIENT_HOST='http://localhost:3000'
    ```
6. Start client
    ```
    npm run dev
    ```
7. Start server
    ```
    npm start
    ```

## Preview

![Login Page](https://firebasestorage.googleapis.com/v0/b/disney-plus-hotstar-clon-13914.appspot.com/o/images%2FScreenshot%20(3).png?alt=media&token=900d1be4-c2a5-45ca-9658-aaadcbb2a38a)
*Login Screen.*

![Screenshot 2](https://firebasestorage.googleapis.com/v0/b/disney-plus-hotstar-clon-13914.appspot.com/o/images%2FScreenshot%20(4).png?alt=media&token=9751104f-12ce-491f-bb83-f394e6c95c57)
*Chat Window.*

## Contributing

We welcome contributions from the community! If you're interested in contributing to the development of the WhatsApp Clone App, please follow these guidelines:

1. Fork the repository and create a new branch for your contribution.
2. Make your changes and ensure that the code is well-documented.
3. Test your changes thoroughly to ensure they don't introduce new issues.
4. Commit your changes and create a clear, concise pull request.
5. Provide a detailed description of the changes and why they are necessary.

### Code Style

Please follow the coding style and conventions used in the project. If there's uncertainty, refer to existing code for guidance.

### Bug Reports and Feature Requests

If you find any bugs or have suggestions for new features, please open an issue on the [Issues](https://github.com/jatin-vashisht/Whatsapp-Clone.git/issues) page.

### Community Guidelines

Be respectful and inclusive when participating in discussions. We encourage open communication and collaboration.

Thank you for contributing to the WhatsApp Clone App!

## License

This project is licensed under the [MIT License](LICENSE).
