# Google Maps API Interface
_maps_interface.py_ can make a request to Google Maps and get the steps needed to get to a destination. The code stores the raw response in _response.json_. Then, the nodes and its coordinates are extracted and stored in _nodes.json_. This file can be used to quickly deliver the coordinates of the next node to the vehicle.