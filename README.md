# JQJiraboard

JIRA stats for [Panic Status Board](http://www.panic.com/statusboard/) (iPad app)

# Screenshot

<p align="center" >
  <img src="http://s221041438.mialojamiento.es/test/JQJiraboard/jiraboard.PNG" alt="JQJiraboard" title="JQJiraboard">
</p>

## Usage

```
define('TITLE', 'TITLE'); 									// set the chart title
define('JIRA_URL', 'https://yourcompany.atlassian.net'); 	// your jira host
define('USERNAME', 'username'); 							// username
define('PASSWORD', 'password'); 							// password
define('REFRESH_RATE','600'); 								// refresh the chart every X seconds
define('MAX_RESULTS','200'); 								// query maximum results
$people = array("user1","user2","user3","user4");			// usernames to monitorize
```

## Items
- user_list.php: User's task list
- user_status.php: Chart showing the number of issues, open, resolved, fixed & closed.
- team_five_day_stats.php: comparision between open and closed task during the last five days.
- team_status.php: given an array of users, this chart shows the number of task for each one.

## License

The MIT License (MIT)

Copyright (c) 2013 Javier Querol

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
