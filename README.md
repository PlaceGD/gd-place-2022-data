([context](https://youtu.be/XZXZGOkJ92w))

# gd-place-data
History data from the GD-Place event, in case anyone wants to analyze it

# how to use
Each element in the `history.json` represents an action performed by a user during the event.
If the elements includes a `placedObject` key, it represents a placed object, otherwise it represents a deletion.

# object data format
`[id];[x];[y];[rotation];[flip];[scale];[zOrder];[mainColor];[mainBlending];[mainOpacity];[detailColor];[detailBlending];[detailOpacity]`