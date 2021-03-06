# Redux-Store

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

An e-commerce platform that can allow the user to create an account and add items into their cart for checkout. The user can likewise remove items later on from their shopping cart. The user can checkout the items in their shopping cart with Stripe and see their previous orders in the order history tab. My motivation for this project was to create an online shopping platform that allows the user to buy stuff. This project helped me improve my skills in Redux and Stripe as well as setting up a Heroku page and using MongoDB Atlas as the database.

## Link to the Project

-   [GitHub Repository][github-repo]
-   [Deployed Link][deployed-link]

## Table of Contents

-   [Installation](#installation)
-   [Project Demo](#project-demo)
-   [Usage](#usage)
-   [License](#license)
-   [Contributing](#contributing)
-   [Tests](#tests)
-   [Questions](#questions)

## Installation

-   To clone the repository
    -   Make sure you have right access to pull in the repository either by applying 'ssh' keys or by providing a username and password'
    -   Make sure your path is proper
    -   Copy the git command to where you want to clone the repository
    ```
    git clone git@github.com:ByteSizeError/Redux-Store.git
    ```
    -   You will see a `Redux-Store` folder.
-   An alternate document to clone a repo can also be found at [github][github-link]

## Project Demo

### Searching for items by category


https://user-images.githubusercontent.com/37029188/150436587-6e891af6-60e3-4e8e-9f94-001dba3bd6ba.mov


### Sign up page

https://user-images.githubusercontent.com/37029188/150436600-5df7e18c-1e79-41e8-872f-6ffecaad9a54.mov


### Adding items to shopping cart


https://user-images.githubusercontent.com/37029188/150436631-6ad76915-943b-4420-ae91-1c59883a22a4.mov


### Deleting items from shopping cart


https://user-images.githubusercontent.com/37029188/150436652-778a0139-5ceb-45e6-97fe-51a291c489b6.mov


### Logging back in


https://user-images.githubusercontent.com/37029188/150436663-f0aca4fd-4274-4b9b-9c46-6c3e0d722a17.mov


### Checking out with Stripe


https://user-images.githubusercontent.com/37029188/150436680-2d5c88bf-8ae5-4a6c-86a4-6608a81a6e79.mov


### Viewing order history


https://user-images.githubusercontent.com/37029188/150436695-35cd046b-41a0-4fdc-87a7-89f08b82b6d1.mov


## Usage

-   Users can add items into their shopping cart
-   Users can remove items from their shopping cart
-   Users can sign in from any other device with the same credentials
-   Users can checkout their shopping cart with Stripe
-   Users can see their order history when signed in

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

https://www.mit.edu/~amini/LICENSE.md

```MIT License

      Copyright (c) 2021 Jimmy Zheng

      Permission is hereby granted, free of charge, to any person obtaining a copy
      of this software and associated documentation files (the "Software"), to deal
      in the Software without restriction, including without limitation the rights
      to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
      copies of the Software, and to permit persons to whom the Software is
      furnished to do so, subject to the following conditions:

      The above copyright notice and this permission notice shall be included in all
      copies or substantial portions of the Software.

      THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
      IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
      FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
      AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
      LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
      OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
      SOFTWARE.
```

## Contributing

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

We as members, contributors, and leaders pledge to make participation in our
community a harassment-free experience for everyone, regardless of age, body
size, visible or invisible disability, ethnicity, sex characteristics, gender
identity and expression, level of experience, education, socio-economic status,
nationality, personal appearance, race, caste, color, religion, or sexual identity
and orientation.

We pledge to act and interact in ways that contribute to an open, welcoming,
diverse, inclusive, and healthy community.

Examples of behavior that contributes to a positive environment for our
community include:

-   Demonstrating empathy and kindness toward other people.
-   Being respectful of differing opinions, viewpoints, and experiences.
-   Giving and gracefully accepting constructive feedback.
-   Accepting responsibility and apologizing to those affected by our mistakes, and learning from the experience.
-   Focusing on what is best not just for us as individuals, but for the overall community.

Examples of unacceptable behavior include:

-   The use of sexualized language or imagery, and sexual attention or advances of any kind
-   Trolling, insulting or derogatory comments, and personal or political attacks
-   Public or private harassment
-   Publishing others' private information, such as a physical or email address, without their explicit permission
-   Other conduct which could reasonably be considered inappropriate in a professional setting

This Code of Conduct is adapted from the [Contributor Covenant][homepage],
version 2.1, available at
[https://www.contributor-covenant.org/version/2/1/code_of_conduct.html][v2.1].

Community Impact Guidelines were inspired by
[Mozilla's code of conduct enforcement ladder][mozilla coc].

For answers to common questions about this code of conduct, see the FAQ at
[https://www.contributor-covenant.org/faq][faq]. Translations are available
at [https://www.contributor-covenant.org/translations][translations].

## Tests

Testing can be performed in the command line after installation of the project on the machine. To test the project go into the command line and type in

```
npm install
```

to install all the required modules.
To run and test the program refer to the project demo as a walkthrough to get started.

To seed the local database we will type in

```
npm run seed
```

Next type in

```
npm run develop
```

If concurrently is missing type in

```
npm install -g concurrently
```

and follow the instructions for how to fix package issues.

After all required modules are installed should be able to run the program. It will prompt you for project information. Here is where you can test the project.

## Questions

For questions you can reach me at https://github.com/ByteSizeError.

You can also reach me at jimmyz0622@gmail.com for additional questions.

[deployed-link]: https://warm-lake-53643.herokuapp.com/
[faq]: https://www.contributor-covenant.org/faq
[github-link]: https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository
[github-repo]: https://github.com/ByteSizeError/Redux-Store
[homepage]: https://www.contributor-covenant.org
[mozilla coc]: https://github.com/mozilla/diversity
[translations]: https://www.contributor-covenant.org/translations
[v2.1]: https://www.contributor-covenant.org/version/2/1/code_of_conduct.html
