# tree for FuchsiaOS

Port of [tree](http://mama.indstate.edu/users/ice/tree/) util for Fuchsia OS.


Step by step guide:

1. copy directory "third_party/tree" under "third_party" 

1. under "packages/gn"
	* copy "packages/gn/tree" receipe file

	* add the "tree" receipe to "default" file:

		``{
    	"imports": [
    	...
        "tree"
        ....
        }
        ``
