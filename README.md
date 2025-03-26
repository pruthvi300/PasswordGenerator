
![Screenshot from 2025-03-26 15-02-21](https://github.com/user-attachments/assets/9a2b89d0-b897-4075-a718-c1bc7d171d2b)
![Screenshot from 2025-03-26 15-01-57](https://github.com/user-attachments/assets/645dcd0e-eb5c-4661-a5cf-9a76e1bd2a7a)

# Password Generator App

This is a **Password Generator App** built using **React** with **Vite**. The app allows users to generate secure and random passwords based on selected criteria such as length, inclusion of numbers, symbols, uppercase, and lowercase letters.

## Features

✅ Generate strong random passwords
✅ Customize password length
✅ Include/exclude numbers, symbols, uppercase, and lowercase letters
✅ Copy generated password to clipboard
✅ Responsive and user-friendly UI

## Tech Stack

- **Frontend**: React (Vite)
- **Styling**: Tailwind CSS / CSS Modules / Styled Components (based on your setup)
- **State Management**: useState (React Hooks)

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Node.js (v16+ recommended)
- npm or yarn

### Steps to Run the Project

1. **Clone the Repository**
   ```sh
   git clone https://github.com/pruthvi300/PasswordGenerator.git
   cd PasswordGenerator
   ```

2. **Install Dependencies**
   ```sh
   npm install   # or yarn install
   ```

3. **Start the Development Server**
   ```sh
   npm run dev   # or yarn dev
   ```

4. **Open in Browser**
   The app will run at: **http://localhost:5173** (or the port shown in the terminal)

## Project Structure
```
password-generator/
│── src/
│   ├── components/       # Reusable React components
│   ├── hooks/            # Custom React hooks (if any)
│   ├── styles/           # CSS/Tailwind styles
│   ├── App.jsx           # Main React component
│   ├── main.jsx          # React entry file
│── public/               # Static assets
│── index.html            # Main HTML file
│── vite.config.js        # Vite configuration
│── package.json          # Project metadata and dependencies
│── README.md             # Project documentation
```

## Usage
1. Select the desired password length (e.g., 8-32 characters).
2. Choose the options:
   - Include Numbers (0-9)
   - Include Symbols (!@#$%^&*)
   - Include Uppercase Letters (A-Z)
   - Include Lowercase Letters (a-z)
3. Click **Generate Password**.
4. Click **Copy to Clipboard** to use the generated password anywhere.

## Deployment
To deploy the project, build it using Vite:
```sh
npm run build   # or yarn build
```
This will generate a `dist/` folder with optimized production-ready files. You can deploy them on platforms like:
- Vercel
- Netlify
- GitHub Pages

## Contributions
Contributions are welcome! Feel free to fork the project and submit a PR with improvements.

## Author
Developed by [Pruthviraj Kakade](https://github.com/pruthvi300)

## License
This project is open-source and available under the [MIT License](LICENSE).

---

🚀 **Happy Coding!**

