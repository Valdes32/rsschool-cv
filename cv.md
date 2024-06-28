# Vladislav Kulygin

---

### Contact information:

**Phone:** +90 (506) 259 94 75<br>
**E-mail:** vladislav.kulygin.191@gmail.com<br>
**Telegram:** @valdes191<br>
[LinkedIn](https://www.linkedin.com/in/vladislav-kulygin-917729252/)<br>

---

### Briefly About Myself:

I want to be Front-End Development

---

### Skills and Proficiency:

- HTML5, CSS3
- Git, GitHub
- VS Code
- Adobe Photoshop, Illustrator, Figma

---

### Code example:

**Peak array index KATA from CODEWARS:** ''Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.''

```javascript
function peak(arr) {
  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr
      .slice(0, i)
      .reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr
      .slice(i + 1)
      .reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```

---

### Courses:

- HTML and CSS Tutorials on the [freeCodeCamp](https://www.freecodecamp.org/) (in progress)
- JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/) (in progress)
- RS Schools Course «JavaScript/Front-end» (in progress)

---

### Language:

**English level** A2
