# Capstone: Flashcard-o-matic

A local school has decided to put together a flash card application, Flashcard-o-matic, to help their students study online. Teachers will use this application to create decks of flash cards for the subjects that they teach, and students will study the decks. The school needs you to build the application that the students and teachers will use.

![flascardApp](https://images.ctfassets.net/c7lxnbtvvcxm/6EQ6qCokZfPfkoU0MkT7EF/e310f418a00c85ca0065fed2a67850f9/Flashcard-o-matic.png)

Bootstrap 4 is included with the starter HTML. You're welcome to use vanilla CSS or Bootstrap 4 for styling your project. However, your finished product doesn't have to match the styles in the provided screenshots because you won't be assessed on the styling or responsiveness of your project.

## Requirements to pass

For your project to pass, all of the following statements must be true. These criteria are reflected in the rubric in the following lesson.
- All tests are passing.
- All the props are treated as read-only.
- State is never directly mutated; it's only updated via setState().
- The Edit Card and Create Card screens share the same form component.
- The useEffect() hooks have the appropriate dependencies listed in the dependency array.
- State is "lifted up" to the parent component where appropriate.
- All inputs are controlled. Generally, there is a warning on the console when you type into the input box and it changes from uncontrolled to controlled. The warning looks like this: "Warning: Input is changing an uncontrolled input of type <text|number|etc.> to be controlled." This is often the result of initializing the state to null or undefined.
