WMD: The WYSIWYM Markdown Editor
================================

Introduction
------------

This is a fork from the wmd branch for [Open Library](https://github.com/openlibrary/wmd), which is forked from the [Stackoverflow branch of wmd](http://github.com/derobins/wmd).
I forked it and added some of the Pull Requests [Nonpython](https://github.com/Nonpython) created for the Stackoverflow branch. It's a jQuery plugin and is very easy to implement.

How to use
----------

Example using wmd with jQuery:

    <html>
        <head>
            <title>WMD Example using jquery</title>
            <link rel="stylesheet" type="text/css" href="wmd.css"/>

            <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.5.2/jquery.min.js"></script>
            <script type="text/javascript" src="jquery.wmd.min.js"></script>
        </head>
        <body>
            <h1>WMD Example using jquery</h1>
            <div>
                <textarea id="notes"/>
            </div>
    
            <script type="text/javascript">
                $().ready(function() {
                   $("#notes").wmd(); 
                });
            </script>
        </body>
    </html>

License
-------

WMD Editor is licensed under [MIT License](http://github.com/openlibrary/wmd/raw/master/License.txt).


