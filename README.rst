====================
 TEDmagi 2024-11-15
====================

This is a talk given for TEDmagi on November 15, 2024.

This work is licensed under Creative Commons Attribution-ShareAlike 4.0
International. To view a copy of this license, visit
https://creativecommons.org/licenses/by-sa/4.0/


Download
--------

HTML is generated from this repository. You can follow these steps to
download and browse it:

1. Click the "(⏵) Actions" tab near the top of the page.
2. Select a workflow from the list.
3. Under "Artifacts", you will find an artifact named "generated-site".
   Click the "⤓" download icon to download a zip file.
4. Extract the zip file in a subdirectory.
5. Open the ``index.html`` file in your browser.


Build
-----

Follow these steps to build the HTML:

1. Clone this repository, and change into the directory.

2. Create and activate a virtual environment:
   ::
       $ python3 -m venv venv
       $ source venv/bin/activate

3. Install requirements for building docs:
   ::
       $ pip install -e ".[docs]"

4. Build the docs as HTML:
   ::
       $ make html

5. To serve the docs locally, you can use Python's webserver:
   ::
       $ cd _build/html/
       $ python3 -m http.server 9000
       $ firefox "http://localhost:9000/"

   Alternatively, open ``_build/html/index.html`` in a browser:
   ::
       $ firefox _build/html/index.html
