Last generated on 4/10/2015.

Activity since last data dump (4/6/2015) will be incorrect, as it contains only
review activity (from scraped profiles) but not other activity (from sede).

Each file is histogram in weekly bins, date range is earliest date of any activity
by any nominee to now; so all files have same date range.

Columns:

  date - seconds since epoch of end of week that bucket is for
  total - total activity events
  accept,badge,comment,post,review,revision,suggest - equivalent to profile pgae tabs.

Voting and flagging activity is not included, of course.

seactivity.db is an sqlite database containing candidate info and all activities for
all candidates.


- Jason