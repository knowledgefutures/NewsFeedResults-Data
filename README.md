# NewsFeedResults-Data
This data repo is under active development and currently, data licensing belongs to the <a href="https://newsq.net/">News Quality Initiative (NewsQ)</a>. A license for invited users is below. 

### Schema
The schema is available <a href="https://docs.google.com/document/d/1-fmfHvsrQR3QTz7aMQu50vrU6YgBsxqbFU064knyZ3U/edit#"> here</a>. For more information about how this dataset works or was produced, email Momen Bhuiyan (momen [at] vt . edu). 

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


### “NewsQ” News Feed Results End User Terms of Use
(NewsQ API End User Terms of Use, Modified)

_The Project and its Purpose_

The Tow-Knight Center for Entrepreneurial Journalism at the City University of New York (“CUNY”) Craig Newmark Graduate School of Journalism (collectively, "Tow Knight," “we,” or “us”), is an educational center for entrepreneurial journalism dedicated to helping to develop and foster sustainable business models for quality journalism.


To support this mission, we have launched the NewsQ Project (the "Project") to create a system that organizes many of the signals of news quality and credibility proliferating within the digital media ecosystem and funnels these signals in a structured and scalable way. More about the project’s purpose can be found here.


We are now offering access to this Database (“the Database”) to invited users across the broader information ecosystem for use in examining news quality and credibility subject to the below terms. Our belief is that openness and transparency in the data we provide is important to the Project’s success. Accordingly, we strive to make the data we provide as open and reusable as possible, and will be continually working to improve the openness and reusability of the data provided.

_Terms of Use_

Tow Knight CUNY and/or its designated agents will provide access to the Database to invited users free of charge, in order to facilitate the study of the online information ecosystem and the improvement of the same. As consideration for this free service, we require your agreement to the following terms. Please read them carefully and indicate your agreement below.

- Access to the Database is intended only for invited users and organizations.
- You agree not to facilitate any unauthorized access to the Database, and to immediately alert us as soon as possible if you know of, or have reason to suspect, any unauthorized access.
- You may not redistribute data from the Database without prior written permission from us. Our policy is to provide permission for all redistributions reasonably necessary for the purpose of scientific or scholarly publication, but we do require that you provide us with your request in advance. You agree to destroy or return any copies of non-reusable data in your possession upon termination of this agreement or of your access to the Database.
- You may not use the Database for any unlawful, illegal (in the United States or any jurisdiction in which you are located), or injurious purposes , or to violate the legal rights (including without limitation, the rights of privacy and publicity) of any third party.
- You may not use the Database in any way that damages, disables, overburdens or impairs the operation of the Database.
- You may not modify or recombine data exported from the Database in any way that would make the data false or misleading.
- You may not use the Tow Knight, News Quality Aggregator (or NewsQ), CUNY or Craig Newmark Graduate School of Journalism name in any way to suggest an affiliation or endorsement of any individual, organization, product, or service without the prior written consent of Tow Knight. Accurately attributing NewsQ as a data source is both welcome and encouraged.
- All data, and all Database access, are provided as is. To the extent allowable by law, we disclaim all warranties of any kind, express or implied, in the data and in our provision of access to it. We make no representations about the accuracy or completeness of the data, and no representations that the data do not infringe any third party rights.
- By indicating your agreement, you represent that you: a. Are an invited user or an authorized agent of an invited organization; b. Have full power and authority to enter into this agreement; and c. Intend to use the Database solely for its intended purposes: improving the information quality ecosystem and/or our understanding of it.
- This agreement is non-transferable, and is binding on all of your successors, agents, and affiliates. Any attempted assignment of this agreement made without Tow Knight’s written consent will be null and void.
- You agree to indemnify and hold harmless Tow Knight, and its agents, affiliates and representatives, and their respective directors, officers, employees and contractors from and against any liability, damage, loss, cost or expense (including, without limitation, reasonable attorneys’ fees) arising from or related to your use of the Database or your breach of these End User Terms of Use.
- While our intention is to continue maintaining the Database indefinitely as a public service, we may stop maintaining or providing access to it at any time. We may terminate this agreement and your access to the Database at any time for any reason or for no reason, in our sole discretion.

_Guidance on citing the Database_
Because our signals are a limited snapshot of information across time, we recommend citing the Database as a whole rather than any individual platform provider.  A suggested citation format is as follows:
Tow-Knight Center for Entrepreneurial Journalism at the City University of New York (“CUNY”) Craig Newmark Graduate School of Journalism and Hacks/Hackers. 2021. NewsQ News Feed Results [database]. 

