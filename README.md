🍽️ Yumi - AI Powered Restaurant Management System
(100 Lessons API Project Bootcamp)
This project was developed as part of Murat Yücedağ's "100 Lessons API Project Bootcamp" series on YouTube. It is a comprehensive restaurant management system starting from core API fundamentals and evolving into advanced AI integrations.

🚀 Project Overview
The project is built on a fully API-driven architecture. It consists of two main layers:

API Layer: The backend where data is processed, secured, and served.

UI Layer: A modern, dynamic web interface where the APIs are consumed to deliver a seamless user experience.

💡 Key Features

Fully Dynamic Content: Menus, chefs, statistics, and testimonials are managed entirely through the database via API endpoints.
Reservation System: A sophisticated "Book A Table" module that allows users to make online reservations.
Admin Dashboard: A robust management interface to control categories, products, reservations, and incoming messages.
AI Integration: Leveraging OpenRouter to integrate OpenAI, Claude, and Hugging Face models for:
Toxic comment detection and spam filtering.
Smart recipe suggestions based on available ingredients.
Automated message replying and AI-powered assistant features.

🛠️ Tech Stack

Backend: ASP.NET Core API (Stable version: 6.0/8.0)
Frontend: ASP.NET Core MVC (API Consumer)
Database: MSSQL Server
ORM: Entity Framework Core (Code First Approach)
Tools: Swagger (API Documentation), Postman, SignalR (Real-time updates)
AI Services: OpenRouter API (Accessing OpenAI, Claude, and Hugging Face models)

⚙️ Installation and Setup

Follow these steps to get the project running on your local machine:
Clone the Repo: git clone https://github.com/yourusername/reponame.git
Database Update: Open the Package Manager Console and run the Update-Database command to generate the MSSQL database.
API Configuration: Update the Connection String in the appsettings.json file to match your local SQL Server settings.

🔑 Critical Step: AI Configuration:

The AI features (recipe suggestions, automated replies, etc.) require an OpenRouter API Key.
You must obtain your own API key from OpenRouter.
Add your API key to the relevant service or settings file in the application. The AI modules will not function without a valid key.


