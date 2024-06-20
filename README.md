# Nodemailer Project

This project demonstrates how to use Nodemailer to send emails using a Gmail SMTP server in a Node.js application.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have Node.js and npm installed on your machine.
- You have a Gmail account.
- You have set up your Gmail account to allow less secure apps or created an App Password if you have 2-Step Verification enabled.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/vpopz/Nodemailer.git
    cd nodemailer-project
    ```

2. Install the dependencies:

    ```bash
    npm install dotenv nodemailer
    ```

3. Create a `.env` file in the root of the project and add your email and password:

    ```env
    EMAIL=your-email@gmail.com
    PASSWORD=your-password-or-app-password
    ```

## Usage

1. Open `nodeMailer.js` and configure your email settings in the `transporter` object.

2. Run the script:

    ```bash
    nodeMailer.js
    ```

