CMPUT404-assignment-websockets
==============================

CMPUT404-assignment-websockets

See requirements.org (plain-text) for a description of the project.

Make a shared state Websockets drawing program

Prereqs
=======
Create a virtual environment and install the required dependencies.

```bash
virtualenv venv --python=python3
source venv/bin/activate
pip install -r requirements.txt
```

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.

freetests.py is LICENSE'D under a BSD-like license:

From ws4py

Copyright (c) 2011-2014, Sylvain Hellegouarch, Abram Hindle
All rights reserved.

Copyright 2020 Cecilia Wei

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0


Contributors
============

* Mark Galloway
* Abram Hindle
* Cole Mackenzie

References
============
[Dr.Hindle's Websockets Examples](https://github.com/uofa-cmput404/cmput404-slides/tree/master/examples/WebSocketsExamples)

[Using javascript to generate rainbow corlor palette](https://stackoverflow.com/a/32471000)<br>
Author: [Juan Lopes](https://stackoverflow.com/users/1327235/juan-lopes)<br>
Function used: HSVtoRGB(h,s,v), rainbow(p)<br>
modification when using: instead of using an index list for the variable p, I used the position x's value and it worked well.<br>
