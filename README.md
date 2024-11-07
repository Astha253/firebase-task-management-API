# Firebase Task Management API with Real-Time Notifications

This project is a **backend system for task management** that uses **Firebase Firestore** as the database and **Firebase Cloud Functions** to send real-time notifications via **Firebase Cloud Messaging (FCM)**. Users receive notifications when tasks are created or updated, and they can manage their own tasks once authenticated.

## Features

- **Task Management**: Users can create, view, update, and delete tasks.
- **Real-Time Notifications**: Users receive notifications on task creation and status updates (e.g., "completed").
- **Firebase Authentication**: Users must be logged in to access and modify tasks.
- **Cloud Functions**: Functions handle notifications and real-time updates on task changes.
- **Firestore Database**: Used to store tasks, each with fields like title, description, status (pending/completed), and due date.

## Technologies Used

- **Node.js** for backend development
- **Firebase Firestore** for storing tasks
- **Firebase Cloud Functions** for serverless functions
- **Firebase Cloud Messaging (FCM)** for sending notifications
- **Firebase Authentication** for user authentication

## Prerequisites

- Node.js installed
- Firebase CLI installed (`npm install -g firebase-tools`)
- Firebase project set up on [Firebase Console](https://console.firebase.google.com/)

## Project Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/firebase-task-manager.git
   cd firebase-task-manager

   
Here’s the complete guide in Markdown format, ready for copy-pasting into your README or any other document:

markdown
Copy code
# Firebase Task Management API Project Setup Guide

This guide will walk you through setting up your Firebase Task Management API project, writing a `README.md` file, and uploading the project to GitHub.

---

## 1. Initialize Git in Your Project Folder

Open a terminal or command prompt in your project directory and initialize Git:

```bash
git init
This command creates a new Git repository in your project folder.



