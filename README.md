# Java-Genrics
These are some properties of generic methods:

Generic methods have a type parameter (the diamond operator enclosing the type) before the return type of the method declaration.
Type parameters can be bounded (we explain bounds later in this article).
Generic methods can have different type parameters separated by commas in the method signature.
Method body for a generic method is just like a normal method.
To declare an upper-bounded type, we use the keyword extends after the type, followed by the upper bound that we want to use:

public <T extends Number> List<T> fromArrayToList(T[] a) {
    ...
}
