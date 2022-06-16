# vue3CLI_And_Tailwind
# Bước 1 create project
      + vue create project
# Bước 2 : install tailwindcss, postcss, autoprefixer
      + cd project
      + npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9
# Bước 3 tạo ra tailwind.config.js, postcss.config.js
      + npx tailwindcss init -p
      
![Capture](https://user-images.githubusercontent.com/76818598/174048360-e14f6899-c152-4ceb-b013-01e2d99eaef7.PNG)

# Bước 4 tạo index.css trong src
      + với nội dung
            @tailwind base;
            @tailwind components;
            @tailwind utilities;
# Bước 5 Thêm vào file tailwind.config.js
               content: [
            "./src/**/*.{vue,js,ts,jsx,tsx}"
          ],
# Bước 6: Thêm vào file /src/main.js
      import './index.css'
