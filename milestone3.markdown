---

layout: home

---

# Milestone 3

In this milestone, we look at the data structure choice. The C++ std::map is an 
STL container that is essentially a one for one equivalent to Javas HashMap 
container. While this is effective and provides for fast lookups and insertions,
this structure has no real concept of sequence. Sorting by anything other than
the key is unnecessarily complicated, and would require supplemental containers
to maintain a sort over time. 

The C++ std::vector is essentially a dynamic array, able to automatically grow
when new elements are added. What is important for our purposes is that, like
traditional arrays, std::vector is inherently sequential. The ordering might not
make sense in a given context, but it has an order that we can depend on, and
when that order is changed, that change persists. While insertions and lookups 
are sometimes slower than with std::map, given how useful it can be to order a 
contact list in various ways, the overall advantage goes towards std::vector. 

Additionally, a basic text user interface has been added to demonstrate the code 
functionality.

The code can be found at this repository:


