<!-- saved from url=(0023) https://kacos2000.github.io/WindowsTimeline/ --> 
<!-- https://guides.github.com/features/mastering-markdown/ --> 

## Windows 10 Timeline

**SQLite query to parse Windows 10 (1803) Timeline's ActivityCache.db**


![Preview1](https://raw.githubusercontent.com/kacos2000/WindowsTimeline/master/Preview1.PNG)


![Preview2](https://raw.githubusercontent.com/kacos2000/WindowsTimeline/master/Preview2.PNG)


SQLite Tables processed:

- Activities,
- Activity_PackageID,
- ActivityOperation

Either import [the windows timeline database query](WindowsTimeline.sql) to your SQLite program, or Copy Paste the code to a query tab.
Your software needs to support the SQLIte [JSON1 extension](https://www.sqlite.org/json1.html).

Other queries:

1. [A formated Smartlookup view query](SmartLookup.sql)
2. [Activity_PackageID timeline query](Activity_PackageID_Timeline.sql)

**Tested on:**
- [DB Browser for SQLite](http://sqlitebrowser.org/),
- [SQLiteStudio](https://sqlitestudio.pl/index.rvt) as well as
- [SQLite Expert Pro with the JSON1 extension](http://www.sqliteexpert.com/extensions/)

![Timeline preview](https://raw.githubusercontent.com/kacos2000/WindowsTimeline/master/timeline.jpg)<br>
[**Documentation**](WindowsTimeline.pdf) **and analysis of the database and its entries** (pdf file)




