Last generated on 13-Apr-2015, 14:45 UTC-5.

Activity since last data dump (13-Apr-2015) will be incorrect, as it contains only
review activity (from scraped profiles) but not other activity (from sede).

Data for SO, MSO, MSE, and combined data for all three is included. Each subdirectory
contains a set of CSV files.

Each CSV file is histogram in weekly bins, date range is earliest date of any activity
by any nominee to now (across all included sites); so all files have same date range.

Columns:

  date - seconds since epoch of end of week that bucket is for
  total - total activity events
  accept,badge,comment,post,review,revision,suggest - equivalent to profile page tabs.

Voting, flagging, activity on delete posts is not included, it is not available.

SEDE query for non-review activity is here: http://bit.ly/1CJyLcV

seactivity.db is an sqlite database containing candidate info and all activities for
all candidates.


- Jason