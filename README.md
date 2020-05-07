# godot.ci-pipeline-importers
Godot manual importer testing - practical use case tests

The goal is to provide a single version of the truth for the godot importers, we will provide standard supported formats for each file, and require that they work in at least one importer, as importers are fixed we can update their status

## Current status / tracker

| Source (required)        	| FBX                   	| GLTF2                      	| Collada              	| escn                 	|
|--------------	|-----------------------	|----------------------------	|----------------------	|----------------------	|
| shark.blend  	| failing - mesh broken 	| failing - animation broken 	| failing - animations 	| failing - animations 	|
| end of table 	|                       	|                            	|                      	|                      	|
|              	|                       	|                            	|                      	|                      	|


Files will be added which test different functionality of the importers.

Per package is prefered, and source files are manditory.

### For example
If a file was made in maya .mb or .ma must be provided
If a file was made in blender the .blend must be provided.


