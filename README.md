# Rock Paper Scissors

## Experience the classic game of Rock Paper Scissors in a sleek and interactive online format. Play against the computer and test your luck!

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
- [Got Feedback for Me?](#got-feedback-for-me)

## Overview

### The Challenge

Engage in the timeless game of Rock Paper Scissors with a modern, responsive design. Play against the computer and see if you can outsmart it!

Users should be able to:

- View an optimal layout depending on their device's screen size
- See hover states for interactive elements
- Enjoy smooth animations and an engaging user experience

### Screenshot

![Design Preview](./design/desktop-preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/soumya-123-code/Rock-paper-scissors_frontend_project)
- Live Site URL: [Live Site](https://rock-paper-scissors-frontend.netlify.app/)

## My Process

### Built With

- HTML5
- CSS3
- JavaScript

All necessary assets are in the `/design` folder. Additionally, the `style-guide.md` file contains useful details such as color palettes and fonts.

### What I Learned

- Developing game logic for Rock Paper Scissors in JavaScript
- Enhancing UI with CSS animations and transitions
- Handling user inputs and dynamically generating computer choices

This CSS snippet played a key role in improving my understanding of positioning and transitions:

```css
.game-body__circle-container-paper {
    position: absolute;
    left: 0;
    top: -6.5rem;
}
.game-body__circle-container-scissors {
    position: absolute;
    right: 0;
    top: -6.5rem;
}
.game-body__circle-container-rock {
    position: absolute;
    left: 50%;
    bottom: 6rem;
    transform: translateX(-50%);
}
.game-body__circle-container-paper,
.game-body__circle-container-scissors,
.game-body__circle-container-rock {
    transition: all 0.5s ease-in-out;
}
```

### Continued Development

Through this project, I identified key areas for improvement:

- Mastering CSS Flexbox and Grid for better layouts
- Deepening my knowledge of JavaScript async/await and Fetch API
- Exploring game development concepts further

I aim to refine these skills in future projects to enhance my web development expertise.

### Useful Resources

- [MDN CSS Hover States](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover) - A great reference for understanding CSS hover states.

## Author

**Soumya Ranjan Nayak**

- Website - [Portfolio](https://soumya-123-code.github.io/itsmesoumya)
- GitHub - [@soumya-123-code](https://github.com/soumya-123-code/)
- LinkedIn - [Soumya Ranjan Nayak](www.linkedin.com/in/soumya-ranjan-nayak-50069a15a)

## Acknowledgments

Thanks to the open-source community and various learning platforms that support developers in enhancing their skills.

## Got Feedback for Me?

I appreciate constructive feedback! If you have suggestions, feel free to reach out at soumya050794@gmail.com.

If you enjoyed this project, feel free to share it with others.

**Happy coding!** ☺️🚀

