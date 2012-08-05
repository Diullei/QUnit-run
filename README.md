QUnit-run
=========

Run your QUnit tests "out-of-browser" using node.js.

1) Create a test file like this example:

```javascript
module('test module');
test('test example', function(){
	ok(true, 'test is ok');
});
```

2) Save this file as test.js.

3) Run command line ```node qunit-run .\test.js``` to execute this test and have this output:

![Valid XHTML](https://raw.github.com/Diullei/QUnit-run/master/output.png)
