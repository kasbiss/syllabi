Propose a relational database design (a set of relation schemata) for the online food ordering and delivery application illustrated in this UML class diagram:

UML diagram: https://github.com/LIS561/syllabi/blob/master/labs/UML6.pdf

The proposed design must satisfy the constraints of third normal form, as described in the Kent reading, but you don't need to include attributes for handling every use scenario. Concentrate on what you consider the 3-5 most important attributes of each class, and focus on the following modeling problems:

A menu item's inclusion in any particular order must be associated with a quantity (e.g., how many garlic bread). But the item's inclusion on the restaurant's menu has no particular quantity.
Users will search for items (like ravioli) and for categories (like pasta or Italian cuisine). So those items and categories must each be associated with one or more restaurants. But not every restaurant will include the same items in the same categories: the organization of the menu is up to the individual restaurant.
Write a paragraph of comments on the exercise. Include a description of what joins on your relations would produce tuples that answer a question like: "List restaurants featuring pasta items and the specific items in that category they offer."

Upload your design proposal and comments here.

