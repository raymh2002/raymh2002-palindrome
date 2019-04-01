This is a sample NPM module created by Ray Harvey for Learn Enough JavaScript to Be Dangerous.

This module is to be used as follows:

$ npm install --global raymh2002-palindrome
$ vim test.js
let Phrase = require("raymh2002-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
