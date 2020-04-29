Steps
1. Create .ts file. 
2. Write code in it.
3. Compile it into a JavaScript file with tsc filename.ts. This will create a file with the same name but as a JavaScript file.
4. Do what you wanna do with the JavaScript file like in this program specifically, it does <script src="app.js" defer></script> in the index.html file.
5. Can change what appears on app.js by changing app.ts and recompiling it.

Types
Can specify what type a variable is in a ts file.
TypeScript's type system only helps you during development (before the code gets compiled.) 
It lets you know that one of your variables is giving off an error. An extra step to sanitize your code.

n1: number
n1: string
n1: boolean

Other stuff
1. npm --save-dev lite-server && npm start to host this program on a localhost:3000 that updates automatically anytime you change anything (have to compile first though). It's pretty nice.