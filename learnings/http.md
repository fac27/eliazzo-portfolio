## 1. Write code that executes asynchronously

We designed an accessible web application that used data from an open [Github API](https://docs.github.com/en/rest?apiVersion=2022-11-28) and an open [dog API](https://dog.ceo/dog-api/). 
![Mobile view homepage](/Images/HTTP/mobile%20first.png)
Users could view relevant dog breeds and images according to their input. Accessing the dog image and displaying this on the page took considerably longer than accessing the breed names. Using asynchronous programming we were able to start this longer-running task while responding to other events.

## 2. Use callbacks to access values that aren’t available synchronously

We used the ```.then()``` method with Promises. When a Promise resolved successfuly, it called the ```.then()``` method, passing in a callback function as its argument.
![.then() example](/Images/HTTP/then.png)

## 3. Use promises to access values that aren’t available synchronously

We used the built-in browser API ```Fetch``` which returned a promise that resolves with a "Response" object that represents the response to the HTTP request.

> "Fetch" it is not a type of promise itself. Rather, it is a function that returns a promise.

## 4. Use the fetch method to make HTTP requests and receive responses

In the example below ```Fetch``` is used to access the dog image from the dog API](https://dog.ceo/dog-api/).
![Using fetch to access the dog API](/Images/HTTP/getDog()%20fetch.png)

## 5. Configure the options argument of the fetch method to make GET and POST requests
![GET example](/Images/HTTP/GET.png)

## 6. Use the map array method to create a new array containing new values
![Using map](/Images/HTTP/map().png)

## 7. Use the filter array method to create a new array with certain values removed
![Using filter](/Images/HTTP/filter.png)

## 8. Access DOM nodes using a variety of selectors

Writing this, it has come to my attention that we only used ```.getElementById()``` 🙀. However, I feel confident using other selectors such as ```.getElementsByClassName()```, and ```.querySelector()```/ ```.querySelectorAll()``` (among others).

## 9. Add and remove DOM nodes to change the content on the page
![Add DOM nodes](/Images/HTTP/add%20dom%20nodes.png)

## 10. Toggle the classes applied to DOM nodes to change their CSS properties

This is not something we used, however one might toggle the class on an element using the classList property. 

To add the "active" class to the element:
> myElement.classList.add('active');

To remove the "active" class:
> myElement.classList.remove('active');

To toggle the "active" class::
> myElement.classList.toggle('active');

You can also check if a class is currently applied to the element using the contains() method. For example, to check if the "active" class is currently applied to the element:
> if (myElement.classList.contains('active')) {
  // Do something if the class is present
}

## 11. Use consistent layout and spacing / 12. Follow a spacing guideline to give our app a consistent feel

We used CSS primitives to apply consistent layout and spacing CSS.
![CSS primitives](/Images/HTTP/CSS%20primitives.png)


## 13. Debug client side JS in our web browser

We used the built-in Chrome developer tools.
![Debugging](/Images/HTTP/Inspect%20Network%20DevTools%20scrnshot.png)

## 14. Use console.log() to help us debug our code

Most of our ```console.log()``` statements have been removed as we have completed our projects. However, image #5 demonstrates one instance in which we used ```console.log()``` to confirm our generated GitHub username did not already exist.
