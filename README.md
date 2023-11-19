"# vue- note"

Learned about vue js

### Set up
1. open command panel: 

```js
yarn create vite project-name

npm create vite project-name

```
2. Go to project Directory: 

```
cd project-name
```
3. Install dependency 

```
yarn install 

npm install

```
3. For running project:

```
yarn dev

npm run dev

```


### Showing Data from variable to template

```javascript
<script setup>
const message = 'Welcome. Get ready to';
</script>

<template>

<h1 class="text-4xl"> **{{ message }}** </h1>

</template>










