# islands-and-gaps
My answer to an exercise about islands and gaps in postgreSQL

Given tables "posts" and "users", identify which users poster 3+ times, 3+ months in a row.

Columns of interest include users.id, users.displayname, posts.owneruserid, posts.creationdate

Users.id = posts.owneruserid
