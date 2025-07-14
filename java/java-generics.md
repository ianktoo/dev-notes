# Java Generics

[Java Generics](https://docs.oracle.com/javase/tutorial/java/generics/why.html)

Generics allow types (classes and interfaces) to be parameters when defining classes, interfaces and methods.

# Benefits

1. Stringer type checks.
2. Elimination fo casts

example if a list
    
    List list  = new ArrayList()
    list.add("hello");
    String s = (string) list.get(0)

Re writing it using generics

    List<String> list = new ArrayList<String>();
    list.add("hello);
    String s = list.get(0)


## Generic types





