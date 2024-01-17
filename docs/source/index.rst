.. Flask Example documentation master file, created by
   sphinx-quickstart on Tue Jan 16 21:36:05 2024.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. .. toctree::
..    :maxdepth: 2
..    :caption: Contents:
..    :numbered:


books Database 
=========================================
Database stores book data  

.. automodule:: flask_orm_schema 
   :members: Book
   :no-index:
.. list-table:: Table: books
   :widths: 25 25 25 25
   :header-rows: 1

   * - id
     - author
     - title
     - available
   * - 
     - 
     - 
     - 
   * - 
     - 
     - 
     - 

.. automodule:: flask_orm_schema 
   :members: BirthYear

.. list-table:: Table: birth_years
   :widths: 25 25
   :header-rows: 1

   * - author
     - birth_year
   * - 
     - 

.. note:: 
   SQLAlchemy used to build database relational mapping

Numbers API
=========================================
CRUD routines to read and write to database 

.. automodule:: flask_app
   :members: 

.. Warning:: 
   The data handled by server is not persistent after shutdown. Also, data may not be syncrhonized if run with multiple server processes. 

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
