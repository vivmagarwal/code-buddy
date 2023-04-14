# Code-Buddy

Code-Buddy is a simple and lightweight online coding playground designed for quick prototyping and testing of HTML, CSS, JavaScript, and Jest-based tests. It allows users to write code in separate textareas for each language and instantly view the output in a live preview.

![picture 1](https://res.cloudinary.com/drxuo575c/image/upload/v1681447018/coding-problems/a64883bfdab3eda8909d2b3ca01807c40927c3f54e3934ef02e6f278040d5507.png)  

## Features

- Separate textareas for HTML, CSS, JavaScript, and Jest tests
- Live preview of HTML, CSS, and JavaScript
- Run Jest tests and view the results in real-time
- No need to sign up or log in - just start coding!

## Getting Started

To start using Code-Buddy, simply open the `index.html` file in your browser. You'll see textareas for HTML, CSS, JavaScript, and Jest tests, as well as buttons to run the code and view the live preview.

### Default Values

Code-Buddy comes with some default values to help you get started:

HTML:
```html
<h1>test</h1>
```

CSS:
```css
h1 { color: red; }
```

Javascript: 
```js
function add(a, b) { return a + b }
```

Jest Tests: 
```js
describe('test domo', () => {
  it ('Verify if are received and returned only numbers', () => {
    expect(2+3).toBe(5);
  });
});
```

## Usage
- Write your HTML, CSS, and JavaScript code in their respective textareas.
- Click the "Run" button to update the live preview.
- Write your Jest tests in the "Tests" textarea.
- Click the "Test" button to run the tests and view the results.

## Contributing
We welcome contributions to Code-Buddy! If you'd like to contribute, please follow these steps:

- Fork the repository.
- Create a new branch for your changes.
- Make your changes and commit them to your branch.
- Submit a pull request with a description of your changes.

## License
Code-Buddy is released under the Server Side Public (SSPL) License.
