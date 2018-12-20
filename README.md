# Software testing homework assignment
### Name: YAO Zifan
### Student ID : 48-189727

## Simple List Model
The problem is in the `remove` definition. The `collection.remove()` call should be checked if successful or not,
before changing the value of `n`.

## Linked List Model
Here, because the `remove` definition was not invalidating the iterator when the call was successful, it caused exception prompt afterwards.
By adding `invalidateIt` after the modification of the value of `n`, we can avoid it.