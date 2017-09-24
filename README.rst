pgadmin3-to-psql
================

It is a tiny script that helps do migration from ``pgAdmin3`` to ``psql``.
It recreates a server list in psql-friendly manner.

Status
------

developer version (git master branch).

Using Examples
--------------

    $ ./pgadmin3-to-psql ~/.pgadmin3 ~/.pghosts
    
    $ . ~/.pghosts/my-favorite-server
    
    $ psql

The environment variable ``PGPASSFILE`` can help you if you want to bring
the file ``.pgpass`` from a computer to another.
