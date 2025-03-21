# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)



### **Essential Packages for an Advanced React App**  

Here’s a complete list of packages you may need for a modern React project:  

---

## **1️⃣ Core React Packages (Always Needed)**
```sh
npm install react react-dom
```
- `react` → Core React library  
- `react-dom` → Used for rendering React components in the browser  

---

## **2️⃣ Development Tools**
```sh
npm install -D vite eslint prettier husky lint-staged
```
- `vite` → Fast build tool for React  
- `eslint` → Linter for code quality  
- `prettier` → Code formatter  
- `husky` → Git hooks for pre-commit checks  
- `lint-staged` → Runs linters only on staged files  

---

## **3️⃣ React Router (For Navigation)**
```sh
npm install react-router-dom
```
- `react-router-dom` → For handling navigation and routes  

---

## **4️⃣ State Management**
Choose one of the following based on your needs:  

✅ **Zustand (Lightweight, Recommended)**  
```sh
npm install zustand
```
✅ **Redux Toolkit (For Large Apps)**  
```sh
npm install @reduxjs/toolkit react-redux
```
✅ **Recoil (Alternative to Redux, Good for Simplicity)**  
```sh
npm install recoil
```
✅ **Jotai (Minimal State Management)**  
```sh
npm install jotai
```

---

## **5️⃣ API & Data Fetching**
```sh
npm install axios @tanstack/react-query
```
- `axios` → For making API requests  
- `@tanstack/react-query` → For efficient data fetching and caching  

---

## **6️⃣ UI & Styling**
✅ **Tailwind CSS (Recommended)**
```sh
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```
✅ **Material UI (For Pre-built Components)**
```sh
npm install @mui/material @emotion/react @emotion/styled
```
✅ **Bootstrap (For Simple Styling)**
```sh
npm install bootstrap react-bootstrap
```
✅ **Styled Components (CSS-in-JS)**
```sh
npm install styled-components
```

---

## **7️⃣ Icons & Animations**
```sh
npm install react-icons framer-motion
```
- `react-icons` → For icons  
- `framer-motion` → For animations  

---

## **8️⃣ Form Handling & Validation**
```sh
npm install react-hook-form yup @hookform/resolvers
```
- `react-hook-form` → Handles forms easily  
- `yup` → Schema validation  
- `@hookform/resolvers` → Connects Yup with React Hook Form  

---

## **9️⃣ Utility Libraries**
```sh
npm install lodash dayjs classnames
```
- `lodash` → Utility functions  
- `dayjs` → Date/time formatting  
- `classnames` → Easily manage class names  

---

## **🔟 Optional: Firebase (For Authentication & Database)**
```sh
npm install firebase
```
- Use Firebase for authentication and real-time database  

---

### **📌 Final Notes**
Once you install the necessary packages, you can start your project using:
```sh
npm run dev
```
Let me know if you need help setting up! 🚀