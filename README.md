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

# 6_project_structure
✅## Vue.js 3 application structure.
Vue.js is a popular JavaScript framework for building user interfaces.It provides a structured approach to developing web applications by separating concerns into components.Here's a step-by-step guide to understanding the Vue.js 3 application structure:

## Setting up a Vue.js Project:
To get started, make sure you have Node.js installed on your machine.You can then use the Vue CLI(Command Line Interface) to create a new Vue.js project.Open your terminal or command prompt and run the following command:
```
$ vue create my - vue - app
```
This command will prompt you to select a preset for your project.You can choose the default preset or manually select features as per your requirements.

## Understanding the Project Structure:
Once the project is created, navigate into the project directory:

```
$ cd my - vue - app
```
The project structure will look something like this:

```
css
Copy code
my - vue - app
 ├── public
 │   ├── index.html
 ├── src
 │   ├── assets
 │   ├── components
 │   ├── App.vue
 │   └── main.js
 ├── package.json
 └── ...
```

public / index.html: This is the main HTML file where your Vue.js application will be mounted.You can add your global stylesheets or scripts here.
    
- src: This is the main directory where you'll write your Vue.js application code.
- src / assets: This directory is used to store static assets like images, fonts, etc.
- src / components: This directory is where you'll define your Vue components.
- src / App.vue: This is the root component of your application.It serves as the entry point for your entire application.
- src / main.js: This is the JavaScript file where you'll bootstrap your Vue.js application.

## Understanding the App.vue Component:

Open the src / App.vue file.This file contains three sections: template, script, and style.

template: The template section defines the HTML structure of the component.This is where you write your markup using Vue's template syntax, which includes directives, data bindings, and more.
script: The script section contains the JavaScript code for the component.This is where you define the component's data, methods, computed properties, lifecycle hooks, and more.
style: The style section contains the CSS styles specific to the component.You can use CSS or preprocessors like Sass or Less.

## Creating Vue Components:
In the src / components directory, you can create your own Vue components.Each component should have its own.vue file, which includes the template, script, and style sections.

 For example, let's create a simple "HelloWorld" component. Create a new file src/components/HelloWorld.vue and add the following code:

```
     < template >
    <div>
         <h1>{{ greeting }}</h1>
    </div>
 </ template >

 <script>
 export default {
   data() {
     return {
       greeting: 'Hello, Vue!'
     };
   }
 };
</script>

<style scoped>
 h1 {
   color: blue;
 }
</style>
```

## Registering and Using Components:
To use a component, you need to register it in your src / App.vue file or any other component where you want to use it.In the script section of the component, import the component file and register it using the components option.

In the src / App.vue file, modify the code as follows:

```
    < template >
     <div>
         <h1>{{ greeting }}</h1>
         <HelloWorld />
     </div>
 </ template >

<script>
import HelloWorld from './components/HelloWorld.vue';

 export default {
   components: {
     HelloWorld
   },
   data() {
     return {
       greeting: 'Hello, Vue!'
     };
   }
 };
</script>

<style scoped>
 h1 {
   color: blue;
 }
</style>
```

Now, the HelloWorld component is registered and ready to be used in the App component.You can use it by simply adding < HelloWorld /> in the template section.

##  Bootstraping the Vue Application:
The entry point of your Vue.js application is the src / main.js file.Open it and you'll find the following code:

``` 
import { createApp } from 'vue';
import App from './App.vue';

createApp(App).mount('#app');
```
The createApp function creates a new Vue application instance and takes the root component(in this case, App) as an argument.Finally, the mount method is called to mount the application on the element with the id app in the public / index.html file.

## Running the Vue Application:
Now that you have set up your Vue application structure, you can run it to see the result.Open your terminal or command prompt, navigate to the project directory, and run the following command:

``` 
$ npm run serve
``` 
This will start the development server, and you can view your Vue application by visiting the provided local or network URL.

As you make changes to your components or other files, the browser will automatically reload to reflect the updates.

That's it! You now have a basic understanding of the Vue.js 3 application structure. You can continue building upon this foundation by creating more components, setting up routing, managing state with Vuex, and exploring the rich ecosystem of Vue.js libraries and tools. 

Happy coding!

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

# Class Binding
- 
```
<script setup>
  
  const bgOrange="bg-orange-400"
  
</script>

<template>
 <div class="w-1/3 h-16" :class="bgOrange"></div>
</template>

```
### showing style by condition

