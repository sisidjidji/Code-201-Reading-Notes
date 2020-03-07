# CLASS13

# LocalStorage in JavaScript: 

To use localStorage in your web applications, there are five methods to choose from:

1. setItem(): Add key and value to localStorage

2. getItem(): Retrieve a value by the key from localStorage

3. removeItem(): Remove an item by key from localStorage

4. clear(): Clear all localStorage

5. key(): Passed a number to retrieve nth key of a localStorage



## 1.setItem()

This method just as the name implies allows you to store values in the localStorage object.

It takes two parameters, a key and a value. The key can be referenced later to fetch the value attached to it.

#### window.localStorage.setItem('name', 'Obaseki Nosa');

Where name is the key and Obaseki Nosa is the value. Also note that localStorage can only store strings.

To store arrays or objects you would have to convert them to strings.

To do this we use the JSON.stringify() method before passing to setItem().


## 2.getItem()

The getItem() method allows you to access the data stored in the browser’s localStorage object.

It accepts only one parameter which is the key and returns the value as a string.

To retrieve the user key stored above:

#### window.localStorage.getItem('user');


## 3. removeItem()

The removeItem() method when passed a key name, will remove that key from the storage if it exists. If there is no item associated with the given key, this method will do nothing.

#### window.localStorage.removeItem('name');


## clear()

This method, when invoked clears the entire storage of all records for that domain. It does not receive any parameters.

#### window.localStorage.clear();


## key()

The key() method comes in handy in situations where you need to loop through keys and allows you pass a number or index to local 

storage to retrieve the name of the key.

#### var KeyName = window.localStorage.key(index);