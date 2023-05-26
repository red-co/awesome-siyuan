try SQLite online https://sqliteonline.com/.

use SQLite query and todo as tasks,

1. this snippets query todo more than 1 day.
```sqlite3
SELECT * FROM blocks WHERE strftime('%Y%m%d%H%M%S','now') - updated < 1000000 AND subtype = 't' AND type = 'i'
```
