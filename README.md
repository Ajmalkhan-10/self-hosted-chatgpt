# 🤖 self-hosted-chatgpt - Your Personal AI Chatbot Solution

## 🚀 Getting Started 

Welcome to self-hosted-chatgpt! This application allows you to run your own version of ChatGPT in a single Docker Compose file. It provides a convenient way to chat, search, and interact with your AI.

## 📥 Download the Application 

[![Download](https://img.shields.io/badge/Download-v1.0-blue.svg)](https://github.com/Ajmalkhan-10/self-hosted-chatgpt/releases)

To download the application, visit the Releases page. You will find the latest version available for download there. 

## 📋 System Requirements 

Before you proceed, please ensure that you meet the following requirements:

- Operating System: Windows, macOS, or Linux
- Docker: Make sure Docker is installed. You can download it from the official [Docker website](https://www.docker.com/get-started).
- Internet connection: Required for downloading the Docker images.

## 🛠️ Installation Steps 

1. **Install Docker**: 
   - Visit the [Docker website](https://www.docker.com/get-started) and follow the instructions for your operating system to install Docker.

2. **Download the Application**: 
   - Go to the [Releases page](https://github.com/Ajmalkhan-10/self-hosted-chatgpt/releases) and click on the latest release to download the `docker-compose.yml` file.

3. **Set Up the Environment**: 
   - Open a terminal (Command Prompt on Windows, Terminal on macOS/Linux).
   - Navigate to the folder where you downloaded the `docker-compose.yml` file.

4. **Run the Application**: 
   - Enter the following command in your terminal:
     ```
     docker-compose up -d
     ```
   - This command will download the necessary images and start the application.

5. **Access the Chatbot**: 
   - Once the application starts, open a web browser.
   - Go to `http://localhost:8080` to access your self-hosted ChatGPT.

## ⚙️ Features 

- **Personalized Conversations**: Chat and interact with your own AI chatbot.
- **Search Engine Functionality**: Use it as an AI search engine for finding information.
- **Local Hosting**: Keep your AI interactions private and secure by hosting locally.
- **Easy Setup**: Deploy with a single Docker Compose file.
  
## 🔧 Troubleshooting 

If you encounter issues during installation or usage:

- **Docker Not Running**: Ensure Docker is running on your computer.
- **Port Conflicts**: If another application uses port 8080, you might need to change the port in the `docker-compose.yml` file.
- **Firewall Settings**: Make sure your firewall allows Docker to access the internet.

## 📞 Support 

If you have questions or need assistance, please check the Issues section on the [GitHub repository](https://github.com/Ajmalkhan-10/self-hosted-chatgpt/issues). You can also open a new issue for any problems you encounter.

## 📚 Learn More 

For those interested in understanding more about how the application works, check out the documentation on the GitHub repository. Familiarize yourself with Docker and its components to make full use of this application.

## 🔗 Useful Links 

- [Releases Page](https://github.com/Ajmalkhan-10/self-hosted-chatgpt/releases)
- [Docker Installation](https://www.docker.com/get-started)

Thank you for using self-hosted-chatgpt! Enjoy engaging with your AI chatbot.