# LJ Code 201 - Day 1

My first day in Code Fellows was great, I met my classmates and my instructor who was doing a great job explaining in detail each part of the course. I was surprised by vocabulary, i found myself often looking up words that other classmates knew. But I like the challenge and it's just the first day, i'm sure my technical english vocabulary will improve quickly in this course. I'm also finding that it's good practice to write in the journal everyday.

I have learned abut the Git which is a version control system that allows you to save and back up your work, it also lets you share code and collaborate with developers on different projects.

I created two separate repositories and cloned them with the command :
git clone <Web URL>


Learned about the ACP process which are the three important commands on Git: add, commit, push

#### I used some shortcuts:
* command +t to open a new tab
* command +k to clear the terminal
* command +tab to switch app
* Option +command +I or J to open the developer tools

#### Developer Tools
The developer tools were a very interesting thing to discover because it helps you with debugging your code.

#### Terminal Commands
I practiced some commands in Terminal:
`pwd` ,`cd` , `ls` , `rm` , `mv`, `sudo` , `man` , `date` , `cal`, `atom`.

#### Absolute vs Relative Paths
Found out about the difference between absolute and relative path.

#### In class
It was excellent practice using what we learned on a project and then later expanding on the project to learn a bit more.

I implemented validation of user input when prompting for age. I found out that the prompt always returns a string no matter what the user inputs, so i used parseInt which lets you convert a string into a number and if it can't convert the string to a number it returns "NaN". I couldn't get by with only using parseInt alone, I used the isNaN function to check if the returned value of parseInt is a number or "NaN".

- resource : <http://stackoverflow.com/questions/17907455/how-to-get-numeric-value-from-a-prompt-box>

Here is the code:

		 <!DOCTYPE html>
		 <html lang="en">

		<head>
		  <meta charset="UTF-8">
		  <title>Class demo 19 sept</title>
		  <style>

		    body{
		      text-align: center;
		      color:gray;
		    }
		  </style>
		</head>

		<body>
		  <h1>Tell me about yourself</h1>
		  <p>What is your name?</p>
		  <p>how old are you?</p>
		  <p>what's your favorite hobby?</p>
		  <p>what's your favorite place?</p>
		  <script>
		    var name = prompt("what is your name?");
		    console.log('The user\'s name is ' + name);
		    var age = prompt('How old are you?');
		      while(isNaN(parseInt(age))){
		        age = prompt('How old are you?');
		      }
		    console.log('The user\'s age is ' + age);
		    var hobby = prompt('What is your hobby?');
		    console.log('The user\'s hobby is  ' + hobby);
		    var place = prompt('what is your favorite place so far?');
		    console.log('the user\'s favorite place is :' +place)
		    alert('Im'+ ' '+ name + ',' + ' '+ age  + ' ' + 'years old '+ 'I like '+ hobby + ' ' + 'my favorite place is ' +place);
		  </script>

		</body>
		</html>
