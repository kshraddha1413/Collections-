**Collection**

A Collection is a group of individual objects represented as a single unit.
Java provides Collection Framework which defines several classes and interfaces to represent a group of objects as a single unit.

The Collection interface (java.util.Collection) and Map interface (java.util.Map) are the two main “root” interfaces of Java collection classes.

Collection : Root interface with basic methods like add(), remove(), 
             contains(), isEmpty(), addAll(), ... etc.
 
Set : Doesn't allow duplicates. Example implementations of Set 
      interface are HashSet (Hashing based) and TreeSet (balanced
      BST based). Note that TreeSet implements SortedSet.

List : Can contain duplicates and elements are ordered. Example
       implementations are LinkedList (linked list based) and
       ArrayList (dynamic array based)

Queue : Typically order elements in FIFO order except exceptions
        like PriorityQueue.  

Deque : Elements can be inserted and removed at both ends. Allows
        both LIFO and FIFO. 

Map : Contains Key value pairs. Doesn't allow duplicates.  Example
      implementation are HashMap and TreeMap. 
      TreeMap implements SortedMap.        

The difference between Set and Map interface is that in Set we 
have only keys, whereas in Map, we have key, value pairs.

Collection is an interface but Collections is a class.
Collection used to represent a group of individual objects as an entity but collections is present in java.util package to define several utility methods like sort, search. for example: Collections.sort(anyCollection);


**Set in Java**

Set is an interface which extends Collection. It is an unordered collection of objects in which duplicate values cannot be stored.
Basically, Set is implemented by HashSet, LinkedHashSet or TreeSet (sorted representation).
Set has various methods to add, remove clear, size, etc to enhance the usage of this interface

set<String> hs = new HaseSet<String>();
 

**MAP**
 
 The Map interface is not a subtype of the Collection interface. 
 
 A Map cannot contain duplicate keys and each key can map to at most one value.
 Some implementations allow null key and null value like the HashMap and LinkedHashMap, but some do not like the TreeMap.
 
 There are two interfaces for implementing Map in java: 
 1)Map and S
 2)sortedMap, and 
 three classes: HashMap, TreeMap and LinkedHashMap.
 
** Why and When to use Maps? **

Maps are perfect to use for key-value association mapping such as dictionaries. 
The maps are used to perform lookups by keys or when someone wants to retrieve and update elements by keys. Some examples are:
1)A map of zip codes and cities.
2)A map of managers and employees. Each manager (key) is associated with a list of employees (value) he manages.
3)A map of classes and students. Each class (key) is associated with a list of students (value).

