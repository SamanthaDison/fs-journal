# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
Interpolations using {{}} to dynamically render data
V-bind to bind ceratin class attributes or properties to elements ":"
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single page application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
SPA'S are faster to load and more responsive
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
Calls methods upon page load
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
The v-model attribute is a way of creating a two way binding between the user input and the vuejs component. Typically used for input fields and form submissions
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
For calling methods upon actions by the user:
@click="deleteTask" will delete task when user clicks that element
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if; v-else
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
To be able to assign a unique attribute to elements on the page such as an ID; allows for the user to manipulate data uniquely
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
<slot> is typically used for modals and/or form injections. By placing a <slot> within a components template; you may reuse the same component by instead dynamically rendering the <slot> attributes.
```