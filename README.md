# SQLi(SQL injection)

#### What Is SQLi (SQL injection)?

SQL injection is a web security vulnerability. In some cases, it allows an attacker to access the database system, so the attacker can delete or change database data that the attacker should not be allowed to do. or in other cases, the attacker can receive the user's information. In short, SQLi is a vulnerability created by a negligent creator, allowing ordinary users to exploit it. causing serious consequences in the database system.
#### Impact of SQLi (SQL injection)

As a result, ordinary users can access the database system. Edit, delete or query the system's database data. Causes serious loss to the ownership company

![SQLi](https://github.com/DOMBNC/SQLi/assets/101182846/c1871951-83d2-4ed4-8ed7-e5e9f9de2145)

#### How to detect web SQL injection vulnerabilities?

You can use a systematic set of tests on the application or website entry points to detect web SQL injection vulnerabilities. Here are some common ways to detect:
* You can use the single quote character ' and look at the error message to identify it.
* You can use boolean conditional statements such as OR 1=1, 2=2, 'a' = 'a', 3>2 and so on. Look at the response results of the app/website to identify.
* you can use sleep(time) statement and see the response delay time of the application/website.
* you can also use the scan on Burp Suite tool to detect SQLi.
