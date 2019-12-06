

# QUMODE

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![Wire](https://github.com/qumode/qumode-visualizer/blob/master/banner.png)

### What? 
Qumode is a visual programming language that allows users to perform algorithmic operations and subroutines with graphical tools. Quantum Circuit Diagrams are a helpful visual language that is more readible than writing down matrices. Circuit composers help us understand quantum algorithms. 

Qumode will provide a visual programming language that uses the standard circuit conventions for making operations on the circuits and qubits to help solve problems and for learning through exploration. 

### Why?
Most computing paradigms in theoretical physics are generally based on diagrams infering a particular phenomenon, quantum gates  to Feynmann diagrams, and category theory are represented graphically.
Qumode was built on a principle that people should not be limited by the tools they use and that more people should be able to operate quantum computing as accessible as classical computing.

In quantum computing we find more artifacts of these method, for example tensor diagrams and gates can easily be represented as diagrams and it suffices as a good practice. For instance a solid line depicts a qubit register,and boxes resemble gates.
 
### Who


Quantum Computing affords us the ability to think of computation more often diagrammatically. Qumode is a language that harnesses this principle and hopefully anyone interested in quantum computation can approach it with this method. 

> “It now ceases to be important to maintain a distinction between upper and lower indices.”
– Roger Penrose, 1971




Qumode is a repository containing a set of libraries (artifacts) that makes it super easy to build blazing fast & reactive visual programming language for the web.

It offers a core data processing framework and a library with React-components that will get you started. Take a look at the underlying artifacts to learn more about Wire and its offerings.

QUMODE also depends on node packages [Quantum Tensor Networks](https://github.com/stared/quantum-tensors). This is currently under development.

### QUMODE Artifacts

-   [Q-Core](artifacts/wire-core): The core processing framework
-   [Q-UI](artifacts/wire-ui): A React-library with suitable UI components
-   [Q-Editor](artifacts/wire-editor): An example of a visual node editor built with Wire

### Contributions

Contributions are more than welcome. Please let me know if you want to become a collaborator on this project.
If you find bugs, issues or ideas of improvement, let me know by opening an Issue.

### Core

- [React](https://facebook.github.io/react/) (w/o JSX)
- [Redux](http://redux.js.org/)
- [React DnD](http://react-dnd.github.io/react-dnd/)
- [React Select](http://jedwatson.github.io/react-select/)
- [reselect](https://github.com/reactjs/reselect)

I'm currently *not* using [RxJS](http://reactivex.io/rxjs/), which Jonas
used and commended in his talk. I may still elect to try it out (see Todo
section above), but think for the time being, Redux should be sufficient
without adding additional mental overhead of where state is coming from.

### Development

- [Babel](https://babeljs.io/)
- [budō](https://github.com/mattdesl/budo)
- [standard](https://standardjs.com/)
- [tape](https://github.com/substack/tape)


