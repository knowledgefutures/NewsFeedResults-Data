# NewsFeedResults-Data
This data repo is under active development and currently, data licensing belongs to the <a href="https://newsq.net/">News Quality Initiative (NewsQ)</a>. Data may not be complete and should not yet be used for research purposes. (In other words, things are still a bit messy, but thanks to your participation, we're working towards something that can be released and used among researchers).  

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