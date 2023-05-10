[HW_2 : Terminal. Format : JSON](https://github.com/Vitaly-chek/JSON)

[HW_2 : Terminal. Format : XML](https://github.com/Vitaly-chek/XML)

[HW_1 : Terminal](https://github.com/Vitaly-chek/Terminal)

[HW_1 : Git](https://github.com/Vitaly-chek/Git)

---

# HW_2 : TXT

1. Create an external repository called TXT;

2. Clone the TXT repository to the local computer - `git clone URL`;

3. Inside the local TXT create a file “new.txt” - `touch new.txt`;

4. Add a file under git - `git add .`;

5. Commit the file - `git commit -m "create new file"`;

6. Push the file to an external GitHub repository - `git push`;

7. Edit the contents of the “new.txt” file - write information about yourself (name, age, number of pets, future desired salary). Write everything in TXT format:

```
Info:
  About me:
          Name - Vitaly;
          Lastname - Krivoruchek;
          Age - 23;
          Pets - 3.
  Work:
      Position - QA Engineer;
      Salary - 600;
      Currency - USD.	
```

8. Push changes to an external repository - `git commit -am "updated file"`;

9. Create file preferences.txt - `touch preferences.txt`;

10. Add information about your preferences (Favorite movie, favorite TV series, favorite food, favorite season, side you would like to visit) to the file preferences.txt in TXT format:

```
Preference:
        Favorite movie - The Wolf of Wall Street;
        Favorite series - The 100;
        Favorite food - Okroshka, Fried potatoe;
        Favorite season - Summer, Autumn;
        Favorite countries - Switzerland, Canada.
```

11. Create a skills.txt file, add information about the skills that were studied on the course in TXT format - `touch skills.txt`:

```
Skills:
        1. Basic theory;
        2. What is client-server architecture;
        3. HTTP Server request methods;
        4. HTTP server response codes;
        5. HTTP request and response structures;
        6. What is JSON, XML. Their structure;
        7. API testing via Postman (JS, API autotests);
        8. Removing and reading logs from an external server;
        9. Sniffing http web traffic via Charles and Fiddler;
        10. Dev Tools of web browsers (Google Chrome, FireFox);
        11. VPN. (How it works, why you need it, how to use it, tool options);
        12. Mobile testing;
        13. iOS feature, android, guidelines;
        14. Building iOS apps with XCode;
        15. Building Android apps with Android Studio;
        16. ADB (android device management);
        17. Proxy and vpn setup on iOS and Android;
        18. Interception (sniffing) mobile traffic via Charles and Fiddler on iOS and Android;
        19. Linux command line (terminal) (copy, create, view, move files on non-GUI servers);
        20. Basic bash scripting, automation of routine tasks on the server;
        21. Access to remote servers;
        22. SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join);
        23. Postgres database (installation, configuration and use);
        24. Redis non-relational database (installation, configuration and use);
        25. Load testing in Jmeter;
        26. Scrum development methodology.
```

12. Make a commit in one line - `git add . && git commit -m "new 2 files"`;

13. Send 2 files at once to an external repository - `git push`;

14. On the web interface, create a file bug_report.txt;

15. Make Commit changes (save) changes on the web interface;

16. Modify the bug_report.txt file on the web interface, add a bug report in TXT format:

```
Bug report:
        Project - Notes;
        Version - 1.3;
        Id - №5;
        Summary - When clicking on the 'A to Z' filtering button on the main page of the application, chaotic filtering of lists occurs;
        Step to reproduce:
                1. Open the 'Notes' app;
                2. Create 15 lists that will start accordingly (A, a, D, 3, :, U, u, Ш, ш, 5, @, Ї, ї, -, d);
                3. On the main page of the application, click on the filter button 'A to Z';
        Actual_result - Lists are sorted randomly;
        Expected_result: 
                1. The lists are sorted in order: symbols, numbers, Latin letters (upper case first), Cyrillic letters (upper case first);
                2. Correct order: (-, :, @, 3, 5, А, а, D, d, U, u, Ї, ї, Ш, ш).
        Severity - Minor;
        Priority - Normal;
        Status - New;
        Environment - IPhone 7 Plus, version 15.4.1;
        Autho - Vitaly;
        Assignee - Ivan.
```

17. Make Commit changes (save) changes on the web interface;

18. Synchronize external and local TXT repository - `git pull`.
