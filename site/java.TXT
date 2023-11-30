// JavaScript Document
function page(stor) {
if (stor == 'stor1') {
	document.getElementById('stor1').style.display = 'block';
	document.getElementById('stor2').style.display = 'none';
	document.getElementById('stor3').style.display = 'none';
	document.getElementById('stor4').style.display = 'none';
	document.getElementById('stor5').style.display = 'none';
	}
if (stor == 'stor2') {
	document.getElementById('stor1').style.display = 'none';
	document.getElementById('stor2').style.display = 'block';
	document.getElementById('stor3').style.display = 'none';
	document.getElementById('stor4').style.display = 'none';
	document.getElementById('stor5').style.display = 'none';
	}
if (stor == 'stor3') {
	document.getElementById('stor1').style.display = 'none';
	document.getElementById('stor2').style.display = 'none';
	document.getElementById('stor3').style.display = 'block';
	document.getElementById('stor4').style.display = 'none';
	document.getElementById('stor5').style.display = 'none';
	}
if (stor == 'stor4') {
	document.getElementById('stor1').style.display = 'none';
	document.getElementById('stor2').style.display = 'none';
	document.getElementById('stor3').style.display = 'none';
	document.getElementById('stor4').style.display = 'block';
	document.getElementById('stor5').style.display = 'none';
	}
if (stor == 'stor5') {
	document.getElementById('stor1').style.display = 'none';
	document.getElementById('stor2').style.display = 'none';
	document.getElementById('stor3').style.display = 'none';
	document.getElementById('stor4').style.display = 'none';
	document.getElementById('stor5').style.display = 'block';
	}
}