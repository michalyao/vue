### Basic
prefixed with v-
reactive behavior to the rendered DOM
message is a binder. to bind value on this element's title attribute

``` javascript
<span v-bind:title="message">
    Hover your mouse over me for a few seconds to see my dynamically bound title!
</span>
```

- `vbind-{attr}:{var}`=""
- `v-if`=""
- `v-for`= "var in array"
- `v-on`= "method"
- `v-model`=""

### Components

 pass data from the parent scope into child components
 
``` javascript

Vue.component('name', {
  //component <template>
})

```