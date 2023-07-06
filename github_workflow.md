# GitHub workflow

HemengoDistrib Back\_end application  with Docker, Mysql, NodeJs.



## Make your feature

#### 1. Make sure your are on the develop brach

```bash
    git checkout develop
```

#### 2.Update your develop branch

```bash
    git pull origin develop
```

**3.Create your feature branch**

```bash
    git checkout -b feature/1.0.5
```

**4.Make your changes**

<div align="left">

<figure><img src=".gitbook/assets/Screenshot_20230627_152856.png" alt="" width="188"><figcaption></figcaption></figure>

</div>

**5.Commit your changes**

```bash
    git add .
    git commit -m "Add fonction XXX"
```

**6.Checkout to develop branch**

```bash
    git checkout develop
```

**7.Update your develop branch**

```bash
    git pull origin develop
```

**8.merge**

```bash
    git merge --no-ff feature/1.05
```

**10.Push develop to GitHub**

```bash
    git push origin develop
```

## Run on Development mode:

This will install all dependencies

```bash
    ./run_dev
```

Development utilities:

* [nodemon](https://www.npmjs.com/package/nodemon)
  * nodemon is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.
* [eslint](https://www.npmjs.com/package/eslint)
  * ESLint is a tool for identifying and reporting on patterns found in ECMAScript/JavaScript code.
* [mocha](https://www.npmjs.com/package/mocha)
  * ☕️ Simple, flexible, fun JavaScript test framework for Node.js & The Browser ☕️



## Testing

We're using Mocha and Chai for unit tests.

#### Test unit mode:

```bash
    ./run_test_unit
```

#### Test integration mode:

```bash
    ./run_test_int
```

## This Readme:

direct link:

[https://hemengodistrib.gitbook.io/readme/](https://hemengodistrib.gitbook.io/readme/)

Edition link:

[https://app.gitbook.com/o/y6FaMG4lcnLoVhxgPu5B/s/qDSVtzkRBF5vWhG5slnf/](http://localhost:5000/o/y6FaMG4lcnLoVhxgPu5B/s/qDSVtzkRBF5vWhG5slnf/)
