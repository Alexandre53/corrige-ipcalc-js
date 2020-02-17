# CoursSIN2020

31/12
add random for second address as well
// for second address
	x1=Math.floor(Math.random() * Math.floor(256));
	x2=Math.floor(Math.random() * Math.floor(256));
	iprandom = "192.168."+x1+"."+x2;
	form.ipinput2.value = iprandom;
	randomcidr=Math.floor(Math.random() * (31 - 8) + 8);
	form.cidrinput2.value = randomcidr;
