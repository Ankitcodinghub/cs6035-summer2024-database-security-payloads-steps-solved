# cs6035-summer2024-database-security-payloads-steps-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs6035-summer2024-database-security-payloads-steps-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123362&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6035 summer2024 database security payloads steps Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<h4><a href="https://www.ankitcodinghub.com/product/cs6035-database-security-spring-2025-solved/"><span style="color: #ff0000;"><strong>2025 SOLUTION LINK click here!!</strong></span></a></h4>
<h4><a href="https://www.ankitcodinghub.com/product/cs605-database-security-marks-above-60-solved/"><strong><span style="color: #ff0000;">2024 FALLSOLUTION <span style="color: #3366ff;">LINK</span></span></strong></a></h4>
<strong>Task 0: GTID Verification (flag0 – 5 pts)</strong>

<strong>*NOTE – Task 0 has 1 flag (flag0)</strong>

This task will set up the rest of the project, which is why we are offering five free points – like where you got bonus points in kindergarten for putting your name (and spelling it right) on a test.

Note that you&nbsp;<strong>**only have twenty-five attempts</strong>&nbsp;at entering your correct GTID, at which point you will be locked out and have to restore your VM.

To earn your hash for flag0, you must perform the following actions.

<ol>
<li>Click on the Task 0 Menu from the home page. The page will open in a new tab.</li>
</ol>
<ol>
<li>Enter your GTID and click Submit</li>
</ol>
<strong>Where do I find my GTID?</strong>

<ol>
<li style="list-style-type: none;">
<ul>
<li>Please see the&nbsp;<a href="https://github.gatech.edu/pages/cs6035-tools/cs6035-tools.github.io/RequiredReading">Required Reading</a>&nbsp;page for instructions to retrieve your GTID.</li>
</ul>
</li>
</ol>
Hints:

<ul>
<li>After obtaining your hash, add your flag0 hash into the JSON file and submit it to Gradescope to verify it is correct before proceeding to Tasks 1-4!</li>
<li>While this means you will “burn” a submission, it is HIGHLY recommended as the wrong setup means all flags will generate incorrectly!</li>
</ul>
Include your flag0 hash into the JSON file, and now, onto Task 1!

&nbsp;

<strong>TASK 1: INFERENCE ATTACK- #1 (flag1 – 20 pts)</strong>

<strong>**NOTE – Task 2 has an array flag</strong>

<strong>Your first two attacks will involve what is called an inference attack. This is not an actual hack against a system, and it often doesn’t involve hackers at all. Data security is about keeping data confidential on a need-to-know basis, and most data at most companies is secured by permissions that limit who can see data. These permissions can be at the level of the table (the full list of a particular type of data, for instance the employee table contains the basic data about employees), the level of a row (a row in this case would correspond to the record for a single employee), or the level of a column (in this case a piece of information about an employee, like gender or position at work). However, it takes thought and care to maintain these controls, and often they can be inadvertently and carelessly circumvented. An inference attack usually involves access to standard reports available to a wide range of employees. Consider the sensitive area of salary. A company might consider that a column to restrict in terms of access and might well make an employee roster report that anyone could view that does not list people’s salaries. However, there may be other standard reports a company uses that are not carefully designed to protect those controls. By using two or more reports together, a rank-and-file employee can discover salary details they are not supposed to know by combining the information on the two reports and inferring the missing data, thus the name “inference attack”. You use multiple data sets to learn information that you are not supposed to know.</strong>

<strong>This is what has happened with these first reports you are looking at that were provided to you for testing. You have been given internal reports for a single company. One report is a simple employee roster, one report lists out how long employees have been members of the organization, one report groups data on all employees together to provide the average salary for employees based upon the state that they live in, and the final report lists the average salary for employees based upon how long they have been a part of the company. Individually, these four reports do not violate the controls that the client has placed on access to sensitive HR data. However, as you do your analysis, you realize that there has been a hole opened in those controls to someone who puts the reports together and does a little analysis of the contents of the reports.</strong>

