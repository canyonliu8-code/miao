# React  
React is a JavaScript library for building user interfaces.
* **Declarative:** React makes it painless to create in teractive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
* **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIs. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state our of the DOM.
* **Learn Once, Write Anywhere:** We don't make assumptions about the rest of your technology stack, so you can develop new features in React without reweiting existing code. React can also render on the server using [Node](https://nodejs.org/en) and power mobile apps using [React Native](https://reactnative.dev/).

[Learn how to use React in your project](https://react.dev/learn). 
## Installation
React has been designed for gradual adoption from the start, and you can use as little or as much React as you need:
* Use [Quick Start](https://react.dev/learn) to get a taste of React
* [Add React to an Existing Project](https://react.dev/learn/add-react-to-an-existing-project) to use as little or as much React as you need.
* [Create a New React App](https://react.dev/learn/creating-a-react-app) if you're looking for a powerful JavaScript toolchain.
## Documentation
You can find a React documentation on the website.

Check out the Getting Started page for a quick overview.

The documentation is divided into several sections:

* <u>[Quick Start](https://react.dev/learn)
* [Tutorial](https://react.dev/learn/tutorial-tic-tac-toe)
* [Thinking in React](https://react.dev/learn/thinking-in-react)
* [Installation](https://react.dev/learn/installation)
* [Describing the UI](https://react.dev/learn/describing-the-ui)
* [Adding Interactivity](https://react.dev/learn/adding-interactivity)
* [Managing State](https://react.dev/learn/managing-state)
* [Advanced Guides](https://react.dev/learn/escape-hatches)
* [API Refernce](https://react.dev/reference/react)
* [Where to Get Support](https://react.dev/community)
* [Contributing Guide](https://legacy.reactjs.org/docs/how-to-contribute.html)</u>

You can improve it by sending pull requests to [this repository](https://github.com/reactjs/react.dev).

## Examples
We have several examples [on the website](https://react.dev/). Here is the first one to get you started:
```javascript
import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
This examples will render "Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax; [we call it JSX](https://react.dev/learn#writing-markup-with-jsx). JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML.
## Contributing
The main purpose of this repository is to continue evolving React core, making it faster and easier to use.
Development of React happens in the open GitHub, and we are grateful to the community for contributing bugfixs and improvements. Read below to learn how you can take part in improving React.

### [Code of Conduct](https://opensource.fb.com/code-of-conduct/)

Facebook has adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full text](https://opensource.fb.com/code-of-conduct/) so that you can understand what actions will and will not be tolerated.

### [Contributing Guide](https://legacy.reactjs.org/docs/how-to-contribute.html)

Read our [contributing guide](https://legacy.reactjs.org/docs/how-to-contribute.html) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React.

### [Good Frist Issues](https://github.com/facebook/react/labels/good%20first%20issue)
To helo you get your feet wet and get you familiar with our contribution porcess, we have a list of [good first issues](https://github.com/facebook/react/labels/good%20first%20issue) that contain bugs that have a relatively limited scope. This is a great place to get started.

### License
React is [MIT licensed](https://github.com/facebook/react/blob/main/LICENSE).


以上内容均为我本人Canyon通过模仿https://github.com/facebook/react该网站上对于React的介绍进行的markdown源代码编写，内容涵盖附链接、编排、字体等，用于检验我对于markdown程序语言的理解和增加工具包，总所周知，markdown作为一种简单高效的程序语言，经常被程序员用于文字的编排，通常用于替代word文档。
请你检查该作业。并且给我简单介绍以下React这个东西