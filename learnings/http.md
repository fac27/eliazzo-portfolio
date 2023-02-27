## 1. Write code that executes asynchronously

We designed an accessible web application that used data from an open [Github API](https://docs.github.com/en/rest?apiVersion=2022-11-28) and an open [dog API](https://dog.ceo/dog-api/). User had the option of searching through the API's and pulling dog breeds and images according to their input. Accessing the dog image and displaying this on the page took considerably longer than accessing the breed names. Using asynchronous programming we were able to start this potentially long-running task while responding to other events.

## 2. Use callbacks to access values that aren’t available synchronously

We used the .then() method in conjunction with Promises. When the Promise resolved successfuly, it called the .then() method, passing in a callback function as its argument.

## 3. Use promises to access values that aren’t available synchronously

We used the built-in browser API "Fetch" which returned a promise that resolves with a "Response" object that represents the response to the HTTP request.

* Note * "Fetch" it is not a type of promise itself. Rather, it is a function that returns a promise.

## 4. Use the fetch method to make HTTP requests and receive responses
![Using fetch to access the dog API](/Images/getDog()%20fetch.png)

## 5. Configure the options argument of the fetch method to make GET and POST requests

## 6. Use the map array method to create a new array containing new values
![Using map](/Images/map().png)

## 7. Use the filter array method to create a new array with certain values removed
![Using filter](/Images/filter.png)

## 8. Access DOM nodes using a variety of selectors

Writing this, it has come to my attention that we only used getElementById. However, I feel confident using other selectors such as getElementsByClassName, getElementsByTagName, querySelector, querySelectorAll, parentNode and getAttribute (among others).

## 9. Add and remove DOM nodes to change the content on the page

![Add dom](/Images/add%20dom%20nodes.png)

## 10. Toggle the classes applied to DOM nodes to change their CSS properties

## 11. Use consistent layout and spacing

## 12. Follow a spacing guideline to give our app a consistent feel

## 13. Debug client side JS in our web browser

## 14. Use console.log() to help us debug our code
