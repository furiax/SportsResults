<h1>Sport Results Notifier</h1>

<h2> How to use</h2>
This is an automated service app that will scrape sport results and then email these results once per day on a fixed time.<br>
<br>
Setup:<br>
- In Mail.cs provide the from email address, the password and the to emailaddress. <br>
- In SportResultService.cs, in the sendTime field, give in the time you wish the mail will be sent daily.<br>
<br>
That's it !<br><br>
Keep the program running and as long as it runs it will scrape the data and send out an email with the latest NBA results each day on the desired time.<br>

<br>
<br><hr>
This application is a part of the www.thecsharpacademy.com roadmap.<br>
Goal of the website is to become a (better) C# and .Net developper.<br>
<br>
<h2>About the project:</h2>
This application gets sport results (NBA games) from a website and then send these results to the user trough mail.<br>
<br>
<h2>Requirements:</h2>
- Build an application that scrapes data using the Agility Pack Library.<br>
- Create a mail function that emails this data to a user using SMPT.<br>
- The data should be scrapped only once per day and send to a specific emailadress.<br>
- This should be a service that runs automatically without interaction.<br>
<br>
<h2>Lessons learned:</h2>
- Learned how to harvest data from a non-Api source.<br>
- Learned how to compose and send emails with SMPT.<br>
- Had to search for a way to automate the process so no user interaction is necessary <br>
<br>
<h2>Resources used:</h2>
- The documentation at the assignment page and the discord channel of www.thecsharpacademy.com <br>
- Various google and youtube pages.<br>
