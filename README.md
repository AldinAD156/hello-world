!--trying repository--!

<!DOCTYPE html>
<html>
<head>
  <title>Bootstrap Example</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="styleid.css" />
  
</head>
<body>
<div id="sola">
	<nav class="navbar navbar-expand navbar-dark bg-dark">
		<div class="dropdown">
			<button class="navbar-toggler-icon fixed" data-toggle="dropdown" id="#solaNavbar" aria-haspopup="true" aria-expanded="false"></button>
			<a href="../notepad/solaid.html" class="btn btn-dark"><i class="fa fa-home fa-2x"></i></a>
				<div class="dropdown-menu" aria-labelledby="solaNavbar">
					<a href="../notepad/zurueckid.html" class="dropdown-item"><i class="fa fa-qrcode"></i>Scan</a>
						<div class="dropdown-divider"></div>
					<a href="../notepad/fehlerid.html" class="dropdown-item"><i class="fa fa-info"></i>Fehler Melden</a>
				</div>
        </div>
	
	<div class="dropdown dropleft float-right ml-auto">
		<button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">
		User
		</button>
			<div class="dropdown-menu">
				<a class="dropdown-item" href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Logout</a>
				<div class="dropdown-divider"></div>
				<a class="dropdown-item" href="#"><i class="fa fa-question" aria-hidden="true"></i>Fehler melden</a>
			</div>
	</div>
  
	</nav>
	
	<div class="container-fluid"><br>
		
		<h1>Home</h1><br>
		
			<div class="card" style="width: 12rem; border: skyblue solid 1px;">
				<div class="card-body">
					<a href="../notepad/wareneingangid.html" class="btn btn-primary" role="button"><i class="fa fa-truck"></i>Wareneingang</a>
				</div>
			</div>
			
			<div class="card" style="width: 12rem; border: skyblue solid 1px;">
				<div class="card-body">
					<a href="#" class="btn btn-primary" role="button"><i class="fa fa-barcode"></i>Kommisionierung</a>
				</div>
			</div>
			
			<div class="card" style="width: 12rem; border: skyblue solid 1px;">
				<div class="card-body">
					<a href="#" class="btn btn-primary"><i class="fa fa-check-square-o"></i>Inventur</a>
				</div>
			</div>
			
			<div class="card" style="width: 12rem; border: skyblue solid 1px;">
				<div class="card-body">
					<a href="../notepad/zurueckid.html" class="btn btn-primary"><i class="fa fa-qrcode"></i>Scan/Info</a><br>
				</div>
			</div>
			
			<div class="card" style="width: 12rem; border: skyblue solid 1px;">
				<div class="card-body">
					<a href="../notepad/umlagerungid.html" class="btn btn-primary"><i class="fa fa-arrows-v"> </i>Umlagerung</a>
				</div>
			</div>
			
				
			</div>
		</div>
		
</div>


	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  
</body>
</html>
