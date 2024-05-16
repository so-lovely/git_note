**subscriptable**
“Subscriptable” is just a fancy way of saying "something you can use square brackets on to get parts from it.” For example, my_list[0] and my_dict['key'] accesses the element at 0 and key, respectively.

In Python you can only use square brackets [] to access elements of a list, array, or dictionary. If you try to do the same thing with a function, you get the “function object is not subscriptable” error.

Simply put, you're trying to treat a function like it's a list, but you can't do that because they are different things.

