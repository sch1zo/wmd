WMD: The WYSIWYM Markdown Editor
================================

Introduction
------------

another fork of wmd. see the fork queue to see where it came from.
It's a jQuery plugin and is very easy to implement.

How to use
----------

Example using wmd with jQuery:

    <html>
        <head>
            <title>WMD Example using jQuery</title>
            <link rel="stylesheet" type="text/css" href="wmd.css"/>

            <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.5.2/jquery.min.js"></script>
            <script type="text/javascript" src="jquery.wmd.min.js"></script>
        </head>
        <body>
            <h1>WMD Example using jQuery</h1>
            <div>
                <textarea class="wmd-input"></textarea>
            </div>
    
            <script type="text/javascript">
                $(function() {
                   $(".wmd-input").wmd(); 
                });
            </script>
        </body>
    </html>

Fork Queue
---

- [RobinBrouwer](https://github.com/RobinBrouwer/wmd)
  - Pull Requests from [Nonpython](https://github.com/Nonpython)
- [Open Library](https://github.com/openlibrary/wmd)
- [Stackoverflow branch of wmd](http://github.com/derobins/wmd)



License
-------

WMD Editor is licensed under [MIT License](http://github.com/openlibrary/wmd/raw/master/License.txt).
