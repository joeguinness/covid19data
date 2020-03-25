# covid19data
repository for covid 19 (coronavirus) data

# data format

Each state has its own file. There is a row for
each county. The first column gives the county
names. The subsequent columns correspond to
times at which the total cases in each county
are updated. The column headings give the update
time in the format

2020-03-25 15:35

for an update at 3:35pm on March 25. The cells
contain the total number of confirmed cases
in each county up to the update time. Zero
counts can be left blank.

# editing in spreadsheet programs

If you edit a file in a spreadsheet program, the
programs try to convert the dates to date format.
To prevent this, change the format to text when
you read the file into your spreadsheet program.
Otherwise, you can edit the files in any text editor.
