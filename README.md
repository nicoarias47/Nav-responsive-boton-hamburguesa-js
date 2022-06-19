# Navbar Resposive + Btn Hamburger

## JS

```
const navToggle = document.querySelector(".nav-toggle");
const links = document.querySelector(".links");

navToggle.addEventListener("click", function () {
   links.classList.toggle("show-links");
});
```

## HTML

```
<div class="nav-center">
          <!-- Nav Header -->
          <div class="nav-header">
            <div class="logo">
              <!-- LOGO -->
              <img
                src=""
              />
            </div>
            <!-- BTN: IMPORTANTE -->
            <button class="nav-toggle">
              <i class="fas fa-bars"></i>
            </button>
          </div>
          <!-- LINKS A MOSTRAR: IMPORTANTE -->
          <ul class="links">
            <li class="list-items"><a href="#" class="link-item">Home</a></li>
            <li class="list-items"><a href="#" class="link-item">FAQ</a></li>
            <li class="list-items">
              <a href="#" class="link-item">Contact</a>
            </li>
            <li class="list-items"><a href="#" class="link-item">Login</a></li>
          </ul>
        </div>
```
