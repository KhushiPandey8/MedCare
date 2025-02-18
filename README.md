# MedCare 💉

MedCare is your go-to healthcare appointment scheduler! Effortlessly book doctor consultations, manage patient records, and receive timely reminders, all through an intuitive and user-friendly interface. Simplifying healthcare, one appointment at a time!

## Features 🚀
- **Seamless Appointment Booking** 📅 – Easily schedule consultations with doctors.
- **Patient Records Management** 🏥 – Securely store and manage patient history.
- **Timely Reminders** ⏰ – Get SMS notifications using Twilio.
- **Intuitive UI** 🎨 – Built with Next.js and Tailwind CSS for a smooth experience.
- **Secure Backend** 🔐 – Powered by Appwrite for authentication and database management.

## Tech Stack 🛠
### Frontend:
- Next.js
- Tailwind CSS

### Backend:
- Appwrite (Authentication & Database)
- Twilio (SMS Reminders)

## Installation 🔧
### Prerequisites:
Ensure you have **Node.js** and **npm** installed.

### Clone the Repository:
```sh
git clone https://github.com/KhushiPandey8/medcare.git
cd medcare
```

### Install Dependencies:
```sh
npm install
```

### Set Up Environment Variables:
Create a `.env.local` file and add the following:
```sh
NEXT_PUBLIC_APPWRITE_ENDPOINT=your-appwrite-endpoint
NEXT_PUBLIC_APPWRITE_PROJECT_ID=your-appwrite-project-id
TWILIO_ACCOUNT_SID=your-twilio-account-sid
TWILIO_AUTH_TOKEN=your-twilio-auth-token
TWILIO_PHONE_NUMBER=your-twilio-phone-number
```

### Run the Application:
```sh
npm run dev
```
The app will be available at `http://localhost:3000`.

## Deployment 🌍
This project can be deployed on **Vercel**:
1. Push your repository to GitHub.
2. Connect your GitHub repo to **Vercel**.
3. Set up the environment variables on **Vercel Dashboard**.
4. Deploy and enjoy!

## Contributing 🤝
We welcome contributions! Follow these steps to contribute:
1. **Fork** the repository.
2. **Create a branch** for your feature: `git checkout -b feature-name`.
3. **Commit your changes**: `git commit -m "Added new feature"`.
4. **Push to the branch**: `git push origin feature-name`.
5. Open a **Pull Request**.

### Contribution Path:
- **Frontend**: `pages/`, `components/`
- **Backend**: `server/`
- **Twilio Integrations**: `utils/twilio.js`
- **UI Improvements**: `styles/`

## License 📜
This project is licensed under the **ISC License**.

## Author ✨
Developed by **Khushi Pandey**.
Updated file with new changes

Co-authored-by: Princy Mishra <pam346408@gmail.com>
---
Feel free to contribute and improve MedCare! 🚑Addeed content in readme.md
