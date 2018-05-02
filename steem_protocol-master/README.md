Steem Protocol
----------------
This library defines the blocks, transactions, operations, and static validation that is independent of chain state. It
can be used to build and sign transactions.

Dependencies
------------

This library is designed to have minimal 

- fc - defines the reflection used for serialization of the structures
- boost - used by fc and/or directly 

Building
--------
This library is designed to be a submodule of the steem repository and will not build on its own.
