# History Hack Pack
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This "extension pack" will install several tools that may be helpful to you in _HIS393: Digital History_ at the University of Toronto. The MIT license above applies only to this extension pack; indiviual extensions are governed by their own licenses. 

- The [Live share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) extension allows you to edit collaboratively with someone else.  This is quite new, we'll see if we can make use of it in class. 
- [Live Server Preview](https://marketplace.visualstudio.com/items?itemName=negokaz.live-server-preview) shows you what your code will look like once it's on a webserver and being observed in a browser
- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) makes it easier to prettify your code
- [github Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) integrates VSCode with Github
- [Mocha Sidebar](https://marketplace.visualstudio.com/items?itemName=maty.vscode-mocha-sidebar) runs tests from inside VSCode. It's really nice when it works.
- [NPM](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) allows yo uto run node and npm commands right from the editor without opening a terminal.
- [Markdown Shortcuts](https://marketplace.visualstudio.com/items?itemName=mdickin.markdown-shortcuts) adds some hints for markdown syntax.
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) gives fnatastic hints about how to improve your JavaScript code.
- [HTML Hint](https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint) helps you to write better HTML
- [Org-mode](https://marketplace.visualstudio.com/items?itemName=tootone.org-mode) enables syntax highlighting for some of the README files in our repositories.
- [Quokka](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode) is a powerful tool that does **some** evaluation of javascript from inside your editor.  For instanc,e you can use it to check the value of a variable:

  ``` javascript
  function returnArray (first, second, third) {
    // you can define the array using "new Array ()" or just "[ , , ]"
    // don't forget to return it
    // return ; // add the falue here!
  }
  
  let a = returnArray (1, 3,5);
  a
  ```
  Quokka will show the value of `a` in your Vscode editor window, like this: 
  ![](./images/quokka.png)
  Check the Quokka docs for more info
**Have Fun!**
