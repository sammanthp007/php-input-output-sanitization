# Project 2 - Input/Output Sanitization

Time spent: **X** hours spent in total

## User Stories

The following **required** functionality is completed:

1\. [ ]  Required: Import the Starting Database

2\. [ ]  Required: Set Up the Starting Code

3\. [ ]  Required: Review code for Staff CMS for Users

4\. [ ]  Required: Complete Staff CMS for Salespeople
  * [ ]  Required: index.php
  * [ ]  Required: show.php
  * [ ]  Required: new.php
  * [ ]  Required: edit.php

5\. [ ]  Required: Complete Staff CMS for States
  * [ ]  Required: index.php
  * [ ]  Required: show.php
  * [ ]  Required: new.php
  * [ ]  Required: edit.php

6\. [ ]  Required: Complete Staff CMS for Territories
  * [ ]  Required: index.php
  * [ ]  Required: show.php
  * [ ]  Required: new.php
  * [ ]  Required: edit.php

7\. [ ]  Required: Add Data Validations
  * [ ]  Required: Validate that no values are left blank.
  * [ ]  Required: Validate that all string values are less than 255 characters.
  * [ ]  Required: Validate that usernames contain only the whitelisted characters.
  * [ ]  Required: Validate that phone numbers contain only the whitelisted characters.
  * [ ]  Required: Validate that email addresses contain only whitelisted characters.
  * [ ]  Required: Add *at least 5* other validations of your choosing.

8\. [ ]  Required: Sanitization
  * [ ]  Required: All input and dynamic output should be sanitized.
  * [ ]  Required: Sanitize dynamic data for URLs
  * [ ]  Required: Sanitize dynamic data for HTML
  * [ ]  Required: Sanitize dynamic data for SQL

9\. [ ]  Required: Penetration Testing
  * [ ]  Required: Verify form inputs are not vulnerable to SQLI attacks.
  * [ ]  Required: Verify query strings are not vulnerable to SQLI attacks.
  * [ ]  Required: Verify form inputs are not vulnerable to XSS attacks.
  * [ ]  Required: Verify query strings are not vulnerable to XSS attacks.
  * [ ]  Required: Listed other bugs or security vulnerabilities


The following advanced user stories are optional:

- [ ]  Bonus: On "public/staff/territories/show.php", display the name of the state.

- [ ]  Bonus: Validate the uniqueness of `users.username`.

- [ ]  Bonus: Add a page for "public/staff/users/delete.php".

- [ ]  Bonus: Add a Staff CMS for countries.

- [ ]  Advanced: Nest the CMS for states inside of the Staff CMS for countries


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

This section contains all the steps that I took while building this application
This is all happening in the www/ (srv/http/ for arch linux) directory.

Step 1: Download the files

Step 2: Unzip the zipped files

Step 3: Move the *.sql file inside the unzipped directory

Step 4: Create a database called assignment02
```
mysql -u root -p
>> create database assignment02;
>> show databases;
>> exit

# put the definition in the *.sql file to our database assignment02
mysql -u root -p assignment02 < globitek_week2.sql

```

Step 5: Fill in the database credential in private/db_credentials.





## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
