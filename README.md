# Step Wizard

![Step Wizard, HTML and CSS only](https://aston-agency.imgix.net/step-wizard.gif)

Step Wizard, with arrows, made with terse HTML and CSS only. <a href="https://davidwerbrouck.github.io/wizard/">Check it out</a>.


# Adding a step

To add a new step, write this markup.

```html
<a href=''>
  <span>
    Step number<br>
    Step content
  </span>
<a>
```

# States

To show the current step, add the "current" class on the link.
```html
<a href='' class=current>
```
To mark the step who is done, add the "done" class on the link.

```html
<a href='' class=done>
```

# Size and Colors

To change the size of the wizard globaly, edit $main-size in style.scss.

```scss
$main-size: new-size;
```

To change the colors theme, edit $main-color in style.scss.

```scss
$main-color: new-color;
```


👋🏼<a href="https://twitter.com/david_werbrouck">Say Hi!</a>
