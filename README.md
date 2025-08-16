Getting Started
Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

Folder Structure
The workspace contains two folders by default, where:

src: the folder to maintain sources
lib: the folder to maintain dependencies
Meanwhile, the compiled output files will be generated in the bin folder by default.

If you want to customize the folder structure, open .vscode/settings.json and update the related settings there.

Dependency Management
The JAVA PROJECTS view allows you to manage your dependencies. More details can be found in the official VS Code Java Dependency documentation.

Project Description
A simple Java-based Supermarket Billing System that allows users to manage shopping carts interactively via the command line
Users can add products with name, price, and quantity to the shopping cart
Provides options to remove items from the cart by specifying the item number
Displays the current cart contents with item details and calculates the total cost
Supports applying a discount that reduces the total payable amount
Generates and prints a detailed invoice showing all items, the total, and applied discounts
Allows downloading the invoice as a text file named invoice.txt
Clears the cart automatically after invoice generation or downloading to start fresh
Code uses object-oriented principles with separate Product and ShoppingCart classes for modularity
Uses Java standard libraries including Scanner for input and FileWriter for file operations
