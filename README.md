
MegaBlog - A Full-Stack Blog Application

A production-ready blogging platform built with React, Redux Toolkit, and Appwrite. This project features a full CRUD system, user authentication, and image management.


🚀 Features:

   * Complete Authentication: Secure Sign Up, Login, and Logout functionality powered by Appwrite Auth.

   * CRUD Operations: Users can create, read, update, and delete blog posts.

   * Rich Text Editor: Integrated TinyMCE editor for professional content creation.

   * File Management: Image upload, deletion, and real-time previewing using Appwrite Storage.

   * Global State Management: Efficient state handling for user sessions and data using Redux Toolkit.

   * Protected Routing: Custom AuthLayout component to secure private routes from unauthenticated users.

   * Responsive UI: Styled with Tailwind CSS for a clean, modern look on all devices.
     

🛠️ Tech Stack

   ➡️ Frontend: React, Tailwind CSS.

   ➡️ State Management: Redux Toolkit.

   ➡️ Backend-as-a-Service: Appwrite (Database, Auth, and Storage).

   ➡️ Form Handling: React Hook Form.

   ➡️ Navigation: React Router DOM.

   ➡️ Rich Text Editor: @tinymce/tinymce-react.
   

⚙️ Environment Variables:

To run this project, you will need to add the following environment variables to your .env file in the root directory:

   VITE_APPWRITE_URL="https://cloud.appwrite.io/v1"
   
   VITE_PROJECT_ID=""
   
   VITE_DATABASE_ID=""
   
   VITE_COLLECTION_ID=""
   
   VITE_BUCKET_ID=""

📦 Installation:

   1. Clone the repository:
        git clone <your-repo-link>
         cd MegaBlog
      
   2. Install dependencies:
        npm install

   3.  Run the development server:
          npm run dev



🛡️ Security:

   * Ensure your .env file is added to your .gitignore before pushing to public repositories.

   * The project uses a Protected (AuthLayout) component to prevent unauthorized access to post-creation and editing pages.

      
     
