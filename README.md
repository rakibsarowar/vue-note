# 🚀 VUE NOTE

**A hand note of my vue js journey.....**

<br>

<!-- COMMENT -->

## Table of Contents

- [UI Components](#ui-components)
  - [Editable data grid / spreadsheet](#editable-data-grid--spreadsheet)
  - [Table](#table)
  - [Infinite Scroll](#infinite-scroll)
- [Vue Router](#vue-router)

## UI Components

**[`Back to top ⬆️`](#table-of-contents)**

<br>

**Need to note first**

🎯 : **Main Topic.** <br>
🟩 🟨 🟥 : **Paragraph** <br>
📕 : **Havey Note.**  <br>
📒 : **Attention Note.** <br>
🏷️ : **Regular Note** <br>
📌 : **Regular Note** <br>
💎 : **High Value info** <br>
🧨 : **Carefull this** <br>
✋ : **Stop! check the point** <br>

<br>

## 🎯 For setting up the project:
**[`Back to top ⬆️`](#table-of-contents)**

<br>
👉 Step 01. কমান্ড প্যানেল খুলুন | open command panel:

```js
yarn create vite project-name

npm create vite project-name

```

👉 Step 02. নিম্ন কোড দিয়ে প্রজেক্ট ডাইরেক্টরিতে যান | Go to project Directory:

```
cd project-name
```

👉 Step 03. Install dependency ( ডিপেন্ডেন্সিগুলো ইন্সটল করুন নিম্ন কোড দিয়ে ):

```
yarn install

npm install

```

3. For running project ( এবার নিম্ন কোড দিয়ে প্রজেক্ট রান করুন | কোড রানের আগে code . দিয়ে vscode এ ফাইলটি ওপেন করতে পারনে।) :

```
yarn dev

npm run dev

```

## 🎯 setting up the development environment

<br>
Command for creating a project through vite :

```
npm create vite @latest
```

👉 To get started, we'll need to install some tools and configure our environment. Here's a step - by - step guide:

👉 **Step 1: Install Node.js and npm**
<br>
Node.js is a JavaScript runtime that allows us to execute JavaScript outside of a browser.It also includes npm(Node Package Manager), which we'll use to install Vue.js and other dependencies.

- Visit the official Node.js website(https://nodejs.org) and download the latest stable version for your operating system.
- Run the installer and follow the prompts to install Node.js.Make sure to include npm during the installation process.
- To verify that Node.js and npm are installed correctly, open a terminal or command prompt and run the following commands:

```
node--version
npm--version
```

These commands should display the version numbers of Node.js and npm, respectively.

👉 **Step 2: Create a new Vue.js project**
<br>
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
  <br>
  👉 **Step 3: Install project dependencies**
  <br>
  After creating the Vue.js project, we need to install the project dependencies defined in the package.json file.

In the terminal or command prompt, navigate to the project directory(if you're not already in it).
👉 Run the following command to install the project dependencies:

```
npm install
```

<br>

✅Step 4: Start the development server
<br>
Now that our project is set up, we can start the development server and see our Vue.js application in action.

In the terminal or command prompt, make sure you're in the project directory.
👉 Run the following command to start the development server:

```
npm run serve
```

This command will start the development server and display the local development URL where you can access your Vue.js application(usually http://localhost:8080).

** Vite is a build tool that provides a fast and optimized development experience for Vue.js applications.Let's get started:
**
👉 **Step 1: Install Node.js and npm**
Before we begin, ensure that you have Node.js and npm installed on your system.If you don't have them installed, please follow the instructions provided in Step 1 of the previous tutorial.

👉 **Step 2: Create a new Vue.js 3 project with Vite**
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

👉 **Step 3: Start the development server**
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

## 🎯 project structure

<br>
✅ Vue.js 3 application structure.
<br>
Vue.js is a popular JavaScript framework for building user interfaces.It provides a structured approach to developing web applications by separating concerns into components.Here's a step-by-step guide to understanding the Vue.js 3 application structure:

## ✅ Setting up a Vue.js Project:

<br>
To get started, make sure you have Node.js installed on your machine.You can then use the Vue CLI(Command Line Interface) to create a new Vue.js project.Open your terminal or command prompt and run the following command:
```
$ vue create my - vue - app
```
🏷️ This command will prompt you to select a preset for your project.You can choose the default preset or manually select features as per your requirements.

## ✅ Understanding the Project Structure:

<br>
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

## ✅ Understanding the App.vue Component:

<br>
Open the src / App.vue file.This file contains three sections: template, script, and style.

template: The template section defines the HTML structure of the component.This is where you write your markup using Vue's template syntax, which includes directives, data bindings, and more.
script: The script section contains the JavaScript code for the component.This is where you define the component's data, methods, computed properties, lifecycle hooks, and more.
style: The style section contains the CSS styles specific to the component.You can use CSS or preprocessors like Sass or Less.

## ✅ Creating Vue Components:

<br>
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

## ✅ Registering and Using Components:

<br>
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

## ✅ Bootstraping the Vue Application:

<br>
The entry point of your Vue.js application is the src / main.js file.Open it and you'll find the following code:

```
import { createApp } from 'vue';
import App from './App.vue';

createApp(App).mount('#app');
```

The createApp function creates a new Vue application instance and takes the root component(in this case, App) as an argument.Finally, the mount method is called to mount the application on the element with the id app in the public / index.html file.

## ✅ Running the Vue Application:

<br>
Now that you have set up your Vue application structure, you can run it to see the result.Open your terminal or command prompt, navigate to the project directory, and run the following command:

```
$ npm run serve
```

This will start the development server, and you can view your Vue application by visiting the provided local or network URL.

As you make changes to your components or other files, the browser will automatically reload to reflect the updates.

That's it! You now have a basic understanding of the Vue.js 3 application structure. You can continue building upon this foundation by creating more components, setting up routing, managing state with Vuex, and exploring the rich ecosystem of Vue.js libraries and tools.

Happy coding!

# 🎯 Showing Data from variable to template
**[`Back to top ⬆️`](#table-of-contents)**

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

# 🎯 Showing data from Object
**[`Back to top ⬆️`](#table-of-contents)**

<br>
👉 Must destructure the object: date=>message=>

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

# 🎯  Displaying-html
**[`Back to top ⬆️`](#table-of-contents)**

<br>
👉 v-html can bind the html

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

# 🎯  Class Binding
**[`Back to top ⬆️`](#table-of-contents)**

```
<script setup>

  const bgOrange="bg-orange-400"

</script>

<template>
 <div class="w-1/3 h-16" :class="bgOrange"></div>
</template>

```

### ✅ showing style by condition
**[`Back to top ⬆️`](#table-of-contents)**

<br>

```
<script setup>

    const weekday = false

</script>

<template>
      <div class="h-16 flex items-center justify-center text-white" :class="weekday?'bg-red-600':'bg-green-600'">
        It's a weekday!
      </div>
</template>

```

### ✅ showing multiple condition
**[`Back to top ⬆️`](#table-of-contents)**

<br>
👉 use array to show multiple condition

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

👉 👉 another example

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

# 🎯  Style Binding
**[`Back to top ⬆️`](#table-of-contents)**

<br>
👉 just use :style

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

👉 👉 use array for multiple condition style

```
:style="[weekday == true ? bgRed : bgDarkGreen, weekday == true ? 'font-size:20px' : 'font-size:30px']

```

```
:style="weekday==true?[bgRed,'font-size:20px']:[bgDarkGreen, 'font-size:30px']

```

## ✅ Simple Loop or List Rendering (this is called for looping in vue js)

<br>
👉 use v-for for looping
👉 must give a unique :key (ID)

```
<script setup>
const items = [1,2,3,4,5]
</script>

<template>
  <section class="mx-auto container flex items-center text-center flex-col space-y-2">
        <!-- <div class="p-5 border border-gray-600 w-40" v-for="n in 5"> {{ n }}</div> -->
        <div class="p-5 border border-gray-600 w-40" v-for="item in items"> {{ item }}</div>

    </section>
</template>

<style scoped>

</style>

```

👉 another example:

```
<script setup>
const tasks = [
  "Complete project proposal",
  "Update website content",
  "Fix bug in user authentication",
  "Prepare presentation slides",
  "Test new feature implementation",
];
</script>

<template>
  <section class="mx-auto container">
    <section class="mx-auto container space-y-3">
        <div class="p-5 border border-gray-600 text-left" v-for="(task, index) in tasks">{{ index+1 }}. {{task}}</div>
    </section>
  </section>
</template>

<style scoped>

</style>

```

## ✅ showing object by loop:

<br>

```
<script setup>
const tasks = [
  { id: 1, title: "Complete project proposal", status: "In Progress" },
  { id: 2, title: "Update website content", status: "Completed" },
  { id: 3, title: "Fix bug in user authentication", status: "In Progress" },
  { id: 4, title: "Prepare presentation slides", status: "Pending" },
  { id: 5, title: "Test new feature implementation", status: "In Progress" },
];

const person = {
  name: "John Doe",
  age: "45",
  designation: "CTO",
  email: "john@doe.com"
}
//v,k,i

function getCompleteTasks(){
  return tasks.filter( task => 'Completed'==task.status)
}

function getTasksInProgress(){
  // return tasks.filter( task => 'In Progress'==task.status)
  return tasks.filter( function(task){
    return 'In Progress'==task.status
  })
}

</script>

<template>
  <section class="mx-auto container">
    <section class="mx-auto container space-y-3">
      <h2>Completed</h2>
      <div class="p-5 border border-gray-600 text-left" v-for="(task, index) in getCompleteTasks()" :key="index">{{ task.id }} - {{task.title}} </div>
      <h2>In Progress</h2>
      <div class="p-5 border border-gray-600 text-left" v-for="(task, index) in getTasksInProgress()" :key="index">{{ task.id }} - {{task.title}} </div>
      <h2>Pending</h2>
      <div class="p-5 border border-gray-600 text-left" v-for="(task, index) in tasks" v-show="'Pending'==task.status" :key="index">{{ task.id }} - {{task.title}} </div>
      <!-- <div class="p-5 border border-gray-600 text-left" v-for="(task, index) in tasks" :key="index">{{ task.id }} - {{task.title}} </div> -->
      <h2>Object Loop</h2>
      <div class="p-5 border border-gray-600 text-left" v-for="(value, property, index) in person" :key="property">{{ property }} = {{ value }}</div>

    </section>
  </section>
</template>

<style scoped></style>
```

# 🎯 vue instance and data binding
**[`Back to top ⬆️`](#table-of-contents)**

<br>

Vue.js is a popular JavaScript framework for building user interfaces.It allows you to create reactive components that update automatically when their underlying data changes.Let's dive into the concepts of Vue instances and data binding.

## Vue Instance:

<br>
A Vue instance is the root of every Vue application.It acts as a container that connects your HTML template with your JavaScript code.You create a Vue instance using the Vue constructor function. Here's an example of creating a basic Vue instance:
<br>

```
    // HTML

 < div id = "app" >
    {{ message }}
 </ >
```

```
// JavaScript
 var app = new Vue({
             el: '#app',
             data: {
                 message: 'Hello, Vue!'
             }
         });
```

In this example, we have an HTML template with an element having the ID app.We pass this selector to the el option of the Vue instance to mount it to that element.The data option contains the properties and their initial values that we want to use in our template.In this case, we have a message property with the initial value of 'Hello, Vue!'.

## Data Binding:

<br>
Data binding in Vue allows you to establish a connection between the data in your Vue instance and the DOM elements in your template.There are different types of data bindings available in Vue, such as text interpolation, property binding, and event binding.Let's explore each of them with code examples.

## Text Interpolation:

<br>
Text interpolation allows you to display the value of a property in your Vue instance directly in the template.Use double curly braces({{}}) to perform text interpolation.Here's an example:
<br>

```
     < div id = "app" >
         <p>{{ message }}</p>
 </ >
```

- The message property from the Vue instance will be inserted into the < p > element.

## Property Binding:

Property binding allows you to bind the value of an HTML attribute to a property in your Vue instance.Use the v - bind directive or its shorthand(: ) to perform property binding.Here's an example:
<br>

```
     < div id = "app" >
         <img: src="imageUrl" >
     </div >
```

In this example, the src attribute of the < img > tag is bound to the imageUrl property in the Vue instance.Any changes to imageUrl will automatically update the src attribute.

## Event Binding:

<br>
Event binding allows you to bind DOM events to methods in your Vue instance.Use the v - on directive or its shorthand(@) to perform event binding.Here's an example:
<br>

```
     < div id = "app" >
         <button @click="sayHello" > Click me</button >
     </ >
```

In this example, the click event of the < button > element is bound to the sayHello method in the Vue instance.When the button is clicked, the sayHello method will be called.

These are just a few examples of data binding in Vue.Vue provides many more features and directives for handling more complex scenarios.I hope this introduction to Vue instances and data binding was helpful to you.Feel free to explore the official Vue documentation for more in -depth information and examples.Happy coding!

# 🎯  8 Vue.js directives.
**[`Back to top ⬆️`](#table-of-contents)**

<br>
Directives are special attributes that you can use in your Vue templates to apply behavior to the DOM elements. Vue.js provides several built-in directives that you can use out of the box, and you can also create custom directives.

Here are some of the most commonly used Vue.js directives:

### v-if / v-else:

These directives are used for conditional rendering. You can use them to conditionally render elements based on a certain condition.

<br>

```
 <div v-if="isVisible">This is visible</div>

 <div v-else>This is hidden</div>

```

### v-for:

The v-for directive is used to render a list of items based on an array. It iterates over the array and generates the necessary DOM elements.
<br>

```
 <ul>
  <li v-for="item in items" :key="item.id">{{ item.name }}</li>
</ul >

```

### v-bind:

The v-bind directive is used for binding values to an element's attributes or props. It allows you to dynamically set values based on data in your Vue instance.
<br>

```
 <img v-bind:src="imageSrc">

 <a v-bind:href="linkUrl">{{ linkText }}</a>
```

### v-on:

The v-on directive is used to attach event listeners to elements. It allows you to listen to DOM events and trigger methods in response.
<br>

```
 <button v-on:click="handleClick">Click me</button>

```

### v-model:

The v-model directive is used for two-way data binding. It creates a relationship between form input elements and the data in your Vue instance.
<br>

```
<input v-model="message" type="text">

```

These are just a few examples of Vue.js directives. There are more directives available in Vue.js, and you can even create your own custom directives if needed.

Remember that directives are applied to DOM elements as attributes. The v- prefix is used to indicate that an attribute is a Vue directive.

<br>

# 🎯  v - bind in Vue.js
**[`Back to top ⬆️`](#table-of-contents)**

In Vue.js, v-bind is a directive used to bind data or expressions to an HTML attribute. It allows you to dynamically update the value of an attribute based on the underlying data or computed properties in your Vue component.

## ✅Here's the general syntax of v-bind:

<br>

```

 <tag-name v-bind:attributeName="expression"></tag-name>

```

👉 The v-bind directive is often abbreviated with a colon (:), so you can also write it like this:
<br>

```

 <tag-name :attributeName="expression"></tag-name>

```

Now, let's dive into some examples to illustrate how v-bind works:

### ✅ Example 1: Binding a Data Property

<br>

Suppose you have a data property called title in your Vue component, and you want to bind it to the title attribute of an `<h1>` element.

<br>

```
<template>

  <h1 v-bind:title="title">Hello World</h1>

</template>

<script>
export default {
  data() {
    return {
      title: "My Awesome Website"
    };
  }
};
</script>

```

<br>
In this example, the value of the title attribute will be dynamically updated whenever the title data property changes.

### ✅Example 2: Binding a Computed Property

<br>
You can also use v-bind with computed properties. Here's an example where we bind a computed property called fullName to the value attribute of an <input> element.
<br>

```
<template>
  <div>
    <input type="text" v-bind:value="fullName" />
    <p>Full Name: {{ fullName }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      firstName: "John",
      lastName: "Doe"
    };
  },
  computed: {
    fullName() {
      return this.firstName + " " + this.lastName;
    }
  }
};
</script>

```

👉 In this case, the input field will always display the full name, which is derived from the firstName and lastName data properties.

### ✅Example 3: Binding to Inline Styles

<br>
You can also use v-bind to bind CSS styles dynamically. Here's an example where we bind the backgroundColor style property to a data property called color.
<br>

```
 <template>
  <div v-bind:style="{ backgroundColor: color }">
    <p>Some content with a dynamic background color.</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      color: "red"
    };
  }
};
</script>

```

<br>

👉 In this example, the background color of the <div> element will be updated to the value of the color data property.

✅ class binding in Vue.js 3. Class binding allows you to dynamically add or remove CSS classes to elements based on certain conditions or data in your Vue component.This feature is useful for styling elements based on their current state.

In Vue.js 3, you can use the v - bind directive(or the shorthand : ) to bind a class to an element.Let's go through some examples to understand how it works.

### 👉 Example 1: Basic Class Binding

Suppose you have a Vue component with a data property called isActive, which determines whether a button should be active or not.You want to apply a CSS class called active when the button is active.Here's how you can achieve that:
<br>

```
< template >
   <button: class="{ active: isActive }" > Click me</button: >
 </template >

   <script>
     export default {
       data() {
     return {
       isActive: false
     };
   }
 };
   </script>

```

👉 In this example, the : class directive binds the active class to the button element when the isActive data property is true.

### 👉 Example 2: Conditional Class Binding

<br> 
You can also bind multiple classes conditionally.Let's say you have two classes, success and error, and you want to apply them based on the value of a data property called status:
<br>

```

< template >
   <div: class="{
     success: status === 'success',
     error: status === 'error'
     }">
     { { status } }
   </div: >
</template >

<script>
     export default {
       data() {
     return {
       status: 'success'
     };
   }
 };
</script>

```

👉 In this example, the : class directive applies the success class when status is 'success', and the error class when status is 'error'.

### 👉Example 3: Dynamic Class Binding

<br>
You can also bind classes dynamically based on computed properties or methods.Let's say you have a computed property called isSpecial that determines whether an element should have a special class:
<br>

```

   < template >
   <div: class="specialClasses" > Some element</div: >
 </template >

   <script>
     export default {
       computed: {
       isSpecial() {
       // Some condition to determine if the element is special
//       return true;
     },
     specialClasses() {
       return {
       special: this.isSpecial
       };
     }
   }
 };
   </script>

```

<br>

👉 In this example, the specialClasses computed property returns an object with the special class when isSpecial is true.If isSpecial is false, the class will not be applied.

👉 These are just a few examples of how you can use class binding in Vue.js 3. With class binding, you can create dynamic and responsive UIs by applying or removing CSS classes based on your component's data.

# ✅style binding in Vue.js 3.

Style binding allows you to dynamically apply CSS styles to elements based on data in your Vue component.It's a powerful feature that enables you to create dynamic and responsive user interfaces. Let's dive into the details with some code examples.

In Vue.js 3, you can use the v - bind directive to bind CSS styles to elements.Here's the syntax for style binding:
<br>

```

 < div: style = "{'property': value}" > Content</ >

```

<br>

👉 The :style directive binds the styles to the element, and the expression within the quotes specifies the CSS properties and values you want to apply.

👉 Here are a few examples to illustrate how style binding works in practice:

### ✅Example 1: Binding a single style property

<br>

```

  < template >
   <div: style="{'color': textColor}" > This text will have a dynamically bound color.</div: >
  </template >

   <script>
     export default {
       data() {
     return {
       textColor: 'red'
     };
   }
 };
  </script>

```

<br>

👉 In this example, the textColor data property is bound to the color CSS property.The text within the < div > will be displayed in the color specified by the textColor property, which is initially set to 'red'.

### ✅Example 2: Binding multiple style properties

<br>

```

   < template >
   <div: style="{'color': textColor, 'font-size': fontSize + 'px'}" >
     This text will have dynamically bound color and font size.
   </div: >
  </template >

   <script>
     export default {
       data() {
     return {
       textColor: 'blue',
     fontSize: 16
          };
        }
      };
   </script>

```

👉 In this example, both the color and font - size properties are bound to the textColor and fontSize data properties, respectively.The fontSize is concatenated with 'px' to provide a valid CSS value.

### ✅ Example 3: Dynamic style bindings with computed properties

<br>

```

   < template >
   <div: style="textStyle" > This text will have dynamically computed styles.</div: >
   </template >

   <script>
     export default {
       data() {
     return {
       isBold: true,
     isUnderline: false
     };
   },
     computed: {
       textStyle() {
       return {
       'font-weight': this.isBold ? 'bold' : 'normal',
     'text-decoration': this.isUnderline ? 'underline' : 'none'
       };
     }
   }
 };
  </script>

```

<br>

👉 In this example, the textStyle computed property dynamically computes the CSS styles based on the isBold and isUnderline data properties.If isBold is true, the text will be displayed in bold, and if isUnderline is true, the text will be underlined.

👉 These examples demonstrate the basics of style binding in Vue.js 3. You can bind any CSS property and value pairs you need, and even use dynamic data or computed properties to compute the styles at runtime.Remember to prefix property names with a dash when using kebab -case CSS properties, such as 'font-weight' and 'text-decoration'.

👉 I hope this explanation and these code examples help you understand style binding in Vue.js 3. Feel free to ask if you have any further questions!

# 🎯 Life cycle:
**[`Back to top ⬆️`](#table-of-contents)**

```
<script setup>
import {ref, onBeforeMount, onMounted, onUnmounted, onUpdated } from 'vue'
const status = ref([])
const apiResponse = ref(null)

onBeforeMount(() => {
  console.log('before mount')
  status.value.push('before mount')

  fetch('https://jsonplaceholder.typicode.com/todos/1')
    .then(response => response.json())
    .then(json => {
      apiResponse.value = json
    })
})

// onBeforeMount(function(){
//   status.value.push('before mount')
// })

onMounted(() => {
  console.log('mounted')
  status.value.push('mounted')
})


</script>

<template>
  <section class="mx-auto container">
    <h1 class="my-5">Lifecycle Hooks</h1>
    <div class="flex justify-between mt-20">
      <div class="w-1/2">
        <img src="//vuejs.org/assets/lifecycle.16e4c08e.png" alt="">
      </div>
      <div class="text-2xl w-1/2">
        {{ status }}
      </div>
      <p class="mt-10">
        {{ apiResponse  }}
      </p>
    </div>

  </section>

</template>

<style scoped></style>

```




# Vue Router

<br>
Vue Router is a powerful routing library that allows you to build single - page applications with multiple views and handle navigation between them.Let's dive into the details and explore some code examples!

## 👉 Step 1: Installation and Setup
<br>
To start, make sure you have Vue.js 3 installed in your project.You can create a new Vue.js project or use an existing one.Once you have Vue.js set up, you can install Vue Router v4 using npm or yarn:


**Using npm/ Using yarn**

```
npm install vue - router@next

yarn add vue - router@next
```

## 👉 Step 2: Configuration
<br> 
Once you've installed Vue Router, you need to configure it in your Vue.js application. Create a new file called router.js (or any other name you prefer) in your project's root directory.In this file, we'll define our routes and configure the router.

```
// Import Vue and Vue Router
import { createRouter, createWebHistory } from 'vue-router';

// Import your components for routing
import Home from './components/Home.vue';
import About from './components/About.vue';
import Contact from './components/Contact.vue';

// Create the router
const router = createRouter({
     history: createWebHistory(),
     routes: [
         {
             path: '/',
             name: 'home',
             component: Home
         },
         {
             path: '/about',
             name: 'about',
             component: About
         },
         {
             path: '/contact',
             name: 'contact',
             component: Contact
         }
     ]
 });

// Export the router
export default router;

```
<br>

In the code snippet above, we import the necessary modules from vue - router.Then we import the components that we want to use as routes, such as Home, About, and Contact.We create a new router instance using createRouter() and provide the routes array.Each route is defined with a path, a unique name, and the corresponding component to render when the route is visited.

## ✅ Step 3: Integrate the Router in your main Vue instance
<br> 
To integrate the router into your main Vue instance, open your main.js(or equivalent) file and import the router we just created.Then use the router instance in the Vue app.
<br>

```
// Import Vue and the router
import { createApp } from 'vue';
import router from './router';

// Import the root component
import App from './App.vue';

// Create the Vue app
const app = createApp(App);

// Use the router
app.use(router);

// Mount the app to the DOM
app.mount('#app');
```

## ✅ Step 4: Creating Route Components

Now let's create the components for the routes we defined earlier. For example, create a file called Home.vue and add the following code:

```

     < template >
     <div>
         <h1>Home</h1>
         <!-- Your home page content here -->
     </div>
     </ template >

     <script>
         export default {
             // Component options here
         }
     </script>

```
<br>
Similarly, create About.vue and Contact.vue files with their respective content.
<br>

## ✅ Step 5: Navigating between Routes

To navigate between routes, you can use the < router - link > component provided by Vue Router.This component renders an anchor tag that automatically updates the URL and triggers the corresponding route.
<br>

 ```
     < template >
     <div>
         <h1>My Website</h1>
         <nav>
           
             <router-link to="/">Home</router-link>
             <router-link to="/about">About</router-link>
             <router-link to="/contact">Contact</router-link>
         </nav>

         <router-view></router-view>
     </div>
     </template >

     <script>
         export default {
            // Component options here
         }
     </script>

```
<br>

 In the code snippet above, we've added the <router-link> components to create navigation links for the Home, About, and Contact routes. The to attribute specifies the path to navigate to when the link is clicked.
<br>
Additionally, we've added the <router-view> component, which acts as a placeholder for the content of the currently active route. When a user navigates to a specific route, the component associated with that route will be rendered inside the <router-view>.

## ✅ Step 6: Route Parameters and Dynamic Routes
<br>
Vue Router allows you to define dynamic routes that can accept parameters.For example, let's say we want to create a route for displaying a user's profile.Modify the router.js file to include a dynamic route:

```
// ...

 const router = createRouter({
     history: createWebHistory(),
     routes: [
         // ...
         {
             path: '/user/:id',
             name: 'user',
             component: User
         }
     ]
 });

// ...

```

<br>

In the code snippet above, we added a dynamic route / user /: id.The :id part indicates a parameter that can be passed in the URL.
<br>
Now, let's create the User.vue component to display the user's profile:

<br>

```
     < template >
     <div>
         <h2>User Profile</h2>
         <p>User ID: {{ $route.params.id }}</p>
         <!-- Additional user profile content here -->
     </div>
    </ template>

     <script>
         export default {
             // Component options here
         }
     </script>
```
<br>

In the User.vue component, we access the parameter value using $route.params.id.This allows us to display the user's ID dynamically based on the URL.

## ✅Step 7: Programmatic Navigation
<br>

Besides using < router - link > for navigation, Vue Router also provides a programmatic way to navigate between routes using the $router object.

For example, to navigate to the / about route programmatically, you can use the $router.push() method:
<br>

```

 methods: {
     navigateToAbout() {
         this.$router.push('/about');
     }
 }
```
<br>

In this code snippet, the navigateToAbout method is called when a button or a specific event is triggered, and it uses $router.push() to navigate to the / about route.

These are the basic steps to get started with Vue Router v4 in Vue.js 3. You can explore more advanced features and concepts in the official Vue Router documentation(https://next.router.vuejs.org/). Remember to customize and extend the code examples based on your specific application requirements.



Let's continue exploring more features of Vue Router v4 in Vue.js 3.

## ✅Step 8: Nested Routes
<br>
Vue Router allows you to create nested routes, which are useful for building complex application layouts.You can nest routes inside other routes by using the children property.

Modify the router.js file to include a nested route for a user's settings:

<br>

```
// ...

 const router = createRouter({
     history: createWebHistory(),
     routes: [
         // ...
         {
             path: '/user/:id',
             name: 'user',
             component: User,
             children: [
                 {
                     path: 'settings',
                     name: 'settings',
                     component: UserSettings
                }
             ]
         }
     ]
 });

// ...

```

<br>

In the code snippet above, we added a nested route for the user's settings under the /user/:id route. The UserSettings component will be rendered when the /user/:id/settings path is accessed.

## ✅Step 9: Route Guards
<br>
Route guards are functions that can be used to control navigation behavior.They allow you to implement authentication, authorization, and other custom logic before navigating to a route.

Vue Router provides three types of route guards: beforeEach, beforeResolve, and afterEach.You can define these guards in the router.js file.

     Here's an example of using the beforeEach guard to check if a user is authenticated before allowing access to certain routes:

<br>

// ...

 router.beforeEach((to, from, next) => {
     const isAuthenticated = // Check if user is authenticated
  
   if (to.name === 'admin' && !isAuthenticated) {
         // Redirect to login page if user is not authenticated
         next({ name: 'login' });
     } else {
         // Allow access to the requested route
         next();
     }
 });

// ...

<br>

In the code snippet above, we use the beforeEach guard to check if the user is authenticated before accessing a route.If the user is not authenticated and the requested route is 'admin', we redirect them to the 'login' route.Otherwise, we allow access to the requested route.

##  ✅   Step 10: Dynamic Route Matching
<br>
Vue Router v4 introduced a new feature called dynamic route matching, which allows you to match routes based on dynamic conditions.This feature is useful when you want to conditionally load different components or layouts based on specific criteria.

Here's an example of using dynamic route matching:

<br>

```

// ...

 const router = createRouter({
     history: createWebHistory(),
     routes: [
         // ...
         {
             path: '/post/:id(\\d+)',
             name: 'post',
             component: Post,
             meta: {
                 requiresAuth: true
             }
         }
     ]
 });

// ...
```
<br>


In the code snippet above, we define a dynamic route / post /: id(\\d +) that matches only if :id is a numeric value.We also added a meta property to the route object, which can be used to add custom metadata to the route.

##  ✅   Step 11: Route Transitions
<br>
Vue Router v4 integrates seamlessly with Vue.js 3's transition system, allowing you to add transition effects when navigating between routes. You can use CSS transitions or third-party animation libraries to create visually appealing route transitions.

Here's an example of adding a fade transition when navigating between routes:
<br>

```

     < template >
    <transition name="fade">
         <router-view></router-view>
     </transition>
    </ template >

     <style>
         .fade-enter-active, .fade-leave-active {
             transition: opacity 0.5s;
 }

       
         .fade-enter, .fade-leave-to {
             opacity: 0;
 }
     </style>

```
<br>

In the code snippet above, we wrap the < router - view > component with a < transition > component.The name attribute specifies the name of the transition, which in this case is "fade".We also define the CSS classes for the fade transition effect.During the enter and leave phases, the opacity is gradually adjusted to create a smooth fade effect.

##  ✅   Step 12: Navigation Guards in Component Options
<br>
Apart from using global route guards, you can also define navigation guards at the component level.This allows you to apply specific guards only to certain components.

In a Vue component, you can define the beforeRouteEnter, beforeRouteUpdate, and beforeRouteLeave methods to handle navigation guards. 
Here's an example of using the beforeRouteEnter guard to fetch data before entering a component:
<br>

```

 export default {
     // Component options here

     beforeRouteEnter(to, from, next) {
         // Fetch data before entering the component
         fetchData().then((data) => {
             next((vm) => {
                 vm.data = data;
             });
         });
     }
 }
```
<br>

In the code snippet above, the beforeRouteEnter guard is used to fetch data from an API before entering the component.Once the data is fetched, it is passed to the next() function using a callback.The callback receives the component instance(vm) and allows you to access and set component data.

These are some additional concepts and features of Vue Router v4 in Vue.js 3. As you continue working with Vue Router, I recommend referring to the official documentation(https://next.router.vuejs.org/) for more details and advanced usage.




Let's continue exploring more features of Vue Router v4 in Vue.js 3.

## ✅Step 13: Named Views
<br>
Vue Router allows you to define multiple named views within a single route, allowing you to render different components in different named view outlets.

In your router configuration(router.js), you can define multiple components within a route using the components property.Each component is associated with a unique named view.
<br>

```

// ...

 const router = createRouter({
     history: createWebHistory(),
     routes: [
         // ...
         {
             path: '/dashboard',
             name: 'dashboard',
             components: {
                 default: Dashboard,
                 sidebar: Sidebar,
                 header: Header
             }
         }
     ]
 });

// ...

<br>

```

In the code snippet above, we define a route named 'dashboard' with multiple components assigned to different named views(default, sidebar, and header).

// To render these named views in your template, use the < router - view > component with the name attribute to specify the named view outlet.


//     < template >
//     <div>
//         <router-view></router-view> <!-- Renders the default view -->
//         <router-view name="sidebar"></router-view> <!-- Renders the sidebar view -->
//         <router-view name="header"></router-view> <!-- Renders the header view -->
//     </div>
// </ >

// ✅    Step 14: Navigation Events
// Vue Router emits various navigation events that allow you to perform actions before, during, or after navigation.You can listen to these events and execute custom logic accordingly.

// To listen to navigation events, you can use the $router object in your components.


 export default {
     mounted() {
         this.$router.beforeEach((to, from, next) => {
             // Perform actions before each route navigation
         });

         this.$router.afterEach((to, from) => {
             // Perform actions after each route navigation
         });
     }
}

```
<br>

In the code snippet above, we use the $router.beforeEach() and $router.afterEach() methods to register navigation event listeners.These methods allow you to execute custom logic before and after each route navigation.

## Step 15: Lazy Loading Routes

<br>
Lazy loading routes is a technique used to optimize the initial loading time of your application by splitting your code into smaller chunks and loading routes on - demand.

Vue Router v4 supports lazy loading routes using dynamic imports.

```
const About = () => import('./components/About.vue');
const Contact = () => import('./components/Contact.vue');
```

In the code snippet above, we use the dynamic import syntax to lazily load the About and Contact components when they are needed.

Lazy loading routes can significantly improve the performance of your application by reducing the initial bundle size and loading only the necessary components when required.

These are some additional concepts and features of Vue Router v4 in Vue.js 3. I encourage you to explore the official documentation(https://next.router.vuejs.org/) for further details and advanced topics.

Let's continue exploring more features of Vue Router v4 in Vue.js 3.

## ✅Step 16: Navigation Duplicates
<br>
By default, Vue Router allows navigating to the same route multiple times consecutively.However, you can configure it to prevent navigating to the same route twice in a row by using the replace option in the router.push() method.

```
this.$router.push({ path: '/dashboard', replace: true });
```
<br>
In the code snippet above, the replace option is set to true when using router.push().This ensures that navigating to the same route consecutively will replace the current entry in the browser's history stack instead of creating a new entry.
<br>
## ✅Step 17: Scroll Behavior
<br>
When navigating between routes, Vue Router automatically scrolls to the top of the new page.However, you can customize the scroll behavior by defining a scrollBehavior function in your router configuration.
<br>

```

 const router = createRouter({
     history: createWebHistory(),
     routes: [

// ...
     
     ],
     scrollBehavior(to, from, savedPosition) {
         if (savedPosition) {
             // Scroll to saved position (e.g., when using the browser's back/forward buttons)
             return savedPosition;
         } else {
             // Scroll to top
             return { top: 0 };
         }
     }
 });

```
<br>

In the code snippet above, the scrollBehavior function is defined to customize the scroll behavior.If there is a saved position(e.g., when using the browser's back/forward buttons), it scrolls to the saved position. Otherwise, it scrolls to the top of the page.

<br>

## ✅ Step 18: Error Handling
Vue Router provides error handling capabilities, allowing you to handle specific routing errors or global errors that occur during navigation.

To handle specific errors, you can use the beforeEach guard and call the next function with an error parameter.
<br>

```
 router.beforeEach((to, from, next) => {
     if (to.meta.requiresAuth && !isAuthenticated()) {
         next({ name: 'login', params: { redirect: to.fullPath }, replace: true });
     } else {
         next();
     }
 });

```
<br>

 In the code snippet above, if a user tries to access a route that requires authentication but is not authenticated, we redirect them to the login page with the original route as a parameter(redirect) and replace the current history entry.

To handle global errors during navigation, you can listen to the router.onError event.

<br>

```
 router.onError((error) => {
     // Handle the error
 });

```

<br>

In the code snippet above, the router.onError event listener allows you to handle global errors that occur during navigation.

<br>

## ✅    Step 19: Hash Mode
<br>
By default, Vue Router uses the HTML5 History API for clean URLs.However, if you need to support older browsers or server configurations that don't support HTML5 History API, you can switch to hash mode.

To enable hash mode, update your router configuration:
<br>

```
 const router = createRouter({
     history: createWebHashHistory(),
     routes: [
         // ...
     ]
 });

```
<br>

In the code snippet above, we use createWebHashHistory() instead of createWebHistory() to enable hash mode.

Hash mode adds a hash symbol(#) to the URLs and relies on the hashchange event to handle route changes.This allows older browsers and server configurations to handle client - side routing.

These are some additional concepts and features of Vue Router v4 in Vue.js 3. I encourage you to refer to the official documentation(https://next.router.vuejs.org/) for more details and advanced usage.



