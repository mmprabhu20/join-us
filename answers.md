# `twob || !twob`

Please put your responses in a file
called `answers.md`. And yes! our humor is dry 🏜

## Introductions

- Who are you? What do you like building?

```
I'm Manikanda Prabhu from chennai,working as a full stack developer in ocean softwares,chennai and
 I did my Post Graduation in Anna University and like to build softwares like e-commerce and business softwares in
 MERN stack.

```

- Do you own a PC and have a good internet
  connection? Let's hear those specs 💪!
  ```
  Yes,I own a PC and also have a good internet connection.
  I have Dell laptop with i5 7th Generation and 8GB RAM and 512 SSD
  ```
- Your stackoverflow, linkedin, personal site.
  Anything you'd want us to see.
  ```
  Stackoverflow: -
  linkedin:https://www.linkedin.com/in/manikanda-prabhu-ba0082200/
  personal site: -
  ```
- What programming languages have you messed around with?
  ```
  javascript
  ```
- What sort of tooling is on your machine?
  - Programming languages, compilers, runtimes etc
  ```
  ReactJS,NodeJS ,MongoDB,MySQL,ExpressJS,Javascript,Html,CSS,Bootstrap,
  ```
  - What OS do you run?
  ```
  Windows
  ```
  - What editor/IDE do you use?
  ```
  Visual Studio
  ```
- Are you more into front-end or back-end? (If you're
  into web development).
  ```
  Both
  ```
- Are you interested in AI/ML, Systems Programming
  or anything outside your current domain.
  ```
  Yes,I'm interested in AI/ML
  ```
- What are you learning now?

```
Blockchain
```

## Let's hack!

Please answer in the language that you're
applying for. We're a JS shop, so answers in JS
get extra 🍪

- Find the longest word in a string.

  - Given `The quick brown fox jumped over the lazy dog` is the input to your function, it should return `jumped`.

```
const findthelongestword=(input)=> {
  var words = input.split(' ');
  var longestword = '';
  for (var i = 0; i < words.length; i++) {
    if (words[i].length > longestword.length) {
      longestword = words[i];
    }
  }
  return longestword;
}

var input = 'manikanda prabhu';
console.log(findthelongestword(input));

```

- Repeat a string `n` times.

  - If `abc` and `3` are the arguments to your function, it shoudl return `abcabcabc`

```
const getrepeatstring=(input, repeatvalue)=> {
  return input.repeat(repeatvalue);
}

var input = 'asdf';
var repeatvalue = 4;
console.log(getrepeatstring(input, repeatvalue));

```

- Remove duplicates in an array

  - If `[1, 20, 3, 1, 3, 3]` is the input to your
    function, it should return `[1, 20, 3]`

```
const removeuplicatevalues=(input)=> {
  var values = [...new Set(input)];
  return values;
}

var input = [1,1,2,2,3,3,4,4,4];
console.log(removeuplicatevalues(input));

```

- Remove falsy values

  - If `[42, "everything", "", 2, false, "everything"]` is the input to your function, it should return `[42, "everything", 2, "everything"]`

```
const removefalsyvalues=(input)=> {
  return input.filter(Boolean);
}
var input = [42, "everything", "", 2, false, "everything"];
console.log(removefalsyvalues(input));

```

- Truncate a string

  - If `'Absolute victory'` and `3` are the inputs to
    your function, it should return `Abs...`

        ```
        const truncatestring =(input, truncateValue)=> {

    if (input.length > truncateValue) {
    return input.slice(0, truncateValue) + '...';
    }
    return input;
    }
    var input = 'Absolute victory';
    var truncateValue = 3;
    console.log(truncatestring(input, truncateValue));  
     ````

## Notes

- We look for style and patterns when reviewing submissions.
- Please **do not** lift answers from somewhere and
  send it to us verbatim.
- Do show off your git kung-fu. Multiple commits? Branch naming?
- If you can't answer everything, thats ok too! Go ahead and raise that PR anyway.

> **வாழ்த்துகள்!** 🙏
