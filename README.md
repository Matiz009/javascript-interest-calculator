# JavaScript Interest Calculator

A web page that calculates simple interest from principal, rate and time.

## Screenshot

_Screenshot coming soon._

## Features

- Inputs for principal amount, number of years and interest rate (%)
- Calculates simple interest as `principal x years x rate / 100`
- The Calculate button changes colour on hover

> **Known issue (TODO):** `calculateInterest()` calls `location.reload()` straight after showing the result, so the result disappears immediately.

## Tech stack

- HTML with Bootstrap classes, served from `index.php` (the page has no PHP logic)
- Vanilla JavaScript (`app.js`)

## Getting started

Because the page is a `.php` file, serve it with PHP:

```bash
git clone https://github.com/Matiz009/javascript-interest-calculator.git
cd javascript-interest-calculator
php -S localhost:8000
# open http://localhost:8000
```

## Project structure

```
index.php  Page markup
app.js     Interest calculation
LICENSE
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
