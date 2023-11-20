# VUE NOTE
### A text bank of vue js journey.....
<br>

# For setting up the project
1. open command panel: 

```js
yarn create vite project-name

npm create vite project-name

```
2. Go to project Directory:

```
cd project-name
```
3. Install dependency: 
```
yarn install 

npm install

```
3. For running project:

```
yarn dev

npm run dev

```
# 05 ✅ setting up the development environment

Command for creating a project through vite :

```
npm create vite @latest
```
👉 To get started, we'll need to install some tools and configure our environment. Here's a step - by - step guide:

✅Step 1: Install Node.js and npm
Node.js is a JavaScript runtime that allows us to execute JavaScript outside of a browser.It also includes npm(Node Package Manager), which we'll use to install Vue.js and other dependencies.
- Visit the official Node.js website(https://nodejs.org) and download the latest stable version for your operating system.
- Run the installer and follow the prompts to install Node.js.Make sure to include npm during the installation process.
- To verify that Node.js and npm are installed correctly, open a terminal or command prompt and run the following commands:
```
node--version
npm--version
```
These commands should display the version numbers of Node.js and npm, respectively.

✅   Step 2: Create a new Vue.js project
Now that we have Node.js and npm installed, we can use Vue CLI(Command Line Interface) to create a new Vue.js project.

👉 Open a terminal or command prompt and run the following command to install Vue CLI globally:
```
npm install - g @vue / cli
```

👉 Once the installation is complete, navigate to the directory where you want to create your project.For example, if you want to create a project in a folder called "my-vue-project," use the following command:

```
cd path / to / my - vue - project

```
👉 Run the following command to create a new Vue.js project:
```
vue create.
```
The dot at the end of the command specifies the current directory as the project root.If you want to create the project in a subdirectory, replace the dot with the desired directory name.

- Vue CLI will prompt you to pick a preset for your project.For a basic setup, you can choose the default preset(Manually select features) by pressing Enter.

- Vue CLI will then present you with a list of features to choose from.You can use the arrow keys to navigate and the spacebar to select or deselect features.For a minimal setup, you can select Babel and Router, then press Enter.

- Vue CLI will ask whether you want to use history mode for the router.If you're unsure, you can choose the default option (Yes) by pressing Enter.

- Finally, Vue CLI will ask whether you want to save this as a preset for future projects.You can choose Yes or No based on your preference.

✅    Step 3: Install project dependencies
After creating the Vue.js project, we need to install the project dependencies defined in the package.json file.

In the terminal or command prompt, navigate to the project directory(if you're not already in it).
👉 Run the following command to install the project dependencies:
```
npm install
```
✅Step 4: Start the development server
Now that our project is set up, we can start the development server and see our Vue.js application in action.

In the terminal or command prompt, make sure you're in the project directory.
👉 Run the following command to start the development server:
```
npm run serve
```
This command will start the development server and display the local development URL where you can access your Vue.js application(usually http://localhost:8080).

 ** Vite is a build tool that provides a fast and optimized development experience for Vue.js applications.Let's get started:
**
👉 Step 1: Install Node.js and npm
Before we begin, ensure that you have Node.js and npm installed on your system.If you don't have them installed, please follow the instructions provided in Step 1 of the previous tutorial.

👉 Step 2: Create a new Vue.js 3 project with Vite
To create a new Vue.js 3 project with Vite, follow these steps:

 Open a terminal or command prompt.

 Run the following command to install Vite globally:

```
npm install - g create - vite
```
👉 Once the installation is complete, navigate to the directory where you want to create your project.For example, if you want to create a project in a folder called "my-vite-project," use the following command:

```
cd path / to / my - vite - project
``` 
👉 Run the following command to create a new Vue.js project with Vite:

```
// create - vite.

``` 
The dot at the end of the command specifies the current directory as the project root.If you want to create the project in a subdirectory, replace the dot with the desired directory name.

Vite will prompt you to pick a framework for your project.Since you want to create a Vue.js project, press Enter to select the default option(vue).

Vite will ask whether to use the JavaScript or TypeScript template.Choose your preferred option by pressing Enter.

Vite will then install the project dependencies and set up the project structure for you.

👉 Step 3: Start the development server
After creating the project, we can start the development server and see our Vue.js application in action.

In the terminal or command prompt, navigate to the project directory(if you're not already in it).

Run the following command to install the project dependencies:

```
npm install
``` 
Once the installation is complete, start the development server by running the following command:

```
npm run dev
```
This command will start the Vite development server and display the local development URL where you can access your Vue.js application(usually http://localhost:3000).

Congratulations! You have successfully set up a Vue.js 3 project with Vite.You can now start building your Vue components, styles, and application logic in the project.


# Showing Data from variable to template
- use {{ variable name/ function name }} to show data.
- install Volor to get all extension. 

```javascript
<script setup>
// variable: 
const message = 'Welcome. Get ready to';

// function: 
function getDate(){
  const date = new Date();
  return date.toDateString()
}

</script>

<template>
<div>
<h1 class="text-4xl"> {{ message }} </h1>

<h2 class="mt-10 text-xl text-gray-700">Today is <span>{{ getDate() }}</span></h2>

</div>
</template>

```

# Showing data from Object
Must destructure the object: date=>message=>

```
<script setup>
const data = {

  message: 'Welcome. Get ready to master Vue.js 3!',
  date: '30th June, 2023',
  tasks: [1, 2, 3, 4, 5]
}
</script>

<template>

  <div class="container mx-auto flex items-center justify-center min-h-screen flex-col">

    <h1 class="text-4xl"> {{ data.message }} </h1>
    <h2 class="mt-10 text-xl text-gray-700">You have <span>{{ data.tasks.length }} tasks for today</span></h2>
  </div>
</template>

```

# Displaying-html
- v-html can bind the html
```
<script setup>
    const message = 'Welcome. Get ready to master <em>Vue.js 3!</em>'
    const date = '<strong>30th June, 2023</strong>'
</script>

<template>
  <div class="container mx-auto flex items-center justify-center min-h-screen flex-col">
      <h1 class="text-4xl" v-html="message"></h1>
      <h2 class="mt-10 text-xl text-gray-700">Today is <span v-html="date"></span></h2>
  </div>
</template>

```

video 14
