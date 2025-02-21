A feature-rich eBook reader that supports TXT and PDF files, allowing users to customize their reading experience with highlighting, note-taking, brightness adjustment, and theme customization.

Features

Multi-Format Support: Read TXT and PDF files seamlessly.

User Authentication: Secure login and signup using Firebase authentication.

Library Management: Save, download, and wishlist books while tracking reading progress.

Personalized Reading Experience: Adjust brightness, change themes, and modify font size.

Interactive Features: Highlight text, take notes, and access a built-in dictionary.

Book Discovery: Integrated Google Books API for exploring new books.

Location-Based Services: Map functionality to calculate distances related to books and reading locations.

Tools & Technologies Used

Frontend: React Native

Authentication & Database: Firebase

APIs: Google Books API, Dictionary API

File Handling: Expo DocumentPicker, Expo FileSystem

Navigation & UI: React Navigation, React Native Components

Map & Location Services: React Native Maps

Installation & Setup

Clone the repository:

git clone https://github.com/yourusername/repository-name.git

Navigate to the project directory:

cd repository-name

Install dependencies:

npm install

Set up Firebase configuration in firebaseconfig.jsx.

Start the application:

npx expo start

Directory Structure

📂 project-root
├── 📂 components
│   ├── Books.jsx
│   ├── DownloadedBooks.jsx
│   ├── Home.jsx
│   ├── Login.jsx
│   ├── Signup.jsx
│   ├── Map.jsx
│   ├── PdfViewer.jsx
│   ├── TxtReader.jsx
│   ├── FirebaseConfig.jsx
│   ├── _Layout.jsx
│   ├── Index.jsx
├── 📂 assets
├── 📂 utils
├── package.json
├── App.js
└── README.md

Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

License

This project is licensed under the MIT License.
