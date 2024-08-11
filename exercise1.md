Sometimes I feel like the love/bond between me and JavaScript is made from heaven, however, I am required by fullstackopen to write about CI/CD concepts in a language other than JavaScript.

Naturally, I would easily go for Python since it is also a scripting language like JavaScript and the most popular programming language (after JavaScript, ofcourse :) ).

The first subject of discussion is linting. Linting is performed while the source code is written and before it’s compiled. In other words, linting is a pre-build check, also called “static code analysis.” Regularly checking our code with linting ensures consistency across the code and the codebase. This minimizes the chances of small errors becoming complex issues after the code is run.

Just like most newbies in software development, I find this linting of a thing a little too overburdening and see it as less important. But, now that I am more into DevOps principles, I can see its relevance in code quality and especially consistency in how a code/app works thereby boosting the development productivity. In JavaScript, a common tool used is Eslint, while in Python I can see PyLint being used by most Python Developers.

Another concept usually neglected is testing. Thorough testing is essential to ensure software systems function correctly, are secure, meet stakeholders' needs, and ultimately provide value to end users. A common tool used in JavaScript is Jest and that of Python is PyTest. Then the last concept in CI is build. Webpack is by far the most popular tool used to accomplish such in JavaScript while PyBuilder appears to lead the space in the Python community.

Virtually all software developers use git as their preferred version control system. And a huge chunk of these Github as their remote repository. Thus, it is no surprise that a good number of developers use Github Actions as a CI/CD tool since it is easily integrated with the existing Github repositories. However, some limitations of GitHub Actions include potential complexity in setting up workflows, limited free minutes for CI/CD, and dependency on GitHub as a platform.

This gives room for a number of alternatives such as CircleCI which provides fast build times, scalable infrastructure, and intuitive configuration. Although, pricing and less intuitive UI compared to Github Actions may discourage some from using it.

Choosing between a self-hosted or a cloud-based CI/CD environment
One major factor to consider in choosing is the server maintenance and ease of configuration/setup. Generally speaking, this is where cloud-based CI/CD environment (SaaS CI/CD service) have the advantage as you have nothing to worry about dealing with serves and fairly simple setup required. However, scalability and extensibility may be things to consider if going for self-hosted CI/CD environment. This is because one has full control and better chances of customizing features as needed.

Like everything, there are pros and cons to all solutions, and with the vast amount of CI/CD options available today, there’s no such thing as “one size fits all”.