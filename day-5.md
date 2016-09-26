#LJ Code 201 - Day 5
The last three days I learned a lot, especially with the` about-me` project, I used pretty much the most important things in HTML and CSS into my project, It took me time trying to find the right layout . also I made my code more -DRY- by refactoring  my Yes and No question into one function that works on array of question

	 function askYesNoQuestion(questionData) {
	   var input = prompt(questionData[0]).toLowerCase();
	   if (input === 'yes' || input === 'y') {
	     correctAnswers++;
	     alert(questionData[1]);
	   } else {
	     alert(questionData[2]);
	   }
	   console.log(name + ' ' + questionData[3] + ' ' + input);
	 }

I also deployed my project by using those commands line on the terminal:
 `git checkout -b gh-pages`
 and then AC process
`git push origin gh-pages`

I like how `background-image` gives me a lot of control over positioning within element