<strong>The audit reveals to start that at minimum at least one person’s salary is publicly available to all employees that can run these four reports. To successfully complete task 1, you need to find a hole in the protection where you can definitively find the actual salary of employees. After finding the first employee, continue looking for a hole in the protection to find the next employee whose salary you can definitively find. Continue this for 4 employees. Each employee will have a hash associated with them. This hash is unique to your VM and was generated when you completed task 0. Once you have identified which employees have the exposed salary, record the hash value displayed for that employee on the report with their salary (2 decimal places) in your JSON file for flags1. You will pass task 1 if you have the correct hash values. Remember that you only get 20 submissions for the entire project, so if you randomly try different hash codes, you will only hurt yourself later in the project.</strong>

<strong>For Task 1 – order matters (order of finding) for the flags (array0 is the first employee found, array1 is the second employee found, etc.)!</strong>

<strong>To earn your hash for flag1, you must perform the following actions.</strong>

<ol>
<li><strong>Hover over the Task 1 Menu, which will display four reports: Employee, Duration, Salary by State, and Salary by Duration.</strong></li>
</ol>
<ol>
<li><strong>Click on the report you want to view (i.e., Employee Report). The report will open in a new tab.</strong></li>
<li><strong>Review the data on all four reports. You are searching through the data to see if you can find at least one employee whose salary you can positively identify exactly.</strong></li>
<li><strong>Once you have found an employee whose salary you know exactly, look at the left of their record on the employee report. In the ID column of the report, there will be a hash (ID) for them. Record this hash and enter it into your JSON file in array0. NOTE: the hashes are generated in connection with your GTID so they will be unique to you and your account. You will need to append to this hash a _ followed by the salary (2 decimal places) of the employee (you may need to do some math).</strong></li>
<li><strong>With one employee found and hence eliminated, is there another employee whose salary you know exactly? Repeat steps 2-4 until no further elimination is possible. Each employee found should be added to the next array pointer in the flag (i.e., employee found order – 1 =&gt; array1 for the second employee found).</strong></li>
</ol>
<strong>Hints:</strong>

<ul>
<li><strong>You need to find a place where data is isolated to a single person. Look throughout the four reports to see if there is anything that makes the data unique at an individual level. You might need to combine multiple reports to do this.</strong></li>
<li><strong>Once you isolate an employee, continue to see if you can isolate another employee. Rinse and repeat until you can no longer isolate an employee.</strong></li>
<li><strong>If it looks like a table and acts like a table, it is probably a table. While this is not necessary to complete the task, you can copy data from the report(s) into a spreadsheet program to manipulate it. This may assist you in tracking down the hole that exposes salaries.</strong></li>
</ul>
<strong>Include your flag1 array consisting of hashes_salaries into the JSON file, and now, onto Task 2!</strong>

<strong>&nbsp;</strong>

<strong>TASK 2: INFERENCE ATTACK- #2 (flag2 – 30 pts)</strong>

<strong>**NOTE – Task 2 has an array flag</strong>

Now that you have seen how an inference attack can compromise data in a single company, we next consider how inference attacks can be used to compromise data by combining unrelated data sets.

For this attack, consider four completely unrelated data sources. All four are internet facing and therefore available to anyone with internet access. The first report is a sample report produced for a local hospital concerning types of procedures done within the last few years. The second report is a voter registration database, which has certain well-established fields in it (you could go to your local board of elections and get a report like this on all registered voters in your district most likely). The third report is a partially de-identified report for an insurance company for a sample data set for public use built by the same developers we have been dealing with. “Partially de-identified” means that though there were some attempts made to remove an obvious link to actual patients, there is still some data left on the report that might link back to a real person if looked at carefully. We also have provided a helpful list of medical codes to link to the hospital report.

