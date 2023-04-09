# DS_client-server_socket_multithreaded
Short Description
Simulates the operation of a restaurant in which many processes take place at the same time and synchronization issues often appear

Full Description
Simulates the operation of a restaurant in which many processes take place
at the same time and synchronization issues often appear. There are 3 chefs in this restaurant, each of whom makes a different kind of food. The 1st
chef mainly deals with grilling fish, the 2nd chef with creation seafood dishes and the 3rd
chef deals with varieties of meat. The customers of a restaurant can simultaneously request some portions of one of these items.

The application we will implement consists of a "server" that has three
different storage locations. These slots are used for storage
of food per item already prepared in the restaurant. Each of these
seats has a capacity of 5 portions.The "client" who can
contact the server can be either the chef or restaurants customers.

When a customer of the store requests some portions of food per item and no
are all available, we'll "block" the request until the respective chefs
make the portions required. Only then can the customer be served. also
when one of the 3 storage slots is full the chef of the specific species will have to
"blocks" and wait until a customer requests even a portion of the
specific type of food.

Hints for implementation
Random delay times between executions of actions from
the chefs and the customers of the store.
Display appropriate messages for each event that occurs (eg fish production
from 1st chef, request for variety of meats from customer).
