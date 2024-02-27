# Tags & Versions 👌
In this README section, we'll explore the core principles of Semantic Versioning, discuss its importance in software development, and provide practical examples of versioning strategies.
. It provides a structured approach to version numbers, consisting of three digits: **major**, **minor**, and **patch**.
##   Semantic Versioning (SemVer)

The versioning standard is a numeric sequence separated into three positions:
![enter image description here](https://www.alura.com.br/artigos/assets/versionamento-semantico-breve-introducao/imagem4.jpg)

### MAJOR 
The first digit informs about the compatibility version and is changed if the software undergoes changes that make it incompatible with other versions. These are called _breaking changes_, updates that have the potential to "break" code using previous versions.

Example: You are using a function from library X, but a new version of the library has been released where that function has a different name or signature. If we try to execute the code using the new version of the library, the function will not run correctly.

Version 1.0.0 → Now it is 2.0.0

### MINOR


The second digit informs about the feature version, where a new function or substantial improvement is added and there are no compatibility issues with other versions.

Example: The library you usually use now has a new feature and is compatible with other versions, only requiring a local update.

Version 2.0.0 → Now it is 2.1.0

### PATCH (Correction)

The third digit indicates the version for bug fixes, performance improvements, or similar changes that do not alter the current functionalities or introduce new ones.

Example: The library you usually use has a bug that creates a vulnerability in the code. This bug has been fixed in a new version.

Version 2.1.0 → Now it is 2.1.1

## Software Publishing Rules

Semantic versioning brings some specifications aiming to maintain clear communication between software, so that when you look at the format of a version, you have the same understanding as anyone else around the world. Some rules are:

-   A version number has the format X.Y.Z, where X, Y, and Z are non-negative integers and should not contain leading zeros. X is the major version, Y is the minor version, and Z is the patch version.
    
-   Each version number must increase numerically; that is, we cannot have a version 1.0.0 and a version 3.0.0 without a version 2.0.0 existing.
    
-   When a package is released, the content of that version should not be modified! If there are modifications, a new version must be released.
    
-   A pre-release version (as we saw before: alpha, beta, rc) can be identified by adding a hyphen after the patch version (the Z in our format) and a series of identifiers separated by dots. The identifier must include only alphanumeric characters and hyphen [0-9A-Za-z-] and must not be empty. Examples: 1.0.0-alpha, 1.0.0-alpha.1, 1.0.0-0.3.7.
    
-   At the beginning of development, the Major version should be zero (0.y.z).
    
-   Version 1.0.0 defines the API as public (the one that has been released and is available to the public). How the version number is incremented after this release depends on the public API and how it changes.
    

If you want to understand other rules about semantic versioning, you can consult the official documentation [by clicking here](https://semver.org/lang/pt-BR/).
