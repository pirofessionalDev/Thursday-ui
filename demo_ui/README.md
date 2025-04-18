# Tailwind and postcss troubleshoot - 
In order to not get the "Could not find module error" use this command "npm install -D/-g[according to your needs] tailwindcss@4.3.17", you will face errors if you try the vanila method to install tailwind for your vite+tailwind setup.
I had to create the "tawilwind.config.js" and "postcss.config.js" files seperately becssue the new install did not create them for me.
