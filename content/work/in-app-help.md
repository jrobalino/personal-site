---
title: "In-app Help"
date: 2019-10-31T18:46:33-05:00
draft: false
---

[Code is not available for this project because the repository belongs to a company I've worked for](/work/in-app-help/)

### Help at your fingertips right when you need it

{{< rawhtml >}}
<iframe style="margin:20px 0px 20px 0px;" width="100%" height="315" src="https://www.youtube.com/embed/xzwPAi4ZU-0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{{< /rawhtml >}}

The in-app help system is a React.js application that displays help to end users when they click the Help button. This system has the following features:

* Displays help within a drawer embedded in the application.
* Displays help contextual to each page.
* Enables technical writers to update the help content without code changes.

The in-app help system sources content from Markdown files stored in AWS S3, and runs AWS Lambda functions to determine the correct file to display based on mappings in a JSON manifest.

