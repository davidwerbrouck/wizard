# Step Wizard

Step Wizard, with arrows, made with terse HTML and CSS only. <a href="https://davidwerbrouck.github.io/wizard/">Check it out</a>.


# Adding a step

```
<a href=''>
  <span>
    Step number<br>
    Step content
  </span>
<a>
```

# States

To show the current step, add the "current" class on the link.
```
<a href='' class=current>
```
To mark the step who is done, add the "done" class on the link.

```
<a href='' class=done>
```

# Size and Colors

To change the size of the wizard globaly, edit $main-size in style.scss.

```
$main-size: 34px;
```

To change the colors theme, edit $main-color in style.scss.

```
$main-color:    #1d1d1f;
```


👋🏼<a href="https://twitter.com/david_werbrouck">Say Hi!</a>
