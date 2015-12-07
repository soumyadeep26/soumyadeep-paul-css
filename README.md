
body{
	background-color:black;
	background-image:url();
}
::selection{
	background: #3776ab;
    color: #fff;
    text-shadow: none;
}
#social{
		position:absolute;
		top:450px;
		left:25px;
		background-color:grey;
		border:2px groove rgba(100,50,255,1);
		padding:5px;
		opacity:0.35;
		box-shadow:0 0 50px rgba(240,128,240,1);
}
#social:hover{
		opacity:1;
		transform: translate(5px,10px);
}
#linkedin,#github{
 	height:30px;
 }
#twitter,#google,#linkedin,#github{
	margin-left:15px;
}
#twitter{
	position:relative;
	bottom:5px;
}
#my-name{
	font-family: 'lato',sans-serif;
	color:rgba(255,255,255,1);
	font-size:70px;
	text-shadow:3px 5px 0px  grey, ;
	position:absolute;
	top:200px;
}
#intro{
	height:50px;
	position:absolute;
	left:60%;
	top:30%;
	color:#BE3434;
	/*font-family:'open sans',sans-serif; */
	font-family: 'Merienda One', cursive; 
	font-size:25px;
	background-color:rgb(65,0,0);
	padding:30px;
	box-shadow:10px 10px #E3BD32,0 0 50px brown;
	text-shadow:1px 1px  orange;
	overflow:hidden;
	opacity:0.75;
}
#intro:hover{
	height:380px; 
	opacity:1;
}
