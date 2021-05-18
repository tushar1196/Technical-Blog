# DOM
##### The full form of Dom is as follows-
* #### **D** stands for Document

* #### **O** stands for Object

* #### **M** stands for Model

###### The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page. A Web page is a document. This document can be either displayed in the browser window or as the HTML source. But it is the same document in both cases. The Document Object Model (DOM) represents that same document so it can be manipulated. The DOM is an object-oriented representation of the web page, which can be modified with a scripting language such as JavaScript.
###### According to W3C - "The W3C Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document."

#### HTML DOM:- 
###### HTML DOM is an Object Model for HTML.
###### It gives:-
*  ###### HTML elements as objects
*  ###### Properties for all HTML elements
*  ###### Methods for all HTML elements
*  ###### Events for all HTML elements

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5a/DOM-model.svg"
     alt="DOM"
     style="float: left; margin-center: 10px;" />


#### **How DOM helps?**

###### When html document is loaded in the browser, it becomes a document object. It is the root element that represents the html document. It has properties and methods. By the help of document object, we can add dynamic content to our web page

#### **Methods for accessing the document object:-**

##### **1. write("String") :-**

###### writes the given string on the doucment.

##### **2.writeln("string") :-**

###### writes the given string on the doucment with newline character at the end.

##### **3.getElementById() :-**

###### returns the element having the given id value.

##### **4.getElementsByName():-**

###### returns all the elements having the given name value.

##### **5.getElementsByTagName():-**

###### returns all the elements having the given tag name.

##### **6.getElementsByClassName():-**

###### returns all the elements having the given class name.

#### **JavaScript helper method:-**

<img src="https://miro.medium.com/max/1416/1*_tc2tXfUOPcI2jGqCDzhPw.png"
     alt="Js helper method"
     style="float: left; margin-center: 10px;" />



##### **1. every() Method:**
###### This method is used to check if all elements of an array pass the test that is implemented by the passed higher-order function. It iterates over the array and check for all values, if he is a same or not.If any value is not same then it will return false

##### **2. fill() Method:**
###### This method fills the array with a static value. It overrides all array values starting from the first element(0th index) and up to the last element(array.length-1 index)

##### **3. filter() Method:**

###### This method filters the array that passes the test with the function passed to it. It returns a new array

##### **4. find() Method:**

###### This method returns the first element that passes the test with the provided function

##### **5. findIndex() Method:**

###### This method returns the first element index that passes the test with the provided function. It can be used in the case of primitive and in the case of objects

##### **6. flat() Method:**

###### This method is used to flatten the array or concatenate the array with the sub-array elements recursively. //[1, [2, 3, 4], 5] >> [ 1, 2, 3, 4, 5 ]

##### **7. forEach() Method:**

###### This is one of the most used method. It is basicallly iterative method. It is used to call or execute the provided/passed function once for each element in an array. It modifies the original array

##### **8. includes() Method:**

###### This method is used to test whether an element is present in an array or not. It checks for a value in primitive and reference in case of an object

##### **9. indexOf() Method:**

###### This method returns the first element index that passes the test with the provided function. It takes a value as input. It should be used in case of primitive. As in the case of objects, it will check its reference. Check is case-sensitive

##### **10. join() Method:**

###### This method concatenates the array values into a string separated by comma(if no separator is provided) or with separator provided

##### **11. lastIndexOf() Method:**

###### It searches for an element in an array and returns the last index of the elements provided in an array. It takes a value as input. It should be used in case of primitive. As in the case of objects, it will check its reference

##### **12. pop() Method:**

###### It removes the last element from an array and returns the removed element

##### **13. push() Method:**

###### It adds or pushes an element as the last element in an array

##### **14. reverse() Method:**

###### This method reverses the array elements

##### **15. shift() Method:**

###### It removes the first element from an array and returns the removed element

##### **16. some() Method:**

###### This method checks if any one of the elements in the array passes the test provided by the predicate function. If in any array index the test pass some method returns true else false. It just checks the element exists in an array. It returns as soon as the predicate function returns true

##### **17. sort() Method:**

###### This method sorts the array in ascending order(default behavior if compare function is not specified). This method mutates the original array

##### **18. unshift() Method:**

###### It adds or inserts an element at the starting position of an array

##### References
1. [javatpint](https://www.javatpoint.com/document-object-model)
2. [geeksforgeeks](https://www.geeksforgeeks.org/dom-document-object-model/)
