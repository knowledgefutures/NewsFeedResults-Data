# NewsFeedResults-Data
The data licensing of this repository originally belonged to the <a href="https://newsq.net/">News Quality Initiative (NewsQ)</a>, and was transferred to Knowledge Futures (hello [at] knowledgefutures . org) for archiving.

### Schema
The schema is available <a href="https://docs.google.com/document/d/1_5VaOiFLzhM5Qu2ccWoX5BGkoeo50eQ2hUs5R2WXGvo"> here</a>. For more information about how this dataset works or was produced, email Momen Bhuiyan (momen [at] vt . edu). 

### Description
1. Data Folder
    1. Collection Period: 07.01.2021 - 08.14.2021
    1. filename format: %source%\_%zipcode%\_%datetime%.csv and %source%\_%zipcode%\_%datetime%_meta.csv (for corresponding meta data)
    2. everyday data was collected twice.
    4. initially data was collected for zip 24060. five zipcode-wise data collection started on 07-06 evening. 2 albuquerque zip codes added on 07-21.
    5. There are some missing dates including  07-04 evening, 07-09, 07-27 morning ...
    6. Twitter data is missing for 07.20 and 07.21 due to an exception
    7. Metadata was collected using newspaper api. Each metadata file has some items due to 403 and 500 error codes (notably for some googlenews, wsj and newsweek links). To collect these missing items, using different library may/not work. need more investigation into this issue
2. Screenshot Folder
    1. Collection Period: 07.05.2021 - 08.14.2021
    2. filename format: %source%\_%datetime%\_%(optional)page/scroll%.csv (forgot to add zip. to connect use datetime.)


_Guidance on citing the Database_
Because our signals are a limited snapshot of information across time, we recommend citing the Database as a whole rather than any individual platform provider.  A suggested citation format is as follows:
Tow-Knight Center for Entrepreneurial Journalism at the City University of New York (“CUNY”) Craig Newmark Graduate School of Journalism and Hacks/Hackers. 2021. NewsQ News Feed Results [database]. 

