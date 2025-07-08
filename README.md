<h1 align="center">⚛️ React</h1>

- ⚠️ React is not a framework — it's a **JavaScript library** developed by **Facebook** to handle **efficient DOM manipulations**, resulting in fast and responsive UIs.

---

<img src = "img\libvsframe.png">

### What is CDN?

- It is a mechanism to request resources from an external server so that the **latency rate is reduced**.

### What is CORS?

- It is a mechanism where **two applications** are running on **different servers**, allowing scripts to share data between them.
- If a script asks for a resource, the other server responds accordingly.
- If it involves storing or accessing **critical data**, the server may request **authentication rights**.
- This mechanism is referred to as **Cross Origin Resource Sharing**.

#### CDN Links for React to Use in Our Project

```html
<script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
```

<img src = "img\cdn.png">


#### Creating an element

```js
const element = React.createElement(
    type, //HTML tag name or React component
    props, //objects with props/attribute or null
    ...childrem, //child elements or text
)
```
#### Accessing the DOM
```js
const container = document.getElementById('idName');
cosnt root = ReactDOM.createRoot(container);
```
<img src = "img\render.png" width="200px">

#### Uasge of {} in React.createElement
- It is used to give the attributes to the elements we create dynamically.

> 💻 Related Code : 
[createElement.html](basic/createElement.html)

