# Remote Injectable Modules System

What is a Remote Injectable Module (RIM)?  A Remote Injectable Module is a component that can be sent from a server and injected into a recieving 
client.  The recieving client should be setup to recieve the component and display it to the end-user.

The components that are sent from the server to the clients should be packed into a single small package that makes it easy to transmit.  Keep in mind, 
if you use the RIM System to populate your client with content, it will be a lot of content being sent across the wire.  To help combat this, you can 
use a caching service on the client that has a TTL.  When the TTL runs out, the client should ask for a new copy of the component.


