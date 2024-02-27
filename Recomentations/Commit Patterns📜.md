# Commit Patterns 📜
According to the documentation of **[Conventional Commits](https://www.conventionalcommits.org/pt-br)**, semantic commits are a simple convention to be used in commit messages. This convention defines a set of rules for creating an explicit commit history, which makes it easier to create automated tools. These commits will help our team to easily understand what changes were made in the piece of code that was committed.

This identification occurs through a word that identifies whether that commit made is a code change, package update, documentation, visual change, test...

## Types & Descriptions 

The semantic commit has the following structural elements (types), which inform the intention of your commit to the user of your code:

-   `feat`- Commits of type feat indicate that your piece of code is adding a **new feature** (relates to MINOR in semantic versioning).
    
-   `fix` - Commits of type fix indicate that your committed piece of code is **fixing a problem** (bug fix), (relates to PATCH in semantic versioning).
    
-   `docs` - Commits of type docs indicate that there have been **changes in the documentation**, such as in your repository's Readme. (Does not include code changes).
    
-   `test` - Commits of type test are used when **changes in tests** are made, whether creating, altering, or deleting unit tests. (Does not include code changes).
   -   `build` - Commits of type build are used when modifications are made to **build files and dependencies**.
    
-   `perf` - Commits of type perf are used to identify any code changes related to **performance**.
    
-   `style` - Commits of type style indicate that there have been changes related to **code formatting**, semicolons, trailing spaces, lint... (Does not include code changes).
    
-   `refactor` - Commits of type refactor refer to changes due to **refactorings that do not alter its functionality**, such as a change in the format of how a certain part of the screen is processed, but that maintained the same functionality, or performance improvements due to a code review.
    
-   `chore` - Commits of type chore indicate **updates to tasks** such as build, administrator configurations, packages... such as adding a package to gitignore. (Does not include code changes).
    
-   `ci` - Commits of type ci indicate changes related to **continuous integration**.
    
-   `raw` - Commits of type raw indicate changes related to configuration files, data, features, parameters.
    


## Recommendations 🎉

[Link to recommendations](https://github.com/iuricode/padroes-de-commits/blob/main/README.md#recomenda%C3%A7%C3%B5es-)

-   Add a type consistent with the content title.
-   We recommend that the first line should have a maximum of 4 words.
-   For detailed descriptions, use the commit description.
-   Use an emoji at the beginning of the commit message representing the commit.
-   Links should be added in their most authentic form, i.e., without link shorteners and affiliate links.
