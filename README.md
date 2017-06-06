# A custom [Skulpt](https://github.com/skulpt/skulpt)

# Diff from Origin

- Turtle.py in standard python 3 mode
- full funtional example with python 3 as default

# Build

1. Install node.js and Python 2 (required to run the build scripts)
2. `npm install`
3. `npm run build`
5. Result: `dist/skulpt.min.js` and `skulpt-stdlib.js`

# Intro

Skulpt is a Javascript implementation of Python 2.x. and Python 3.x. To Turn on the Python 3 support, just run in the global enviroment.

```js
Sk.python3 = true;
```

## Available Function

- math
- random
- turtle
- time (partial)
- random (partial)
- urllib (partial)
- unittest
- image
- DOM (partial)
- re (partial)

- builtin types (list, tuple, string, etc) are not subclassable
- Implement decorators

# Origins

Skulpt is the brainchild of Scott Graham.  See [Skulpt.org](http://skulpt.org) for some early demos of skulpt in action.

Brad Miller has been shepherding the development since sometime in 2010/2011.

We are coordinating sprints on some of the ideas below, builtins, stdlib, third party modules, and core performance [here](https://github.com/skulpt/skulpt/issues/400). 



## Acknowledgements

As time goes on its getting more dangerous to try to acknowledge everyone who has contributed to the project.  And, after all, this is git, so their names are all in the historical record.  But there are a few to call out.

* First and foremost to Scott Graham for starting the original project.
* Bob Lacatena for lots of work on Python longs
* Charles Severence for bug fixes and the re module.
* Leszek Swirski and Meredydd Luff for Suspensions
* Albert-Jan Nijburg for countless bug fixes and process improvements
* Ben Wheeler for the new and improved turtle module
* Scott Rixner and students for many bug fixes and improvements
* Of course, The complete list is here:  https://github.com/skulpt/skulpt/graphs/contributors
