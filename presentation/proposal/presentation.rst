Display and Management of Geomatics Research Data
-------------------------------------------------

.fx: title

Display and Management of Geomatics Research Data
=================================================

Timothy Daniel Trewartha and  Michiel Johan Baird


.. image :: oct.png
   :scale: 50 %


----

Zamani Project
--------------

* Started by the UCT Department of Geomatics in 2004
* Aims to preserve cultural heritage by documenting sites
  and producing laser scanned models
* Over 100 models of sites in various African countries including
  South Africa, Zimbabwe, Kenya and Tanzania
* Some of the models are very large and contain billions of points

.. image :: zamani.jpg
   :scale: 40 %

----

Problems Faced
--------------

* Fast-growing volume of data
* Difficulty in storing the data
* Difficulty with viewing the large models in real-time
* Data locality issues
* Large number of users interact with the data

----

Solution Approach
-----------------

* To enable viewing of the large 3D models at interactive frame
  rates we will implement a hierachical multi-resolution data
  structure
* A server with a large amount of storage will be procured; this will
  be used to store the models and GIS data, and support the core
  functionalities of the solution.


----

Workbench - Michiel
-------------------

How effective is an automated workflow solution in GIS context?

.. image :: workflow.png


----

Previous work
-------------

* Various fields of science has adopted and implemented
  workflow systems
* These systems have increased efficiency and research output
* GIS research has been shown to be applicable to an automated
  workflow system; this has not however been implemented

----

Proposed Solution
-----------------

* Use an existing workflow system as various platforms already
  exist
* Design a workflow that is applicable to GIS
* Write middleware to integrate with existing GIS tools
* Software that automatically transfers data as it is needed down
  the pipeline

----

Testing Criteria
----------------

* How much does the content delivery system decrease waiting time?
* How effective is the workflow system based on the analytics that
  will be generated be the system.



----

Division of Work
----------------

* Tim will be implementing the hierachical datastructure to enable
  real-time interaction with the large 3D models.
* Michiel will be implementing a Scientific workbench that is
  specialised for GIS research. This will pay special attention
  to data movement and intergration with existing GIS tools.

----

Deliverables
------------

* GIS workbench
* Middleware for core functionalities
* Data Flow Facilitator
* Hierarchical Data Structure
* Streaming Infrastucture

----

Timeline
--------

.fx: timeline

+----------------------------------+-------------------+----------------+
| Description                      | Start             | End            |
+==================================+===================+================+
| Web Presence                     | 25 May            | 12 June        |
+----------------------------------+-------------------+----------------+
| Initial Feasibilty Demonstration | 11 June           | 29 June        |
+----------------------------------+-------------------+----------------+
| Background Chapter               | 2 July            | 29 July        |
+----------------------------------+-------------------+----------------+
| Design Chapter                   | 29 July           | 29 August      |
+----------------------------------+-------------------+----------------+
| First Implementation             | 1 July            | 29 August      |
+----------------------------------+-------------------+----------------+
| Final Implementation             | 29 August         | 28 September   |
+----------------------------------+-------------------+----------------+
| Report Outline Complete          | 28 September      | 10 October     |
+----------------------------------+-------------------+----------------+
| Report                           | 28 September      | 31 October     |
+----------------------------------+-------------------+----------------+
| Poster                           | 31 October        | 3 November     |
+----------------------------------+-------------------+----------------+
| Presentation                     | 11 November       | 18 November    |
+----------------------------------+-------------------+----------------+

