# Corgi Simon

A landing page dedicated to a friend's corgi dog, built at the end of 2021 with plain HTML/CSS/JS and a couple of JS libraries. All web design was made by the author as well.

## Features

- Hamburger menu for mobile
- Image gallery slider ([Slick Carousel](https://kenwheeler.github.io/slick/))
- Form validation before sending ([jQuery Validation Plugin](https://jqueryvalidation.org/))
- Contact form submission handled via PHPMailer (`mailer/smart.php`)
- Smooth scroll-to-top arrow, closable modal window

## Tech Stack

- HTML, CSS, vanilla JavaScript
- jQuery, Slick Carousel, jQuery Validation Plugin
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) for contact form email delivery

## Getting Started

```bash
git clone https://github.com/korzinmark/corgi_project.git
cd corgi_project
```

Open `index.html` in a browser. Sending the contact form requires a PHP server (e.g. `php -S localhost:8000`), since it posts to `mailer/smart.php`.
