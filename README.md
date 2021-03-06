# Welcome to `hockey.db`

A free open public domain National Hockey League (NHL) database 'n' schema
(`hockey.db`) for use in any (programming) language
(e.g. uses plain text fixtures/data sets).


## Usage

Use the `sportdb` command line tool to build your own `hockey.db` copy
from the plain text fixtures.  Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/openmundi/world.db.git

Step 2:  Get a copy the `hockey.db` fixtures

    $ git clone git://github.com/opensport/hockey.db.git

Step 3:  Let's build the `hockey.db`

    $ sportdb setup --include ./hockey.db --worldinclude ./world.db

That's it.
See the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby) for more.


## License

The `hockey.db` schema, data and scripts are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Open Sports Database & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
