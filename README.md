# PIR Research Engineer Challenge
Programming Challenge to find a PIR Research Engineer for HashCloak

**WARNING: Do not fork this repository or make a public repository containing your solution. Either copy it to a private repository or submit your solution via other means.**

At HashCloak, we have been trying to [seek a research engineer for our internal private information retrieval (PIR) projects](https://hackmd.io/@hashcloak/BkBvAnkgY) for quite some time now but it has proven to be a challenge. As such, we are taking a different approach to recruit someone for this role.

If you are interested, attempt the programming challenge below and send your solutions to info@hashcloak.com

---

## Question 1
Implement a B+ tree in either C, C++, Go or Rust. 
Your B+ tree implementation must have the following API:
- `AddNode()`: Add a new node to the tree
- `RemoveNode()`: Remove an existing node from the tree
- `AddSubtree()`: Add a subtree to the existing tree
- `RemoveSubtree()`: Remove a subtree from the existing tree
- `Length()`: Return the length of the tree
- `FindNode()`: Find a particular node in the tree

## Question 2
Implement a simple key-value store that uses your B+ tree implementation from Question 1.
Your key-value store must have the following functionality
- Support addition and removal of keys
- Client-Server Networking
- Persistent storage to disk
