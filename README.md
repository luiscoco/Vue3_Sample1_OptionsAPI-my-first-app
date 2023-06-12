# OptionsAPI my-first-app

In Vue.js version 3, components are the building blocks of the user interface. They encapsulate the HTML, CSS, and JavaScript logic for a particular part of the UI and can be reused throughout the application.

There are two ways to define components in Vue.js version 3: using the Options API and using the Composition API.

The Options API is the traditional way of defining Vue components and is based on object options.
Here's a simple code sample using the Options API:

```
<template>
  <div>
    <p>{{ message }}</p>
    <button @click="updateMessage">Update Message</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello, Vue!'
    };
  },
  methods: {
    updateMessage() {
      this.message = 'Hello, Vue updated!';
    }
  }
};
</script>
```
In the above example, we define a component with a template containing a paragraph element and a button. The data function returns an object that contains the message property. The methods object contains the updateMessage method, which updates the message property when the button is clicked.



## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
