---
# Course title, summary, and position.
linktitle: EC 204 - Empirical Economics 2
summary: 
weight: 1

# Page metadata.
title: Overview
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  example:
    name: Overview
    weight: 1
---

## Flexibility

Does taking an econometrics class in college improve job prospects? To what extent do friends determine your outcomes in life? Are married people happier? Are kids going to lag behind if both parents work? What factors determine the timing of retirement? We can use econometrics to answer questions like these, and others in a wide variety of fields. Econometrics is the use of statistical tools to answer questions using economic or other data. The main objective of economists to use econometrics is to deduce causality.
This is the second course in the introductory level sequence in empirical economic analysis. More specifically, this course will introduce you to the tools needed to do empirical work, namely, a data set, econometric skills, and computer software. By the end of this class, you should be able to pose a question, develop a hypothesis, and analyze your hypothesis using available data, and econometric skills developed in class. Topics covered in this class include simple and multiple linear regression models, hypothesis testing, goodness of fit, heteroskedasticity, autocorrelation, and panel data. I would love for you to learn econometrics for the sake of learning, however, as an additional motivation, I should add that the skills that you learn in this class are greatly valued in the job market.

## Delete tutorials

**To remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## Update site menu

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```
## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`.
