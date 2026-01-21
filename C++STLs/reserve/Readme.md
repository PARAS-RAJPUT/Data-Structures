# Reserve

reserve() is a member function of std::vector that pre-allocates memory for a specified number of elements without changing the vector’s size.

It is mainly used to:

Improve performance

Avoid repeated reallocations

Prevent iterator and pointer invalidation during growth


