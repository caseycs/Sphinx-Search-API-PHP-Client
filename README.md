# SphinxSearch PHP API

[SphinxSearch](http://sphinxsearch.com/) is a powerful search engine to index MySQL and PostgreSQL 
databases.

This repository is used to make SphinxSearch API PHP Client available through 
[composer](http://getcomposer.org/).

    {
        "require": {
            "silexneutron/sphinxsearch-api": "dev-master"
        }
    }


There is also [branch](https://github.com/romainneutron/Sphinx-Search-API-PHP-Client/tree/psr0) with [PSR-0](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md)
file structure and without class-only constants (for example `SEARCHD_COMMAND_SEARCH` moved
to `SphinxSearchApi_Client::SEARCHD_COMMAND_SEARCH`).

    {
        "require": {
            "silexneutron/sphinxsearch-api": "dev-psr0"
        }
    }


# License

This is licensed under the GNU General Public License
