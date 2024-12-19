# Netflix GPT
# configurations
    - create react app
    - configured the Tailwind css
        -npm install -D tailwindcss
        -npx tailwindcss init
        -configure template path
                -/** @type {import('tailwindcss').Config} */
                    module.exports = {
                    content: [
                        "./src/**/*.{js,jsx,ts,tsx}",
                    ],
                    theme: {
                        extend: {},
                    },
                    plugins: [],
                    }
# features
    - Login/sign Up
        - login/singup form
        - Redirect to browser page
    -Browser (main page)
        - Header
        -main movie
            -background trailer
            - tile and description
            - movie name suggestions
                -movie Liists
    - netflix-GPT
        - serach bar
        - movie suggestions
# Run and Build
    - npm run start/ npm start.
    - npm build