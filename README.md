# Painting Tool with Screen Mirroring (Java)
<p>This painting tool imlpements a primitive type of screen mirroring feature that is implemented using JAVA sockets. <br>
It keeps track of an activity vector in memory which stores different activities performed by the user,<br> 
these activities represent some type of shape that a user has drawn, each activity object stores some information about the activity.</p>

<p>Whenever a new activity is performed, it is added into this activity vector and a copy of this activity vector is sent to the connected client (if any)<br>
When a new copy of an activity vector is received, the client on the other side automatically draws an identical image on its own canvas using the activity elements that are stored in its activity vector.
</p>
