# godot.pipeline-importers
Godot manual importer testing - practical use case tests

# Quality control
Any importer should work the way a .png importer works, if the file is written by another program it should open, provided the file is not corrupted and valid, and can be re-opened in the package it was made by.

The goal is to provide a single version of the truth for the godot importers, we will provide standard supported formats for each file, and require that they work in at least one importer, as importers are fixed we can update their status

Files will be added which test different functionality of the importers.

Per package is preferred, and source files are mandatory.

The goal overall one day will be to automate this testing for now, manual checking is fine.

# Current status / tracker

| Model        	| FBX                   	| GLTF2                      	| Collada              	| escn                 	| Issue tracker 	|
|--------------	|-----------------------	|----------------------------	|----------------------	|----------------------	|---------------	|
| shark.blend  	| failing - mesh broken 	| working                   	| failing - animations 	| failing - animations 	| https://github.com/KhronosGroup/glTF-Blender-IO/issues/791	|
| end of table 	|                       	|                            	|                      	|                      	|               	|
|              	|                       	|                            	|                      	|                      	|               	|

# Examples
If a file was made in maya .mb or .ma must be provided.
If a file was made in blender the .blend must be provided.


# Licensing
The license of your model can be provided in a sub folder, and it can explicitly override the MIT licensing. Please be aware submitting models which are not your own will not be accepted.
