# HLA.alleles.org Redesign

Open the link here to view the codespace: [https://codesandbox.io/](https://codesandbox.io/p/github/MCooper1210/hla_alleles_org_refresh/main?file=%2Fpackage-lock.json)

This repository contains the ongoing website redesign for [HLA.alleles.org](http://hla.alleles.org), a comprehensive resource for information on HLA and related genes. Eleventy is being used to build all of the pages, and we are currently working on adding content to these pages.

## Project Overview

This project focuses on redesigning the HLA.alleles.org website, a global repository for information on the HLA gene, frequently used by laboratories and researchers. The primary goal is to modernise the website to meet current web standards for accessibility, mobile performance, and search engine optimisation (SEO).

## Technology Stack

- **Eleventy (11ty)**: A static site generator used to build pre-rendered pages, improving performance and reducing data usage for mobile users.
- **Nunjucks**: Used for templating, enabling efficient and reusable components across pages.
- **Bootstrap**: Chosen for easy implementation of responsive, accessible UI components and mobile-first design.
- **JavaScript**: Employed for future dynamic functionality, especially for interactive features like the gene page.
- **JSON**: Structured data used to build pages dynamically.

## Features

- **Modern Accessibility and SEO**: Optimised to meet accessibility standards and improve SEO.
- **Component-Based Architecture**: Reusable components are created to simplify development and ensure consistency. Any update to a component affects all pages, which will help when finalising the site.
- **Responsive Design**: A mobile-first approach with Bootstrap ensures optimal user experience across devices.
- **Data-Driven Pages**: JSON files are used to dynamically generate content, reducing redundancy and improving site maintainability.
- **Breadcrumb Navigation**: Enhances site navigation, allowing users to track their location within the site.
- **Interactive Gene Page**: A JavaScript-powered page providing users with an interactive experience for exploring gene-related information.

## Future Goals

- Implement a scalable component system for ease of maintenance and future updates.
- Ensure the site is highly performant, especially for mobile users with limited data.
- Improve the visual appearance and usability, making the site more modern and user-friendly for researchers globally.

## Getting Started

To set up the project locally, follow these steps to install and preview the required Eleventy package:

```bash
npm install @11ty/eleventy
```
```bash
npx @11ty/eleventy
```
```bash
npx @11ty/eleventy --serve
```
