# Contributing to FOSS Acronyms

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to this project, which are hosted in the [D-EDGE Organization](https://github.com/d-edge) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Code of Conduct

This project and everyone participating in it is governed by the [D-EDGE Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [softwarecraft@d-edge.com](mailto:softwarecraft@d-edge.com).

## Working on your first Pull Request?

You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://kcd.im/pull-request)

## Git Commit Messages

This project follows a subset of [Conventional commits specification](https://www.conventionalcommits.org/en/v1.0.0/).
No type, no scope. Only description and so upper case the first letter.

## What to contribute?

### Fill gap

FOSS-Acronyms has a lot of blank space waiting to be filled. Find an empty string in one of the [JSON](https://github.com/d-edge/foss-acronyms/tree/main/data) and fix it!

![image](https://user-images.githubusercontent.com/3449303/191771306-a820a087-7e8e-462a-bd69-358b58a0d377.png)

Pro-tips: Open [acronyms.json](https://github.com/d-edge/foss-acronyms/blob/main/data/acronyms.json) and search for `""` 😄

### Add new acronym

You can contribute by adding new entries to the list of acronyms.

- Find a good missing acronym
  - Grab one in the [issues](https://github.com/d-edge/foss-acronyms/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22). Issues are filled with good missing acronyms.
  - Submit your own. A missing acronym is an acronym not in the list nor in the issues. A good acronym is any acronym used by the FOSS community.
- Fork the project. [You can use this shortcut](https://github.com/d-edge/foss-acronyms/fork).
- Edit the JSON. A good acronym need
  - an `Abbreviation` like "FOSS"
  - a `Definition` like "Free & Open Source Software"
  - a `Usage` like "That is both free software and open-source software where anyone is freely licensed to use, copy, study, and change the software in any way, and the source code is openly shared so that people are encouraged to voluntarily improve the design of the software"
  - an `Example` wich is a collection of html link like `<a href=\"https://en.wikipedia.org/wiki/Free_and_open-source_software#Usage\">FOSS/FLOSS</a>`. Don't forget to escape all the quote (e.g. `\"`).
- Submit a PR

Finally here is an example of a [merged PR](https://github.com/d-edge/foss-acronyms/pull/63/files). Have fun hacking this project 😸

Thank you for contributing!
