# SQLi(SQL injection)

#### What Is SQLi (SQL injection)?

SQL injection is a web security vulnerability. In some cases, it allows an attacker to access the database system, so the attacker can delete or change database data that the attacker should not be allowed to do. or in other cases, the attacker can receive the user's information. In short, SQLi is a vulnerability created by a negligent creator, allowing ordinary users to exploit it and causing serious consequences in the database system.
#### SQLi types
SQL injection has 3 main types:
* In-band SQLi
* Inferential SQLi (Blind SQLi)
* Out-of-band SQLi
![SQL_Injection_Type](https://github.com/DOMBNC/SQLi/assets/101182846/7eae2824-a4ab-46c0-8999-a73204ce1e7e)
#### How it works
* In-band SQLi
This is the most common form of attack and is also the easiest to exploit SQL Injection vulnerabilities
This is an example of In-band SQLi:
![Capture](https://github.com/DOMBNC/SQLi/assets/101182846/abf3f182-d9a5-4af9-987c-31175ebf472e)


#### Impact of SQLi (SQL injection)

As a result, attackers can take advantage of this vulnerability to retrieve users' data such as:
* User account and password
* personal data
In addition, it also can directly affect the database.

![SQLi](https://github.com/DOMBNC/SQLi/assets/101182846/c1871951-83d2-4ed4-8ed7-e5e9f9de2145)

#### How to detect web SQL injection vulnerabilities?

You can use systematic tests on the application or website entry points to detect web SQL injection vulnerabilities. Here are some common ways to detect:
* You can use the single quote character ' and look at the error message to identify it.
* You can use boolean conditional statements such as OR 1=1, 2=2, 'a' = 'a', 3>2 and so on. Then look at the response results of the app/website to identify.
* you can use sleep(time) statement and see the response delay time of the application/website.
* you can also use the scan on Burp Suite tool to detect SQLi.
