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

