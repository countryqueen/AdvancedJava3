# AdvancedJava3
Demonstrate the use of Classes and Objects - Inheritance and Polymorphism.  Write a program for a used book store to track their inventory.  The book dealer buys and sells three kinds of items, books, DVD movies, and paintings.  Each item in inventory should have an instance of an object instantiated for it.  Each object should have at least one constructor and should use get and set methods to set and read the object properties.  The super class StoreItem should contain all the objects and methods that all StoreItems share such as the properties title, author, date acquired, purchasePrice (what the dealer paid to get this item in the store), asking price (the price the dealer wants for this item), etc., and the methods get, set, printableString.  A method to calculate the profit on a sale is also necessary.   The Book class should have the properties that are unique to Books (genre, title author, etc). The Movie class should have the properties that are unique to movies(title, director, actors[], actresses[], etc.).  The Painting class should have the properties that are unique to paintings (height, width, media (oil, water color, etc.) ).      Make the object instances keep track of how many of each type of StoreItem are in the store. When selling a item, you will remove the object and decrement the count for that item's class.  When adding an item to inventory, an object needs to be instantiated and the count for that item type increased.  (Hint: Use a static counter.)  Demonstrate the use of inheritance (Hint:  StoreItem is the super class).  Also, demonstrate polymorphism in this project.  Allow the user to add inventory (create new objects), sell inventory (remove objects), and display current inventory (display each object’s properties one at a time).  IMPORTANT: None of these classes, StoreItem, book, Movie, or Painting, should have direct input or output.  This means that the GUI class should handle the IO, not the StoreItem class.  Or, said another way, the Book class should not ask the user for the value of a property, nor shall it print output directly to the screen.  Listed below is the UML diagram for the minimum level project for this assignment.