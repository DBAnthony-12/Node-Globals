# Node-Globals
Node.js provides a set of global objects and variables that are available throughout the application without the need for explicit declaration.

Key global in Node.js
--------------------------
	Process:  Provides information about the current Node.js process, environment variables, and methods to interact with the process.
	Console: Allows printing messages to the console for debugging and logging purposes.
	Require: Used to include modules and packages in Node.js applications.
	Module: Represents the current module and provides methods and properties to interact with the module system.
	__dirname: Represents the directory name of the current module.
	__filename: Represents the file name of the current module.
	Global: Acts as a global namespace for variables and functions accessible from any module.

These global objects simplify common tasks in Node.js development and provide essential functionality for building applications. However, it is important to use global variables cautiously to avoid potential conflicts and maintain code readability and maintainability.

Third-Party Packages
---------------------------
Node introduces the Node Package Manager (NPM), a tool for managing packages, which are collections of one or more modules. Third party packages are also known as modules or libraries which are pre-written code components created by developers and made available for use in software development. In context of node.js, third party packages are managed using NPM (Node Package Manager) and are typically installed and imported into projects as dependencies. Numerous functionalities are covered by these packages, such as web frameworks, database connectors, authentication systems, and utility functions. Using third-party packages gives you access to tested and dependable solutions that are kept up to date by the larger community, which can greatly accelerate development, improve code quality, and expand the capabilities of apps. 

Package.json Files
------------------------
An essential part of Node.js projects is the package.json file, which acts as a manifest for the project and its dependencies. It also includes a list of all the dependencies needed for the project to function, both development and direct, as well as those needed for building, testing, and other development activities. Scripts that describe different tasks for controlling the project, including launching the server, executing tests, or creating the project, are also included in the package.json file. A key component of Node.js development is the package.json file, which offers crucial project setup and information while guaranteeing uniformity and reproducibility across many environments.


