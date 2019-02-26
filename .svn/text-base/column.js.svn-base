// script by Paul Bellows

function setTall() {
	if (document.getElementById) {
// read the height of each div element
		var contentHeight = document.getElementById('maincontent');
		var leftHeight = document.getElementById('leftnavbar');
// see if the content div is the tallest and set the style.height of the other two accordingly
		if (contentHeight.offsetHeight >= leftHeight.offsetHeight) {
			leftHeight.style.height = (contentHeight.offsetHeight - 20) + 'px';
			}
		}
	}
window.onload = function() {
	setTall();
}

window.onresize = function() {
	setTall();
}