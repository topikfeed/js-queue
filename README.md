Just a simple queue implementation in JavaScript.

Link the file using script tag or directly embed it in your html.

To create a new queue :

var queue = new Queue();

To enqueue an element :

queue.enqueue('e');

To peek for the first element of the queue :

var item = queue.peek();

To get the number of elements left in the queue :

var length = queue.getLength();

To check whether the queue is empty : 

var isEmpty = queue.isEmpty();
