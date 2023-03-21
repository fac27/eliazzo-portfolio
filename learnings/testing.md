The project task was to build a to-do list tracker with automated tests covering all the main user stories. The tracker should allow users to create, complete and delete tasks from a list.


1. Check that passing a given input into our tests returns the expected output

The equal() function was passed into each test to test that the output of the test was as expected.
![equal() and test() functions](/Images/TESTING/equal()%2Btest().png)


2. Write tests to mimic the behaviour of a user performing different actions

Creating a new list was only possible if the user had written a new list heading in the input section, otherwise an error message was thrown. Testing this function therefore required us to mimic the user inputting  a new list heading by assigning a value to the input section.
![newList() test](/Images/TESTING/newList()test.png)  

3. Write testable, modular functions

``errorMessage()``, ``removeErrorMessage()`` are examples of modular functions that were later used when creating a new list or adding a new item to a list.

![error functions](/Images/TESTING/error().png)

``randomColor()`` is another example of a modular function that is used when creating new lists.
![randomColor()](/Images/TESTING/randomColor().png)

As these were additional user stories, time constraints prevented us from writing tests. However, you will find the deleteEntry() function and it's corresponding test below.

![deleteEntry()](/Images/TESTING/deleteEntry().png)
![deleteEntry() test](/Images/TESTING/deleteEntry()test.png)

4. Write functions that add, remove or modify DOM nodes

We used ``.cloneNode`` within submitToDo() to access elements in the HTML file and clone these to create new checklist rows when users submitted a new item to a list.
`` const checklistRow = document.querySelector("#checklistrow")``
`` const clone = checklistRow.content.cloneNode(true) `` 

5. Apply event listeners to HTML form elements

Users can create new checkists using the new list form. An event listener was applied to the submitList (+) button.
`` submitList.addEventListener("click", newList) ``

![form UI](/Images/TESTING/FormUI.png)

6. Use scope to control what variables are accessible inside functions and blocks

In some instances, variables were declared globally. For example, when declaring variables for event listeners.
![listFormBtn event listener](/Images/TESTING/listFormBtn.png)
![submit list event listener](/Images/TESTING/SubmitList%20.png)

Generally, we tried to keep variables within their relevant functions and minimise unnecessary scope. The two exceptions were``newListform`` and ``card`` as these were used within some functions and passed as arguments to some functions.
![global variables](/Images/TESTING/Global.png)

<!-- 7. Use CSS grid to create complex layouts

8. Use CSS grid to make layouts that adapt to the viewport size -->