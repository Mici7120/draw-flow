# draw-flow
Visual node editor code challenge.

Create a tool to learn to program visually
The tool should allow you to create very simple programs using a visual editor of nodes.

In this case, for example, the output of “Add” could be associated with an “Assign” node that would assign its value.
At a minimum, the editor must support:
- Code blocks
- Assignment
- Basic mathematical operations
- If-Else control structure
- Basic For control structure (from-to)

The editor must ultimately generate Python code and must be able to evaluate it
In a simple way, the editor allows you to create simple ASTs (https://en.wikipedia.org/wiki/Abstract_syntax), convert them to code and evaluate them.

Part 1: Create Node Editor
The editor must be built with the Vue.JS framework and the editor with DrawFlow
(https://github.com/jerosoler/Drawflow).
It must allow programming using the keyboard and mouse, it must also allow save and load programs from the backend

Part 2: Code visualization
The created nodes must be converted to Python code and displayed in the interface.
It should be allowed to run the code and display the results.

Part 3: Backend
The backend must be a REST API composed of endpoints to:
- Save the program
- List saved programs
- Get the program
- Run the program

Optional
If you dare, add support for other programming languages.
Other ideas would be other data types such as “string”, and functionalities such as making HTTP requests

Backend Language: Go
Database: Dgraph
API Router: chi
Interface: Vue.js DrawFlow https://github.com/jerosoler/Drawflow
