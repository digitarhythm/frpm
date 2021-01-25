# frpm
Frontend library manager.  
If there is an "include" entry in the "package.json" of a package, a symbolic link will be created in "node_modules/.include/".  
If the template engine used in node.js is designed to load the libraries in "node_modules/.include", it will be possible to manage them centrally.

# Usage
* frpm Install

```bash
$ npm i frpm
```

* Library install(example)

```bash
$ frpm -i indexstorage
```
