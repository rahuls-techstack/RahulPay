https://codehelp-razorpay-clone.netlify.app/

<--Initial steps to execute Tailwind CSS -->
1. Create index.html file.
2. Create styles.css file and inside it write
@tailwind base;
@tailwind components;
@tailwind utilities; inside the css file and link it to the index.html file.
3. Open new terminal and run
>>npm install -D tailwindcss vite
then run
>>npx tailwindcss init -p
4. Open tailwind.config.js file and add "*" inside content: [],
i.e., content: ["*"],
5. Open package.json file and add
  "scripts": {
    "start": "vite"
  },
below the first line.
6. Run the command on terminal
>>npm install
>>npm run start

And you are good to go .^.