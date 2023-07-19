# Hash Tables 

- Use an analogy
  A Hash Table is like a library cabinet with labeled compartments. Each book (data) has a unique identifier (ISBN). A Hash Function determines which compartment a book should go into based on its ISBN. When you want to find a book, you use the ISBN to calculate the compartment and go directly to that location. It allows for fast data retrieval and organization.

- WHY, WHAT, HOW structure

**WHY Hash Tables?**

Hash Tables are used in computer science and software development for several key reasons:

1. **Fast Data Retrieval**: Hash Tables allow for efficient and fast data retrieval. With an appropriate hash function and minimal collisions, the time complexity for accessing elements is generally O(1), making it an ideal choice for large datasets.

2. **Data Organization**: They provide a structured way to store and organize data based on unique keys. This allows for easy insertion, deletion, and searching of elements.

3. **Key-Value Storage**: Hash Tables are commonly used to implement key-value pairs, where each key maps to a corresponding value. This association is useful for building dictionaries, databases, caches, and more.

4. **Addressing Memory**: Hash Tables play a crucial role in memory addressing, as they provide a mechanism to map keys to memory addresses, facilitating quick access to data stored in different memory locations.

**WHAT is a Hash Table?**

A Hash Table is a data structure that organizes and stores data using a technique called hashing. It consists of an array (or a dynamic list) of compartments, also known as "buckets." Each bucket can store one or more key-value pairs. The Hash Table uses a hash function to map unique keys to specific bucket positions.

**HOW does a Hash Table work?**

1. **Hash Function**: A Hash Table starts with an array (list) of fixed or dynamic size. A hash function takes a key as input and generates a unique index, or "hash code," which corresponds to a specific bucket in the array.

2. **Hashing the Key**: When data needs to be inserted into the Hash Table, the key-value pair is passed to the hash function. The function calculates the hash code from the key and determines the bucket where the pair should be placed.

3. **Handling Collisions**: Collisions may occur when two different keys result in the same hash code (hash collision). To resolve collisions, various techniques can be used, such as chaining (using linked lists or other data structures inside the bucket) or open addressing (probing nearby buckets).

4. **Insertion and Retrieval**: To insert data, the key is hashed, and the value is placed into the corresponding bucket. When you want to retrieve data, the key is hashed again to locate the appropriate bucket, and then the value is returned.

5. **Deletion**: When deleting data, the key is hashed to find the bucket, and the corresponding key-value pair is removed.

6. **Resizing**: As the number of elements in the Hash Table grows or shrinks, it may become necessary to resize the underlying array to maintain efficiency. This involves rehashing all the keys and redistributing the data across the new array.

In summary, a Hash Table is a data structure that stores and retrieves data based on unique keys using a hash function. It offers fast data retrieval, efficient data organization, and is commonly used for key-value storage and memory addressing in various software applications.
