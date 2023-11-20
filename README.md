**VUE NOTE**
A text bank of vue js journey.....

# Setting up
**1. open command panel: 
**
```js
yarn create vite project-name

npm create vite project-name

```
**2. Go to project Directory: **

```
cd project-name
```
**3. Install dependency: 
**
```
yarn install 

npm install

```
**3. For running project:**

```
yarn dev

npm run dev

```

# Showing Data from variable to template
**- use {{ variable name/ function name }} to show data.
- install Volor to get all extension. 
**
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
*** Must destructure the object: date=>message=>**

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
** - v-html can bind the html**
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
