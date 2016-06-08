===========
Hello World
===========


Welcome to ex25's documentation!
================================

Here's an attempt at a code box:

::
    
    print 'here goes nothing'
    > here goes nothing
    
    if 5 + 1 == 6:
        print 'math!!'
    else:
        print 'What is going on?'

Still trying to figure out how to create working links to license and help docs as well as autodoc the code I have included with the project.
        
        Gonna go through the rST quickref documentation to get the syntax down,         then see if I can create a good RTD link for my ex25 example code.

Above, I test the paragraph functionality, and here, I'm testing the *italics* and **bold** functionalities ("inline markup"). Backslashes before asterisks \*should\* remove italicization as well as double back--quotes ("`", apparently).

Now it's time to make some lists:
=================================

Enumerated Lists
^^^^^^^^^^^^^^^^

Lists can be enumerated, bulleted, or definitions.

1. License

2) README

(3) These are the three types of enumeration; we can also use i/I and a/A, and make

    a. Sublists. Hope this works.


Bulleted Lists
^^^^^^^^^^^^^^

- a dash can begin a bulleted list

+ so can a plus sign

  * and an asterisk

Definition Lists
^^^^^^^^^^^^^^^^

word
  the definition of the word is indented two spaces (I think?) and located directly underneath the word.





Guide
^^^^^

.. toctree::
   :maxdepth: 2

   ex25 functions    

   help

   readme

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

