# Vibesphere

Vibesphere is a social media application built with React and Appwrite, aimed at providing a platform for users to share posts, connect with others, and explore content.

## Features

- **Authentication**: User signup and signin using Appwrite authentication.
- **Post Management**: Create, edit, delete, like, and save posts.
- **User Profiles**: View and update user profiles with bio and profile picture.
- **Explore**: Discover recent posts and explore content from other users.
- **Notifications**: Toast notifications for user actions like post creation and updates.
- **Responsive Design**: Mobile-friendly interface for seamless user experience across devices.

## Technologies Used

- **Frontend**:
  - React
  - React Router
  - Tailwind CSS
  - React Query
  - React Hook Form
  - Appwrite JavaScript SDK

- **Backend**:
  - Appwrite (Database, Storage, Authentication)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd vibesphere
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure Appwrite:

   - Set up an Appwrite backend with necessary collections for posts and users.
   - Update `appwriteConfig.js` with your Appwrite endpoint, project ID, and collection IDs.

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173` to view the application.

## Deployment

To deploy Vibesphere to production, follow these steps:

1. Build the application:

   ```bash
   npm run build
   ```

2. Deploy the built files to your hosting provider of choice.

## Acknowledgments

- This project was built as part of learning and exploring React and Appwrite integration.
- Special thanks to the JSM & open-source community for providing libraries and tools that made this project possible.


