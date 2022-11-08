# Frontend Mentor - Todo App Solution

This is a solution to the [Todo app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/todo-app-Su1_KokOW). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Add new todos to the list
- Mark todos as complete
- Delete todos from the list
- Filter by all/active/complete todos
- Clear all completed todos
- Toggle light and dark mode
- **Bonus**: Drag and drop to reorder items on the list

### Screenshot

![Dark Mode Desktop Screenshot](../todo-app-fm/src/assets/img/dark-mode-screenshot-todo-app-fm.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [https://dinadess.github.io/todo-app-fm/](https://dinadess.github.io/todo-app-fm/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Vue JS](https://vuejs.org/) - Vue Framework (Options API | Pinia)
- [TailwindCSS](https://tailwindcss.com/) - TailwindCSS
- [Vue Draggable](https://github.com/SortableJS/vue.draggable.next) - For drag and drop feature

### What I learned

CSS [caret-color](https://developer.mozilla.org/en-US/docs/Web/CSS/caret-color) property that helps you change the text cursor's color of an input.

```css
input {
  caret-color: var(--brightBlue);
}
```

### Continued development

This was my first solo project using VueJS and TailwindCSS. There are much more to learn and I'll keep practicing.

### Useful resources

- [How to persist a pinia store in localStorage using Vue 3](https://github.com/vuejs/pinia/issues/309) - This helped me to save my store into localStorage. It took some time before working as I was mounting the app before setting it.
- [AutoAnimate](https://auto-animate.formkit.com/) - This is a great utility for animating JS-based apps. I included it in the animation of the todos i.e. when adding or removing a todo, there was a smooth animation following but I ended up not using it as it was not working well with the drag-n-drop feature.
- [Deploy a Vue App to Github pages](https://learnvue.co/tutorials/deploy-vue-to-github-pages)

## Author

- Frontend Mentor - [@dinadess](https://www.frontendmentor.io/profile/dinadess)
