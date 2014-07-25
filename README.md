fintp_routingengine
===================

Performs basic ETL routines on messages.

Requirements
------------
- Boost
- Xerces-C
- Xalan-C
- pthread
- **fintp_utils**
- **fintp_log**
- **fintp_transport**
- **fintp_udal**
- **fintp_base**
- **fintp_ws**

See [Getting Started](http://www.fintp.org/getting-started/) to build and install this requirements

Building
-----
- On Unix-like systems, **fintp_routingengine** uses the GNU Build System (Autotools) so we first need to generate the configuration script using:


        autoreconf -fi
Now we must run:

        ./configure
        make

- For Windows, a Visual Studio 2010 solution is provided.

Installation
-----
See [Installation](https://github.com/FinTP/fintp_routingengine/wiki/Installation) for steps required to install and configure the Routing Engine.

Usage
-----
See [Usage](https://github.com/FinTP/fintp_routingengine/wiki/Usage) for a list of usage scenarios.

Contributing
-----
See [How To Contribute](http://www.fintp.org/how-to-contribute) for a list of areas where help is needed.

License
-------
- [GPLv3](http://www.gnu.org/licenses/gpl-3.0.html)

Copyright
-------
COPYRIGHT.  Copyright to the SOFTWARE is owned by ALLEVO and is protected by the copyright laws of all countries and through international treaty provisions. 
NO TRADEMARKS.  Customer agrees to remove all Allevo Trademarks from the SOFTWARE (i) before it propagates or conveys the SOFTWARE or makes it otherwise available to third parties and (ii) as soon as the SOFTWARE has been changed in any respect whatsoever. 
