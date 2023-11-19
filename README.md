SETUP🚀 :
1.Install react app using create-react-app (CRA)
npx create-react-app netflix-gpt

2.Create .env file and put configure
REACT_APP_BASE_URL = YOUR_APPLICATION_BASE_URL;
REACT_APP_OPENAI_KEY = YOUR_API_KEY_WILL_HERE;
REACT_APP_TMDB_KEY = YOUR_API_KEY_WILL_HERE;

3.Install and init tailwind css
npm install -D tailwindcss
npx tailwindcss init

4.Configure tailwind css in your project
npx tailwindcss init command will create a file tailwind.config.js in your project's root directory.
Open tailwind.config.js and replace all content with below code.
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};

5.Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.
@tailwind base;
@tailwind components;
@tailwind utilities;

6.Now you created a react app with tailwind css successfully.
Now run the below command on your terminal to start your local development server.
npm start

FEATURES🚀 :
1.Home Page (is user !authorised)
Signin/Signup Page
      SignInForm / SignUpForm
      
2.Browse Page
     Navbar
     Showcase
     Trendings
     MoviesSuggestion
          MoviesList * N
          
3.NetflixGPT
    Search
    MoviesSuggestion
    
#FEEL FREE TO CONTRIBUTE ❤️ ❤️ 




