# How to Use package.json
<hr>
<h2>What is package.json?</h2>
<p>The <i>package.json</i> file is the center of any Node.js project or npm package. 
It stores information about your project. 
It consists of a single JSON object where information is stored in key-value pairs. 
There are only two required fields; <i>name</p>i> and <i>version</i>, but it’s good practice to provide additional information</p>

### How to create a package.json file form the terminal
- Use `npm init` command: this will run a giuded setup.
- Using `npm init -y` will generate the file with having it ask any questions.
  
### author field
- This is one of the most common pieces of information in the `package.json` file.
- It specifies who created the project, and can consist of a string or an object with contact or other details.
- An object is recommended for bigger projects, but a simple string like the following example will do for this project:
	```
	"author": "Jane Doe",
	```
### Challenge-1-Task
- Add your name as the `author` of the project in the `package.json` file.

#### NOTE: Remember that you’re writing JSON, so all field names must use double-quotes (") and be separated with a comma (,).
<hr>

`HINTS`
> For this challenge:
- I used FreeCodeCamp's Gitpod Starter Project
- I simply typed `"author": "my_name",` in the `package.json` file just above the `"name": "fcc-learn-npm-package-json",`
- After that, I copied the `Simple Browser` link and pasted it under `Solution link` <a href="https://www.freecodecamp.org/learn/back-end-development-and-apis/managing-packages-with-npm/how-to-use-package-json-the-core-of-any-node-js-project-or-npm-package">here</a>

<h5>Happy Coding!</h5>

**Mercy**

