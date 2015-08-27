GLEX is an OpenGL Extension Specification Parser which is used to turn OpenGL extension specification files into a set of compact C source files that can be easily included into existing projects to initialize only the desired extension or core API function pointers.

This is **version 1** of GLEX which parses the human-readable `*.txt` specification files, while <a href="https://github.com/sschuberth/gale/tree/master/glex2">GLEX 2</a> parses the database `*.spec` / `*.tm` files. Both specification file types are linked from the <a href="http://www.opengl.org/registry/">OpenGL Registry</a>. As GLEX is written in PHP, it can be easily used from both the command line and via a web front-end.

Please try out <a href="http://threekings.tk/gale/glex1/">GLEX 1 online</a>.