The problem here comes from the incomplete deidentification of the data in the insurance company’s claim report. Because of this, it may be possible to join these four sources together somehow to find a specific person’s medical history to know that on a specific date, a specific person had a specific procedure done. This is of course a significant breach of HIPAA regulations (in fact, this exercise was inspired by the incident where the medical history of the governor of Massachusetts was made public in just such a fashion). Your objective in this inference attack is to find specific persons who had a procedure that you can link by name and identity to a specific attack in the medical data using all four data sources. You may want to look up the work done on the patient using the codes in the medical history on the medical codes list, which might be helpful in the process. You will find a hash next to each person in the voter report. Select the correct hash as your response to this task by listing the hash in your JSON file for flag2. Just as in Task 1, start by isolating the data, then after that isolation, see if you can isolate down to individuals using the data available and logic. You will pass task 2 if you have the correct hash values. Remember that you only get 20 submissions for the entire project, so if you randomly try different hash codes, you will only hurt yourself later in the project.

<strong>For Task 2 – order does not matters (order of finding) for the flags!</strong>

To earn your hash for flags2, you must perform the following actions.

<ol>
<li>Hover over the Task 2 Menu, which will display four sites: Medical History, Voter Registration, Insurance Claims, and Medical Codes.</li>
</ol>
<ol>
<li>Click on the site you want to view (i.e., Medical History). The site will open in a new tab.</li>
<li>You will need to carefully examine all four sources to see where a patient’s history got compromised. It will be up to you to determine how to do this.</li>
<li>Once you have identified the exposed patient, look up the hash code (ID Column) on the voter registration report for the exposed patient and record it. NOTE: the hashes are specific to you and your GTID as provided in task 0 (and we will use that ID when we grade in Gradescope).You will need to append to this hash a _ followed by the cpt (procedure *not diagnosis) code of the voter.</li>
</ol>
Hints:

<ul>
<li>As with the prior task, feel free to make liberal use of copying data from the VM into a spreadsheet or other similar program on your host, and feel free to do whatever analysis you need to do to figure out the record you seek. As in Task 1, this is not required to complete this task.</li>
<li>unlike Task1 where the data can be more easily narrowed to one record, here you will need to narrow to multiple records to then use logic to narrow to one record. Unlike Task 1 where the order matters to narrow down the data, the order does not matter here as it is logic based instead!</li>
<li>Once you isolate a voter, continue to see if you can isolate another voter. Rinse and repeat until you can no longer isolate a voter.</li>
<li>Sometimes there is no perfect join of data and logic needs to be incorporated,</li>
</ul>
Include your flag2 array consisting of hashes_cptcodes into the JSON file, and now, onto Task 3!

TASK 3: SQL INJECTION – #1 (flag3 – 5 pts / flag4 – 10 pts / flag5 – 10 pts)

*NOTE – Task 3 has 3 flags (flag3, flag4, flag5)

&nbsp;

The next two tasks involve the most common database attack – SQL injection. This attack is one of the most common information security attacks in the world, and yet it is also one of the easiest to mitigate (in other words, lazy or careless programming is what causes this attack to be possible). SQL injection is possible when inputs are not sanitized. That sounds complicated, but what that means simply is that when you give someone a form or a web page to enter data, and there are slots for a user to type in, as a programmer you are responsible to ensure that somewhere in the process those input fields are inspected and any bad input is sanitized. SQL injection happens when the contents of the input fields without data sanitization are used in a text string to create a database query and sent to the database server in a form the developer did not intend.

&nbsp;

To get into the basics of SQL injection, you can start by looking up online “SQL Injection Cheat Sheet” which is a helpful introduction to the topic. But what you will need to do to accomplish this task is figure out how to write some basic SQL code (the complexity won’t be in the SQL code, but in the bypass of the SQL Injection security) that can be placed into the input field of a form and passed to the website in such a way that it is a valid SQL statement that does things that the original developer did not intend. This can be as simple as simply bypassing security, collecting information you should not have, or at worst you will be making actual changes to the data of the website that the website owners do not want at all. Once the hole exists, your power to exploit it can be immense as long as you can guess the structure of the underlying database, or to map it out.

&nbsp;

