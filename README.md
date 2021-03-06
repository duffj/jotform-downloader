JotForm Downloader
==================

Uses the jotform-api-python library to download submissions from multiple forms, using the `shelve` library to cache data
to avoid exceeding the JotForm API quota limit.

[![CircleCI](https://circleci.com/gh/duffj/jotform-downloader.svg?style=svg)](https://circleci.com/gh/duffj/jotform-downloader)


Developer Setup
---------------

1. Clone this repository.
2. Run the installation script.
3. Enter the virtual environment.
3. Set your JotForm API key as an environment variable.
4. Run the test script:

Copy and paste this into a shell:

    ./go
    . .env/bin/activate
    source .env/api.key
    python test.py


Revision History
----------------

* 0.1 - print data structures to JSON, cache using the `shelve` library.
* 0.0 - current (not yet working)


References
----------

* http://api.jotform.com/docs/
