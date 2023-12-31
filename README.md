# Book Collection - Classes version

This application allows you to add and remove technical tests from your collection.  
The list of technical tests is retrieved from a Google API.

## Exercise

### Analysis

Analyze the application and explain how it works, focusing on the @ngrx stack.  
Answer the following questions:

- What is the purpose of the `collectionReducer`?
- What does the `selectBookCollection` selector do?
- What is the purpose of the payload in the `RetrievedBookList` action?

### Implementation

To implement the exercise, follow these steps:

1. Create an effect in the `TechnicalTestsEffects` class that displays an "alert" message whenever a technical test is added or removed from the collection.
2. The message should contain the text: "The technical test 'Title' has been added to the collection" or "The technical test 'Title' has been removed from the collection".
3. Generate additional Actions, Selectors, and Reducers as needed.