For Task 3, you have a website where your user ID is your GTID, as you entered on Task 0. The site wants to upgrade its old Legacy Login page. The legacy page’s main security is done by checking to see if there is a direct match to a user by the username (your GTID). You do not know and will not receive the password to enter the system. For flag3, the developers are asking you to determine the difficulty in bypassing the existing security, knowing that a SQL Injection attack is possible. The developers want to make an attempt to mitigate the risk of such an attack; however, they are wondering if they should be using just client-side data sanitization or both client and server-side data sanitization, with the server-side and client-side data sanitization being the same. For flag4, you will attempt to bypass the security using client-side data sanitization. For flag5, you will attempt to bypass the security using both client and server-side data sanitization. The client provided a snippet of the code they used on the legacy login page. You can use this code to try and figure out how to perform the SQL injection. When you succeed, you will log into the website using your GT ID and no password. The injection will bypass the password requirements and log you in immediately. Once logged in, the hash for flags3-5 keyed to your GT ID will be displayed. All three hashes for Task 3 will be different.

&nbsp;

To earn your hash for flags3-5, you must perform the following actions.

&nbsp;

Hover over the Task 3 Menu, which will display three links: Legacy Login, New Login – Option 1, New Login – Option 2. \

alt_text

&nbsp;

Click on a link. The page will open in a new tab.

&nbsp;

<ol>
<li>For flag3 (Legacy Login) – this is a straight SQL Injection on the password field.</li>
</ol>
&nbsp;

<ol>
<li>For flag4 (New Login – Option 1) – this is a client-side data sanitization SQL Injection on the password field.</li>
</ol>
&nbsp;

<ol>
<li>For flag5 (New Login – Option 2) – this is both a client and server-side data sanitization (2x) SQL Injection of the password field.</li>
</ol>
&nbsp;

Enter in your GTID in the username input field and any additional characters in the password input field you determine will cause the injection. Then press the login button to submit.

&nbsp;

Where do I find my GTID?

&nbsp;

Please see the Required Reading page for instructions to retrieve your GTID.

If your information is correct, you will log into the system and receive your hash.

&nbsp;

Hints:

&nbsp;

For flag4 and flag5, you should use the browser’s Developer Tools to access and debug the client-side code.

For flag5, remember that there will be server-side data sanitization, that you do not have access to, but know the logic will be a duplicate of the client-side data sanitization.

There is difference between encoding, escaping, and sanitization. Understand the difference and the validity of using one or the other, remembering that the client/server-side code is doing sanitization.

&nbsp;

Here is the login code that you were able to obtain from the legacy login page (both username and password have a character limit of 96):

function login($username, $password) {

$sql = “SELECT username, password, hash, count(*) cnt INTO #tmp_user FROM users WHERE username=’$username'”;

$usercheck = $this-&gt;db-&gt;query($sql)-&gt;execute()-&gt;fetch();

if ($usercheck[‘cnt’] != 1) {

return false;

} else {

$sql = “SELECT hash FROM #tmp_user WHERE password=’$password'”;

$userdata = $this-&gt;db-&gt;query($sql)-&gt;next();

if ($userdata) {

return true;

} else {

return false;

}

}

}

&nbsp;

Include your flags3-5 hashes into the JSON file, and now, onto Task 4!

<strong>TASK 4: SQL INJECTION – #2 (flag6 – 10 pts / flag 7 – 5 pts EXTRA CREDIT)</strong>

<strong>*NOTE – Task 4 has 2 flags (flag6, flag7)</strong>

For this task, you will be trying two tasks. One is required to get full credit for this project, one is much harder and therefore will be considered extra credit. We strongly recommend you wait until completing task 5 before trying the extra credit task as some knowledge from task 5 will be needed to complete the extra credit.

Both tasks will use the same banking website. This is a standard type of banking site where you will log in and see the history of a particular account tied to the login. This is another site that your client maintains and they want you to verify the protection they have set up. Your job is to show them that the protection is not adequate.

<strong>*Part one (flag6): logging into a website as a user without a username</strong>

