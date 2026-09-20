# GitHub Upload Guide

## Recommended Repository Name

`E-Commerce-Sales-Intelligence-Dashboard`

## Before Uploading

Rename the Power BI file to:

`E-Commerce-Sales-Intelligence-Dashboard.pbix`

Keep the repository structure simple:

``` text
E-Commerce-Sales-Intelligence-Dashboard/
├── E-Commerce-Sales-Intelligence-Dashboard.pbix
├── README.md
├── UPLOAD_GUIDE.md
├── docs/
└── screenshots/
```

## Option 1 --- GitHub Website

1.  Sign in to GitHub.
2.  Create a new repository named
    `E-Commerce-Sales-Intelligence-Dashboard`.
3.  Add the project files.
4.  Upload the `.pbix` file.
5.  Upload the `README.md`, `docs/`, and `screenshots/` folders.
6.  Commit the files with a message such as:
    `Add Power BI internship dashboard`
7.  Open the repository and check that the README displays correctly.

## Option 2 --- Git Command Line

From the project folder:

``` bash
git init
git add .
git commit -m "Add Power BI internship dashboard"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the URL of the repository you
created.

## Recommended GitHub Description

`Power BI internship project analyzing e-commerce sales, profitability, products, customers, regions, and returns.`

## Recommended Topics

Add relevant repository topics such as:

-   `power-bi`
-   `data-analytics`
-   `data-visualization`
-   `business-intelligence`
-   `dashboard`
-   `dax`
-   `power-query`
-   `data-analysis`
-   `portfolio-project`

## Important

Do not upload confidential company data, credentials, API keys,
passwords, or private source files.

The `.pbix` contains an embedded Power BI model, so only publish it if
you are permitted to share the underlying internship data.
