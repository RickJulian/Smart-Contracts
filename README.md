# Smart-Contracts

The constructor uses "now" to delploy the contract; donations are allowed within a frame of 20 minutes from "now"
(aside of another block that the contract's creator can set).

Once time has passed then another time lock control is performed: this time block.timestamp is required to be greater than 21 minutes
over the initial "now".