```
<script setup>
  
    const weekday = false
  
</script>

<template>
    <section class="mt-10">

      <div class="h-16 flex items-center justify-center text-white" :class="weekday?'bg-red-600':'bg-green-600'">
        It's a weekday!
      </div>
    </section>

</template>

```

### showing multiple condition
- use array to show multiple condition

```
<script setup>
  
    const weekday = false
  
</script>

<template>
    <section class="mt-10">

      <div class="h-16 flex items-center justify-center text-white" :class="[weekday?'bg-red-600':'bg-green-600', weekday==true?'text-2xl':'text-4xl']">
        It's a weekday!
      </div>
    </section>

</template>

```
- another example

```
<script setup>
  
 const colors = {
    bgColor:'bg-teal-100',
    borderColor:'border-teal-500',
    textColor:'text-teal-900'
  }

  const messageType = 'warning'

  if('error'==messageType){
    colors.bgColor = 'bg-red-100'
    colors.borderColor = 'border-red-500'
    colors.textColor = 'text-red-900'
  }

  if('warning'==messageType){
    colors.bgColor = 'bg-orange-100'
    colors.borderColor = 'border-orange-500'
    colors.textColor = 'text-orange-900'
  }   
  
</script>

<template>
<section class="mt-10">
      <div class=" border-t-4 rounded-b px-4 py-3 shadow-md" :class="[colors.bgColor, colors.borderColor, colors.textColor]">
        <p class="font-bold">Our privacy policy has changed</p>
        <p class="text-sm">Make sure you know how these changes affect you.</p>
      </div>
    </section>

</template>

```

# Style Binding
- just use :style

```
<script setup>
const bgOrange = 'background-color: rgba(251, 146, 60, 1)'
const bgIndigo = 'background-color: rgba(129, 140, 248, 1)'
const bgGreen = 'background-color: rgba(52, 211, 153, 1)'

const bgRed = 'background-color: rgba(220, 38, 38, 1)'
const bgDarkGreen = 'background-color: rgba(5, 150, 105, 1)'

const colors = {
  borderColor: 'rgba(20, 184, 166, 1)', //rgba(239, 68, 68,1)
  // 'border-color': 'rgba(20, 184, 166, 1)', //rgba(239, 68, 68,1)
  color: 'rgba(19, 78, 74, 1)', //rgba(127, 29, 29,1)
  backgroundColor: 'rgba(204, 251, 241, 1)' //rgba(254, 226, 226,1)
}

const weekday = true
const messageType = 'error'

if('error'==messageType){
  colors.borderColor='rgba(239, 68, 68,1)'
  colors.backgroundColor = 'rgba(254, 226, 226,1)'
  colors.color = 'rgba(127, 29, 29,1)'
}
</script>

<template>
  <section class="container mx-auto">
    <h1 class="text-center text-3xl py-12">Class & Style Binding</h1>

    <section class="flex space-x-10">
      <div class="w-1/3 h-16" :style="bgOrange"></div>
      <div class="w-1/3 h-16" :style="bgIndigo"></div>
      <div class="w-1/3 h-16" :style="bgGreen"></div>
    </section>

    <section class="mt-10">
      <!-- <div class="h-16 flex items-center justify-center text-white" :style="weekday==true?[bgRed,'font-size:20px']:[bgDarkGreen, 'font-size:30px']"> -->
      <div class="h-16 flex items-center justify-center text-white" :style="[weekday == true ? bgRed : bgDarkGreen, weekday == true ? 'font-size:20px' : 'font-size:30px']">
        It's a weekday!
      </div>
    </section>

    <section class="mt-10">
      <div class=" border-t-4  rounded-b  px-4 py-3 shadow-md" :style="colors">
        <p class="font-bold">Our privacy policy has changed</p>
        <p class="text-sm">Make sure you know how these changes affect you.</p>
      </div>
    </section>
  </section>
</template>

<style scoped></style>

```

-- use array for multiple condition style

```
:style="[weekday == true ? bgRed : bgDarkGreen, weekday == true ? 'font-size:20px' : 'font-size:30px']

```

```
:style="weekday==true?[bgRed,'font-size:20px']:[bgDarkGreen, 'font-size:30px']

```

