
#LJ Code 201 - Day 8

The lab assignment wasn't too bad like yesterday, the hardest part was to refactor my code because I have the same exact code in many places.

    var trEl = document.createElement('tr');
    var thEl = document.createElement('th');
    thEl.textContent='Total';
    trEl.appendChild(thEl) 

 I created two functions, the first one creates a tr and appends child into it, and the second one creates a th or td and appends a text into it.


	 function row(child){
	  var element = document.createElement('tr');
	  if(child){
	    element.appendChild(child);
	  }
	  return element;
	}



		function column(child, type){
	  var element = document.createElement(type);
	  if(child){
	    element.textContent = child;
	  }
	  return element;
	}
