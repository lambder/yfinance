YFINANCE
========

A simple utility to download Historical stock prices from Y! Finance.

DEPENDENCIES
------------

yfinance depends on `clj-time` and `clojure.contrib.http.agent`.

USAGE
-----

    (use 'in.freegeek.yfinance)
    (fetch-historical-data "2009-01-01" "2009-01-31" ["AAPL" "IBM" "MSFT" "GOOG"])

FEEDBACK
--------

Email me: b.ghose at GMail
