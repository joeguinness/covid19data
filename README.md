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

# contributing

If you want to help curate the data, you can download
a state's csv file and create new columns for times
at which the totals were updated. We have had success
using the internet wayback machine to look at previous
snapshots of state public health websites. Some governors
are also tweeting daily totals by county. This is how
we got New Jersey data, for example.

You can use the github pull request feature to submit
your data, or you can e-mail the file to 
guinness@cornell.edu. It would also be helpful if you
include screenshots of where you got the data, with
informative filenames on the screenshot images.

# editing in spreadsheet programs

If you edit a file in a spreadsheet program, the
programs try to convert the dates to date format.
To prevent this, change the format to text when
you read the file into your spreadsheet program.
Otherwise, you can edit the files in any text editor.
