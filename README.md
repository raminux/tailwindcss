#Tailwindcss
First of all it is essential to install VS Code and the following extensions:
- Headwind
- Live server
- Tailwind css IntelliSense
- Alpine.js IntelliSense

Then, it is required to install node.js. For ubuntu just run the following command:
```bash
$> sudo apt install node
$> sudo apt install npm
```
Next, git should be installed:
```bash
$> sudo apt install git
```

Now, we are ready to install tailwindcss. It begins by initializing a node project:
```bash
$> npm init -y
```
Then, install the required libraries:
```bash
$> npm install tailwindcss postcss postcss-cli autoprefixer
```
Then next command will create two config files named, `tailwind.config.js` and `postcss.config.js`. 
```bash
$> npx tailwindcss init -p
```
At this stage, we need to create the directory structure:
```bash
$> touch tailwind.css
$> mkdir dist
$> mkdir dist/css
$> touch dist/css/styles.css
$> touch dist/index.html
```

