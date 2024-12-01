# Number row characters 
! exclamation
@ at the rate
# hash
$ dollar sign
% percentage
^ up
& and
* star
( open bracket
) close bracket
I am Ali Samid Waleed
This is the COMP1238.
## Keyboard shortcuts
Shortcuts I frequently use: 
- Ctrl-C (copy)
- Ctrl-V (paste)
- Ctrl-Z (undo)

Shortcuts I would like to start using: 
- Ctrl-A (select all)
- Win-D (show desktop)
- Super-Hyper-Meta-F (I don’t even have such keys, but it sounds impressive)
[CLI commands](docs/cli.md)
https://sqliteonline.com/#sqltext=%23url-sqlite%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fkamrik%2FIntroText%2Frefs%2Fheads%2Fmain%2Fexamples%2Fsql%2Ft177.db%0D%0A%23tab-name%3Dt177.db%0D%0ASELECT%20*%20FROM%20courses%3B%0ASELECT%20*%20FROM%20assignments%0ALIMIT%2010%3B%0ASELECT%20count(*)%20FROM%20courses%3B%0ASELECT%20min(due_date)%20FROM%20assignments%3B%0A%0ASELECT%20*%0AFROM%20%20courses%0AWHERE%20course_name%20LIKE%20'Intro%25'%3B%0A%0ASELECT%20*%0AFROM%20%20assignments%0AWHERE%20status%20!%3D%20'Completed'%0AORDER%20BY%20due_date%3B%0ASELECT%20course_id%2C%20title%2C%20status%2C%20due_date%0AFROM%20assignments%0AWHERE%20status%20!%3D%20'Completed'%09%0A%20%20AND%20course_id%20LIKE%20'COMM%25'%0A%20%20AND%20due_date%20%3C%20'2024-12-31'%0AORDER%20BY%20due_date%3B%0ASELECT%20title%2C%20due_date%0AFROM%20assignments%0AWHERE%20course_id%20%3D%20'COMP1234'%3B%0ASELECT%20MIN(due_date)%20AS%20earliest_due_date%0AFROM%20assignments%3B%0ASELECT%20MAX(due_date)%20AS%20latest_due_date%0AFROM%20assignments%3B%0ASELECT%20title%2C%20course_id%0AFROM%20assignments%0AWHERE%20due_date%20%3D%20'2024-10-08'%3B%0ASELECT%20title%2C%20due_date%0AFROM%20assignments%0AWHERE%20due_date%20LIKE%20'2024-10%25'%3B%0A%0A%0A
https://sqliteonline.com/#sqltext=%23url-sqlite%3Dhttps%3A%2F%2Fraw.githubusercontent.com%2Fkamrik%2FIntroText%2Frefs%2Fheads%2Fmain%2Fexamples%2Fsql%2Ft177.db%0D%0A%23tab-name%3Dt177.db.1%0D%0AINSERT%20INTO%20assignments%20(course_id%2C%20title%2C%20status)%20%0AVALUES%20('COMP1238'%2C%20'Assignment%20with%20no%20date'%2C%20'Not%20Started')%3B%0A%0ASELECT%20*%20FROM%20assignments%0ALIMIT%2010%3B%20%0A%0ASELECT%20count(*)%20FROM%20courses%3B%0A%0ASELECT%20min(due_date)%20FROM%20assignments%3B%0A%0ASELECT%20*%0AFROM%20%20courses%0AWHERE%20course_name%20LIKE%20'Intro%25'%3B%0A%0ASELECT%20sqlite_version()%3B%0A%0ASELECT%20upper('ABCxyz')%3B%0A%0ASELECT%20length('abcde')%3B%0A%0ASELECT%207*5%3B%0A%0ASELECT%20concat('ABC'%2C%20'-'%2C%20'xyz')%3B%0A%0ASELECT%20date()%3B%0A%0ASELECT%20strftime('%25Y'%2C%20due_date)%20AS%20Year%2C%20*%20%0AFROM%20assignments%3B%0A%0A%0ASELECT%20DISTINCT%20SUBSTRING(course_id%2C%201%2C%204)%20%0AFROM%20courses%3B%0A%0A%0ASELECT%20SUBSTRING(course_id%2C%201%2C%204)%20AS%20prefix%2C%20count(*)%0AFROM%20courses%0AGROUP%20BY%20prefix%3B%0A%0ASELECT%20*%0AFROM%20%20assignments%0AWHERE%20status%20!%3D%20'Completed'%0AORDER%20BY%20due_date%3B%0A%0A%0ASELECT%20course_id%2C%20title%2C%20status%2C%20due_date%0AFROM%20assignments%0AWHERE%20status%20!%3D%20'Completed'%09%0A%20%20AND%20course_id%20LIKE%20'COMM%25'%0A%20%20AND%20due_date%20%3C%20'2024-12-31'%0AORDER%20BY%20due_date%3B