This first part is the part you must complete in order to get full credit for the project (i.e. 100/100). Your task for this portion is to log into the website without knowing any actual accounts. However, you must actually log in as a valid user. You therefore must craft an injection that is smart enough to collect a valid user from the database without having any actual access to the database (see the hints section below for assistance in knowing what the database structure looks like). You must use the skills you gained in Task 3 with some more sophisticated SQL knowledge. There are multiple injections for the username field that will work, your goal is just to ensure that the username is populated from an actual row within the database using your injection. You will need two different injections for the two fields (username and password) in order to log in. Once you have logged in successfully, you will see a valid username where the username text box was and a hash just below the username. This hash is your answer for flag6.

<strong>*Part two (flag7, extra credit): altering transaction history</strong>

The developers want to verify the strength of their protection for the transaction history for the account. Once you complete flag6 and log in, you will see a list of 10 transactions over time. You will notice that one of the 10 transactions is an overdraft charge of $35. You’ll also notice that there is a balance to the account when you bring it up of $1746.52. You need to do two things to test the transaction history and get your extra credit flag. You must get the balance to a total of $2000 with a total of 10 transactions. To do this, you need to do a transfer of money into the account and you will need to delete one of the transactions (for this test the developers want to see if you can remove an unwanted overdraft amount, so you’ll need to remove that specific transaction while adding enough money to make the balance $2000).

Unlike prior injections, this task cannot be performed by attacking the text boxes. You will instead need to alter the output of the actual form within the web browser. This will require you to use the Chrome Developer Tools within the browser. This will probably require you to do some research in how to use these tools to make breakpoints and alter the contents of data as found in a form (which is why this is extra credit). This is what you need to know to fill out the Transfer form when you click on the Transfer button. The routing number and account number fields for this do not matter, feel free to enter any values. You will not be able to alter the account number. You should enter the amount you need to get to $2000 as if the overdraft fee was not there (if you do the injection correctly that transaction will completely disappear and therefore not be used to calculate the balance). If you have the breakpoint set in the correct place, you can stop form execution and actually use the Developer Tools to alter the data within the form to include your SQL injection.

When you have done this correctly, the proper hash will appear below the balance as the value associated with “Validation”. Unlike all other tasks, be warned – there will always be a hash there and its value will change. You therefore can receive an incorrect hash. The hash will ONLY be correct if the balance is $2000 and the number of transactions is 10, with no overdraft fees. Do not try to submit this to Gradescope unless you have no overdraft fee, 10 transactions, and $2000 balance – whatever hash you may have outside of those conditions will not be correct.

Be warned – banking sites use auditing to track history. It won’t be enough simply to delete the transaction. You will have to also remove it from the audit trail. Make sure to look at the hints for an idea how to find this information. The developers won’t give you any credit for your efforts unless you can remove all trace of the deleted transaction.

To start task 4, click on the Task 4 Menu from the home page. The page will open in a new tab.

The text boxes you need to inject into are on the top right.

Required Task Hints:

<ul>
<li>Task 4 uses a query similar to Task 3 to perform the login. If you need to find help in knowing how to query database information to find a username, that query will give you valid metadata information.</li>
<li>The developers have not set up any filtering or logic to change what you enter into the field, just like it was for your legacy task in Task 3. You don’t need to worry about changing any of your injections to bypass a filter.</li>
</ul>
Extra Credit Hints:

