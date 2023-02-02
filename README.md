# Tailwind-css

# Installation

```
npm install -D tailwindcss
npx tailwindcss init

// It will create Tailwind CSS config file: tailwind.config.js
//change content acc to destination
```

## Change package.json

```
"scripts": {

"build": "tailwindcss -i ./input.css -o ./css/styles.css" ,
"watch": "tailwindcss -i ./input.css -o ./css/styles.css --watch" 
}
  ```
## create input.css

Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
  
## Run npm run build to build styles.css file to destination folder 

```
npm run build 
npm run watch
```

## Add link file to the html file

```
<link rel="stylesheet" href="css/styles.css" />
```
