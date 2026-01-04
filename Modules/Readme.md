A. Creating Custom Packages and Modules

1. You can create your own custom packages. Start by creating a folder for your package. Inside this folder, create an __init__.py file. This special file tells Python to treat the folder as a package and initializes the namespace.


B. Sub-packages and Nested Imports

1. You can create sub-packages by adding folders inside your package folder. Each sub-package should also contain an __init__.py file. For example, create a sub_package folder inside your main package and add a module such as mult.py for multiplication operations.

2. Ensure that each folder you want to treat as a package contains an __init__.py file. This allows you to structure your code with packages and sub-packages, making it modular and reusable.


C. Key Takeaways

1. Python modules and packages help organize and reuse code efficiently.
2. Importing built-in and external packages can be done using import and from ... import ... statements.
3. Custom packages require an __init__.py file to be recognized as a package.
4. Sub-packages and modules can be structured and imported using dot notation.