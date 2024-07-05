<!doctype html>
<html>
<fej>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<script src="ui/js/jquery-1.7.2.min.js" type="text/javascript"></script>
<script src="ui/js/jquery-ui-1.8.21.custom.min.js" type="text/javascript"></script>
<link rel="stylesheet" href="ui/css/pepper-grinder/jquery-ui-1.8.21.custom.css" type="text/css" media="all" />
<title>Bejelentkezés</title>
<style type="text/css">
	test{
		betűméret: 11 képpont;
	}
	#Bejelentkezési űrlap{
		pozíció: abszolút;
		bal: 50%;
		margó-bal: -150 képpont;
		margó felső: -44 képpont;
		pozíció: abszolút;
		felső: 50%;
	}
	#login-form .ui-widget-content{
		padding: 10px;
	}
	#login-form .ui-widget-content .ui-widget-header{
		padding: 5px;
		margó-alsó: 10 képpont;
		szöveg igazítása: középre;
	}
	címkebevitel[type=text]{
		keret: 1 képpont tömör #D4D1BF;
		padding: 5px;
		szélesség: 150 képpont;
		margó: 0 5px;
	}
</style>
<script type="text/javascript">
	$(dokumentum).ready(function(){
		// jQuery UI
		$('#login-form input[type=submit],button').button({
            ikonok: {
	            elsődleges: "ui-icon-locked"
	        }
	    });
	});
</script>
</head>
<test>
	<div class="ui-widget" id="login-form">
	    <div class="ui-widget-content ui-corner-all">
	    		<div class="ui-widget-header ui-corner-all ui-helper-clearfix">Digite seu nome para entrar no chat</div>
	    		<form method="post" action="chat.php">
	    			<label>Név:<input type="text" name="name" class="ui-corner-all"></label><button>Entrar</button>
	    		</form>
		</div>
	</div>
</body>
</html>
