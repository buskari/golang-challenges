 ## Problem

In this challenge, you need to develop a data structure that behaves like an LRU Cache. An LRU (Least Recently Used) Cache is a type of data structure that stores up to **X** items. When **X** items are already stored, the least recently accessed item is removed.

## Requirements

Write a structure/class that represents the **LRU Cache**.

The defined type should have three methods/functions:

- **Constructor function**: receives the cache capacity, an integer.
- **Get method**: receives a key (string) and returns a value of any type.
- **Set method**: receives the key and the value.

### Get Method

- Returns `-1` if there is no item for the provided key.
- Keeps track of the access order for each key.

### Set Method

- Stores a value based on a key if the number of stored items is below the capacity.
- Replaces the least recently accessed item if the cache has reached its capacity.
