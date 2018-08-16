# bootstrap-button-sidebar
This project require bootstrap 4 and fontawesome.

Example [here](https://xaberr.github.io/bootstrap-button-sidebar/).

![demo](https://user-images.githubusercontent.com/16030020/44221731-9e646480-a182-11e8-851f-de9812b2b961.gif)

## Usage

1. Include `bootstrap-button-sidebar/dist/main.min.css`

2. Make the navbar

```html
<nav class="navbar">
  <ul class="navbar-nav">
    <li class="nav-item active">
      <a class="nav-link" href="#">
        <i class="fab fa-angular fa-2x"></i>
      </a>
    </li>
    <li class="nav-item popright">
      <a class="nav-link" href="#">
        <i class="fab fa-angular fa-2x"></i>
      </a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#">
        <i class="fab fa-angular fa-2x"></i>
      </a>
    </li>
  </ul>
</nav>
```

## Other

- Add `popright-nav` class to `nav` to achieve the popup bar effect.
- Add `popright` class to `li` to achieve the popup button effect.
- Add `active` class to `li` to achieve the active button effect.
