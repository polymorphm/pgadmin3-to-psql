pgadmin3-to-psql
================

It is a tiny utility that helps to do migration from ``pgAdmin3`` to ``psql``.
It recreates a server connection list in psql-friendly manner.

Status
------

Release ``pgadmin3-to-psql-0.1.2``.

Using Example
-------------

    $ ./pgadmin3-to-psql ~/.pgadmin3 ~/.pgserv
    
    $ . ~/.pgserv/my-group/my-favorite-server.env
    
    $ psql

The environment variable ``PGPASSFILE`` can help you if you want to bring
the file ``.pgpass`` from one computer to another.
