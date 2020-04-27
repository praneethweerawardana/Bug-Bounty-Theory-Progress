1) Open the url and then trying to logged Micro-CMS Changelog Edit page
2) open burpsuite and intercept on
3) save out put report and doing sql injection
   sqlmap -r <path output file store> title username --dbs --dump
4) Then firstly can see Flag0 and after display login credentials
5) login using these credentials and can see another Flag.