<ul>
<li>If you make a mistake in adding a transfer item, you will need to log out and back in. Logging out and back in will reset the transactions to the original amount. You must do your injection in a single click of the Transfer button, and not with multiple clicks.</li>
<li>You will need information hidden in the website to craft your injection. The information is hidden in webpages you cannot reach via any links anywhere in our project. This is why you need to do task 5 first before doing the extra credit, because you will learn how to find this information within the website. This hidden information will show you schema of the transactions and the audit trail. Look closely at the URLs in Task 5 as you did to complete that task, and experiment with what you might need to get a valid URL without a hyperlink.</li>
<li>There are two main ways to insert a row into a table via SQL (ex. below). You will need to figure out which is used to craft your injection!
<ul>
<li>INSERT INTO TABLE (COL1, COL2, …, COLn) VALUES(DATA1, DATA2, …, DATAn)</li>
<li>INSERT INTO TABLE (COL1, COL2, …, COLn) SELECT DATA1, DATA2, …, DATAn FROM …</li>
</ul>
</li>
<li>Chrome Developer Tools can be very concerned about your security and may block you from doing things like pasting data into a variable. If you encounter this, go to the section where warnings are displayed. You may find that Chrome is blocking you and you must take an action to unblock it. This will be necessary to complete your task, assuming you copy and paste the data into the variable (and you definitely will want to do it that way).</li>
</ul>
Include your flag6 and flag7 hash into the JSON file and submit it to Gradescope!

<strong>TASK 5: SQL INJECTION – #2 (flag8 – 10 pts)</strong>

<strong>*NOTE – Task 5 has 1 flag (flag8)</strong>

In this case, you will be looking at a search engine for a database of music albums for a music store. You have discovered that there is a page called “schema” which offers the user a view of the underlying metadata of the table used to populate the main report. By now, if you have been paying attention, the designers of these sites have followed a similar pattern for how their sites work, especially if you look at the hyperlinks that lead to the pages. You know therefore that there is probably a way to get admin access to that schema leveraging that knowledge of how they use links. And that means that there might be table definitions available to users who poke around and try to find things that they should not.

So your task then is first to figure out if you can find any additional information about tables in the database, and second to figure out how to leverage the information you find in the context of a SQL injection. If you are successful in crafting a SQL injection, you will find an actual database account appear on the report that you can use to log into the system using the “Login” screen on task 5. If you have the correct login information you can only obtain by SQL injection, you can enter the login information into that screen and get access to the management console. Of course, for our purposes “management console” is just the hash you need to get credit for the attack. Once the hash appears on the screen, you can enter it into your JSON file.

To earn your hash for flag8, you must perform the following actions.

<ol>
<li>Hover over the Task 5 Menu, which will display four links: Schema, Report, and Login.</li>
</ol>
<ol>
<li>Click on the link you want to view (i.e., Schema). The link will open in a new tab.</li>
<li>You can use the Schema link to see the schema for the table that is used to build the report. Consider based upon how the links have been designed to this point how you might be able to find out more information than this table. You might need admin access to see information.</li>
<li>Once you have found additional information, consider how you might be able to use it on the report page for a SQL injection.</li>
<li>The report search is a simple “SELECT…..FROM….WHERE” type of query using the schema you can see on the initial schema screen. Based on your previous testing, this probably means you can type in a search that will return rows from other tables in the database than intended. Once you have figured out how to execute the injection, type in your attack into the search field and click “Search”.</li>
<li>Once you have done the injection correctly, you will find a username and a password appear in the report data. Use these values to log into the management console on the “Login” screen. When you have the correct login, you will get into the system and your hash will be displayed. Record the hash into your JSON file and submit to Gradescope.</li>
</ol>
Hints:

<ul>
<li>You notice that the pages and urls for the different clients look very similar, with similar structure and conventions.</li>
<li>How can you add contents from another table to an existing SQL query to return one set of data in a report?</li>
<li>You have heard that this company has realized that client-side scripting is easily bypassable and offers a template for the server-side scripting and have started to remove the clien-side sanitization login. However, you are EXTREMELY confident that they are still using the same server-side sanitization logic/code they have previously used for other sites.</li>
<li>There is difference between encoding, escaping, and sanitization. Understand the difference and the validity of using one or the other, remembering that there is no client-side and only server-side sanitization.</li>
<li>Null works great for a SQLi when you don’t know the schema, and when the developers aren’t expecting it. The developers are looking for it!</li>
<li>The login bypass logic you used from Task 3/4 will not work on Task 5, although the choice to attempt is up to you. We explicitly prevented SQL injection on the login screen for this exercise.</li>
</ul>
Include your flag8 hash into the JSON file and submit it to Gradescope!

&nbsp;
