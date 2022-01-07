#### Introduced

A simple function help read all file path in a dir, support for multiple tires.

You can `require` or `import` these files or do something else for them.

Just use `path` and `fs` module in **node**.

#### How to use

replace `dir` with the real Directory path you need to read.

```
const read = require('read_all_file');

const arr = read(dir); // you path

arr.forEach(filePath => console.log(filePath) )
```