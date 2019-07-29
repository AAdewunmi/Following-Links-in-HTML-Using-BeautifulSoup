# Following-Links-in-HTML-Using-BeautifulSoup
# This program will use urllib to read the HTML from the data files below,
# extract the href= vaues from the anchor tags, scan for a tag that is in a
# particular position relative to the first name in the list, follow that link and repeat
# he process a number of times and report the last name you find.
# Actual problem: Start at: http://py4e-data.dr-chuck.net/known_by_Dayna.html
# Find the link at position 18 (the first name is 1). Follow that link. Repeat this process 7 times.
# The answer is the last name that you retrieve.
# Hint: The first character of the name of the last page that you will load is: A
# Sample execution
# Here is a sample execution of a solution:
# $ python3 solution.py
# Enter URL: http://py4e-data.dr-chuck.net/known_by_Fikret.html
# Enter count: 4
# Enter position: 3
# Retrieving: http://py4e-data.dr-chuck.net/known_by_Fikret.html
# Retrieving: http://py4e-data.dr-chuck.net/known_by_Montgomery.html
# Retrieving: http://py4e-data.dr-chuck.net/known_by_Mhairade.html
# Retrieving: http://py4e-data.dr-chuck.net/known_by_Butchi.html
# Retrieving: http://py4e-data.dr-chuck.net/known_by_Anayah.html
# The answer to the assignment for this execution is "Anayah".
