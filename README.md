# alura56
header {
	background: #BBBBBB;
	padding: 20px 0;
}

.caixa {
	position: relative;
	width: 940px;
	margin: 0 auto;
}

nav {
	position: absolute;
	top: 110px;
	right: 0;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

nav a {
	text-transform: uppercase;
	color: #000000;
	font-weight: bold;
	font-size: 22px;
	text-decoration: none;
}

nav a:hover {
	color: #C78C19;
	text-decoration: underline;
}

.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1.5%;
	padding: 30px 20px;
	box-sizing: border-box;
	border: 2px solid #000000;
	border-radius: 10px;
}

.produtos li:hover {
	border-color: #C78C19;
}

.produtos li:active {
	border-color: #088C19;	
}

.produtos li:hover h2 {
	font-size: 34px;
}

.produtos h2 {
	font-size: 30px;
	font-weight: bold;
}

.produto-descricao {
	font-size: 18px;
}

.produto-preco {
	font-size: 22px;
	font-weight: bold;
	margin-top: 10px;
}

footer {
	text-align: center;
	background: url("bg.jpg");
	padding: 40px 0;
}

.copyright {
	color: #FFFFFF;
	font-size: 13px;
	margin: 20px 0 0;
}
