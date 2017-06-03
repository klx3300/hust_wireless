HUST_WIRELESS Login Tool
=========================
This is a simple comand-line tool to login in HUST\_WIRELESS **without a Web Browser**


THIRD-PARTY DEPENDENCIES
------------------------
This simple tool is written in python using these libraries:

* requests - Dealing with HTTP requests


USAGE
-----
    hust_wireless.py

    hust_wireless.py -u <username> -p <password>

    hust_wireless.py -c <configure_file>
    (configure file examples are given as 'example.json')

    (the two sample usages above can be run as daemon mode with option -d)
    (try --help for more detailed descriptions.)

    hust_wireless.py -l
    (logout)
