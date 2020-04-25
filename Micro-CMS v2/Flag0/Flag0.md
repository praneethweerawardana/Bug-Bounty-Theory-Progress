1) open the url
2) this is vulnarable for the SQL Injection Attack.
3) when we trying to create new page or edit already create pages it will asked login credentials. this is vulnarable for the SQL injection. so type blah' or 1=1-- in the username fiels and press enter. Then we can see
   error as SELECT password FROM admins WHERE username=\'%s\'' % request.form['username'].replace('%', '%%')) == 0:, Go back and type Username = ' UNION SELECT '123' AS password# and password = 123. then it will logged to page 3 and display flag.
4) copy and submit flag   
