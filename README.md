# Java Interfaces
# Main Interfaces in Java

In Java, interfaces are a fundamental feature that allows the definition of methods that must be implemented by concrete classes. Some of the main interfaces in Java include:

## `java.lang.Comparable<T>`
- Defines a `compareTo(T o)` method that is used to compare objects for natural ordering.
- It is commonly used in collections to allow objects to be sorted.

## `java.lang.Runnable`
- Defines the `run()` method, which must be implemented by any class whose instances are executed by a thread.
- It is the basis for creating threads in Java.

## `java.util.List<E>`
- Extends the `Collection<E>` interface and represents an ordered collection that can contain duplicate elements.
- Known implementations: `ArrayList`, `LinkedList`.

## `java.util.Set<E>`
- Extends the `Collection<E>` interface and represents a collection that does not allow duplicate elements.
- Known implementations: `HashSet`, `TreeSet`.

## `java.util.Map<K, V>`
- Defines a collection of key-value pairs, without duplication of keys.
- Known implementations: `HashMap`, `TreeMap`.

## `java.util.Iterator<E>`
- Defines methods for iterating over a collection (`hasNext()`, `next()`, `remove()`).
- It is generally used to traverse elements in a collection.

## `java.util.function.Function<T, R>` (and other functional interfaces in `java.util.function`)
- Represents a function that accepts one argument and produces a result. It is the basis for lambda expressions in Java.
- Other functional interfaces include `Predicate<T>`, `Consumer<T>`, `Supplier<T>`, among others.

## `java.io.Serializable`
- A marker interface that indicates that a class can be serialized, meaning it can be converted into a stream of bytes for storage or transmission.

## `java.util.concurrent.Callable<V>`
- Similar to `Runnable`, but allows a value to be returned and a checked exception to be thrown.
- Mainly used in concurrent environments where tasks that return results need to be executed.

These interfaces play essential roles in the Java API, enabling the creation of more flexible and reusable code.
