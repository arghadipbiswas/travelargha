*{
	margin: 0; padding: 0; box-sizing: border-box;
}
header{
	width: 100%; height: 100vh;
	background-image:linear-gradient(rgba(190, 37, 37, 0.3),rgba(0,0,0,0.1)), url("http://cdn26.us1.fansshare.com/photo/tajmahal/taj-mahal-hd-wallpaper-taj-mahal-1067823786.jpg");                          
	/*background-size: 100% 100%;*/
	background-repeat: no repeat;
	background-size: cover;
}
nav{
	width: 100%; HEIGHT: 15vh;
	background: rgba(0, 0, 0, 0.2);
	color: white; display: flex; justify-content: space-between;
	align-items: center; text-transform: uppercase;
}

nav .logo{
	width: 25%; text-align: center;
}
nav .menu{
	width: 40%;/*background: yellow;*/
	display: flex;justify-content: space-around;

}
nav .menu a {
	width: 25%;
	text-decoration: none; color: white;
	font-weight: bold;

}

main{
	width: 100%; height: 85vh;
	display: flex;
	justify-content: center;
	align-items: center;
	text-align: center; color:  white;
}

section{

}
section h3{
	font-size: 35px; font-weight: 200; letter-spacing: 3px;
	text-shadow: 1px 1px 2px black;
}
section h1{
	margin: 30px 0 20px 0;
	font-size: 55px;
	font-weight: 700;
	text-shadow: 2px 1px 5px black;
	text-transform: uppercase;
}
section p{
	font-size: 25px;
	color: #eee;
	word-spacing: 2px;
	margin-bottom: 25px;
	text-shadow: 1px 1px 1px black;
}
section a{
	padding: 12px 30px;
	border-radius: 4px;
	outline: none;
	text-transform: uppercase;
	font-size: 15px;
	font-weight: 1000;
	text-decoration: none;
	letter-spacing: 1px;
	transition: all .5s ease;
}
section .btnone{
	background: white;
	color: black;
}

.btnone:hover{
	background: #00b894;
	color: white;
}

section .btntwo{
	background: #00b894;
	color: white;
}
.btntwo:hover{
	background: white;
	color: black;
}
