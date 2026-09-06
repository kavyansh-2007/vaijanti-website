# Vaijanti Green Energy — Website

This repository contains the source for the Vaijanti Green Energy corporate website: a static, multi-page HTML site with no build step required.

## Viewing the site locally

Open [`index.html`](index.html) directly in a browser, or serve the folder with any static file server, e.g.:

```bash
npx serve .
```

`index.html` is a splash/intro screen that redirects to [`home.html`](home.html) after a few seconds.

## Pages

| File | Description |
| --- | --- |
| [`index.html`](index.html) | Intro splash screen, redirects to the home page |
| [`home.html`](home.html) | Main landing page |
| [`about.html`](about.html) | About Us |
| [`contact.html`](contact.html) | Contact Us |
| [`projects.html`](projects.html) | Projects portfolio |
| [`investors.html`](investors.html) | Investor relations |
| [`electricity-sales.html`](electricity-sales.html) | Electricity sales & PPA |
| [`jobs.html`](jobs.html) | Job opportunities |
| [`life.html`](life.html) | Life at Vaijanti |
| [`values.html`](values.html) | Our values |
| [`diversity.html`](diversity.html) | Diversity & inclusion |

## Structure

Each page is a self-contained HTML file with inline `<style>` blocks — there is no shared CSS/JS build pipeline. Images referenced by the pages live alongside the HTML in the repository root.
