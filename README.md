# Implement-Login-and-Logout-with-Auth0-SDK

This project demonstrates how to integrate Auth0 authentication with a Python Flask application using the Authlib SDK. It provides secure login and logout functionalities, allowing users to authenticate using Auth0 and gain access to user profile information.

## 🚀 Getting Started

To get started with this project, follow the instructions below to set up and run the Flask application with Auth0 authentication.

### 📋 Prerequisites

- Python 3.x installed on your system
- An [Auth0](https://auth0.com/) account
- Basic knowledge of Python and Flask

### ⚙️ Setup and Configuration

1. **Configure Auth0:**
   - Sign in to your Auth0 account and create a new application or select an existing one.
   - Configure the following settings for your application:
     - **Callback URL:** `http://localhost:3000/callback`
     - **Logout URL:** `http://localhost:3000`
   - Obtain your **Client ID**, **Client Secret**, and **Domain** from the Auth0 Dashboard.

2. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

3. **Create a .env file:**

    - Create a .env file in the root directory of your project and add the following environment variables:
        
        ```bash
        AUTH0_CLIENT_ID=yourClientId
        AUTH0_CLIENT_SECRET=yourClientSecret
        AUTH0_DOMAIN=yourDomain
        APP_SECRET_KEY=yourAppSecretKey
        ```

    **Note:** Replace yourClientId, yourClientSecret, yourDomain, and yourAppSecretKey with your actual values. You can generate APP_SECRET_KEY using openssl rand -hex 32.

4. **Install Dependencies:**

    - Run the following command to install the required dependencies:
        
        ```
        pip install -r requirements.txt
        ```

### Run the Application

1. **Run the Flask Application:**

    - Execute the following command to start your Flask application:

        ```
        python3 server.py
        ```

2. **Access the Application:**

    - Open your web browser and navigate to http://localhost:3000 to see your application in action.



