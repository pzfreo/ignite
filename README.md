# ignite
Server-side gateway for MQTT, based in node.js

Please contact me for more information. I'm currently re-factoring and adding documentation.

Ignite is a fairly simple node.js pipe construction that allows interception of each packet
and either responding to the initiator or passing the packet on. 

At the moment, Ignite supports two key functions:

Firstly, it validates credentials against an OAuth2 server and uses the resulting scopes
to perform publish and subscribe authorization.

Secondly, it talks to Docker to launch new Docker instances per user.

However, the aim is to make these functions much more pluggable.
