  // START: trim whitespace from input fields
	const inputField = document.querySelector('.trimwhitespace');
	inputField.addEventListener('keydown', function(event) {
		if (event.keyCode === 32) {
			event.preventDefault();
		}
	});
  // END: trim whitespace from input fields


// START: Inline trim whitespace from input fields
function removeSpaces(string) {
  return string.trim();
}
 
//html 
<input type="text" onblur="this.value=removeSpaces(this.value);"> 
// START: Inline trim whitespace from input fields
  
