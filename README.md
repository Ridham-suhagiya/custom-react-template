# 🚀 My React Library Starter Template

A lightweight, customizable, and blazing-fast starter template for building UIs with React-like functionality! ✨

Powered by [@ridhamsuhagiya/my-react-library](https://www.npmjs.com/package/@ridhamsuhagiya/my-react-library), this template is your go-to solution for creating modern web applications with ease. Whether you're a beginner or a pro, this template has got you covered! 🎉

---

## 🌟 Why Choose This Template?

- 🚀 **Lightning Fast**: Minimal setup with zero bloat.
- 🎨 **Customizable**: Tailor it to fit your project needs.
- ⚛️ **React-like**: Built on a custom React-like library for a familiar dev experience.
- 🛠️ **TypeScript Ready**: Write type-safe code with ease.
- 📦 **Parcel Bundler**: Zero-configuration bundling for a seamless workflow.
- 🧩 **Pre-configured Templates**: Jumpstart your project with ready-to-use templates.

---

## 🛠️ Installation

Get started in seconds! Install the package globally:

```bash
npm install -g @ridhamsuhagiya/my-react-library-starter-template
```

---

## 🚀 Quick Start

### 1️⃣ Initialize a New Project
Run the setup script to create a new project:

```bash
react-from-scratch-init
```

This will:
- 📂 Copy the template files to your current directory.
- 📦 Install all necessary dependencies.

### 2️⃣ Start the Development Server
Navigate to your project folder and start the app:

```bash
npm start
```

Your app will be running at [http://localhost:1234](http://localhost:1234) 🎉

### 3️⃣ Build for Production
When you're ready to deploy, build the project:

```bash
npm run build
```

---

## 📂 Project Structure

```
my-react-library-starter-template/
├── dist/                  # Compiled output 🏗️
├── templates/             # Starter template files 🧩
│   ├── public/            # Static assets 🖼️
│   │   └── index.html     # HTML entry point 📄
│   ├── src/               # Source code 💻
│   │   └── index.js       # JavaScript entry point 🚪
│   └── package.json       # Project dependencies 📦
├── setup.js               # Setup script 🛠️
├── package.json           # Package configuration ⚙️
└── README.md              # Documentation 📚
```

---

## ⚛️ Using the Custom React Library

This starter template uses `@ridhamsuhagiya/my-react-library`, a lightweight React-like library. Here’s an example of how to use it:

```javascript
import { createElement, render, useState } from "@ridhamsuhagiya/my-react-library";

const App = () => {
  const [count, setCount] = useState(0);

  return createElement("div", null,
    createElement("h1", null, `Count: ${count}`),
    createElement("button", { onClick: () => setCount(count + 1) }, "Increment")
  );
};

mount({ componentFunc: APP, componentId: "main-app-component" });
```

---

## 🛠️ Customization

### 🧩 Adding New Features
- **Add Components**: Create new components in the `src/` folder.
- **Add Styles**: Use SCSS or CSS for styling. Parcel supports both out of the box.
- **Add TypeScript**: The template is pre-configured for TypeScript. Just rename `.js` files to `.ts` or `.tsx`.

### 🎨 Theming
Customize the look and feel of your app by modifying the styles.

---

## 🤝 Contributing

Contributions are welcome! 🎉 If you have any ideas, suggestions, or bug reports, feel free to open an issue or submit a pull request.

### Steps to Contribute:
1. **Fork** the repository.
2. **Create a new branch**: `git checkout -b feature/AmazingFeature`
3. **Commit your changes**: `git commit -m 'Add some AmazingFeature'`
4. **Push to the branch**: `git push origin feature/AmazingFeature`
5. **Open a pull request**

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Credits

- **Author**: Ridham Suhagiya
- **Library**: [@ridhamsuhagiya/my-react-library](https://www.npmjs.com/package/@ridhamsuhagiya/my-react-library)

---

## 🚀 Get Started Now!

Ready to build something amazing? Install the template and start coding:

```bash
npm install -g @ridhamsuhagiya/my-react-library-starter-template
react-from-scratch-init
npm start
```

Happy coding! 🎉👨‍💻👩‍💻