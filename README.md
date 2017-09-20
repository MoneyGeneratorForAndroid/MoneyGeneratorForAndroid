<!DOCTYPE html>
<html ng-app="Admin1">
  <head>
    <meta charset="UTF-8">
    <title>ChatROOM</title>
    <meta content='width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no' name='viewport'>
    <link rel="shortcut icon" type="image/png" href="app/images/favicon.png"/>
    <!-- lightbox -->
    <link rel="stylesheet" type="text/css" href="lib/plugins/lightbox2/dist/css/lightbox.css"/>
    <!-- Bootstrap 3.3.4 -->
    <link href="app/css/bootstrap/css/bootstrap.min.css" rel="stylesheet" type="text/css" />
    <!-- Font Awesome Icons -->
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css" rel="stylesheet" type="text/css" />
    <!-- Ionicons -->
    <link href="https://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css" rel="stylesheet" type="text/css" />
    <!-- Theme style -->
    <link href="app/css/dist/css/AdminLTE.min.css" rel="stylesheet" type="text/css" />
    <!-- AdminLTE Skins. -->
    <link href="app/css/dist/css/skins/_all-skins.min.css" rel="stylesheet" type="text/css" />
     <!-- iCheck -->
    <link href="lib/plugins/iCheck/square/blue.css" rel="stylesheet" type="text/css" />
    <link rel="stylesheet" type="text/css" href="app/css/style.css" />
    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
        <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body class="skin-blue layout-top-nav login-page">
    <div ng-view>
  
    </div>
    <!-- jQuery 2.1.4 -->
    <script src="lib/plugins/jQuery/jQuery-2.1.4.min.js"></script>
    <!-- Bootstrap 3.3.2 JS -->
    <script src="lib/plugins/bootstrap/js/bootstrap.min.js" type="text/javascript"></script>
    <!-- FastClick -->
    <script src='lib/plugins/fastclick/fastclick.min.js'></script>
    <!-- AdminLTE App.js -->
    <script src="app/css/dist/js/app.min.js" type="text/javascript"></script>
    <!-- SlimScroll -->
    <script src="lib/plugins/slimScroll/jquery.slimscroll.min.js" type="text/javascript"></script>
    <!-- AdminLTE dashboard demo -->
    <script src="app/css/dist/js/pages/dashboard2.js" type="text/javascript"></script>
    <script src="app/css/dist/js/demo.js" type="text/javascript"></script>
    <!-- lightbox jquery -->
    <script src="lib/plugins/lightbox2/dist/js/lightbox.js" type="text/javascript"></script>
    <!-- angularJS -->
    <script src="lib/plugins/angular/angular.js" type="text/javascript"></script>
    <!-- angular-resource -->
    <script src="lib/plugins/angular-resource/angular-resource.js" type="text/javascript"></script>
    <!-- angular-route -->
    <script src="lib/plugins/angular-route/angular-route.js" type="text/javascript"></script>
    <!-- iCheck -->
    <script src="lib/plugins/iCheck/icheck.min.js" type="text/javascript"></script>
    <!-- ngStorage -->
    <script src="lib/plugins/ngStorage.min.js" type="text/javascript"></script>
    <!-- angular-sockets -->
    <script src="lib/plugins/angular-socket.js" type="text/javascript"></script>
    <!-- Socket.io -->
    <script type="text/javascript" src="/socket.io/socket.io.js"></script>
    <!-- ng-file-upload-shim.js -->
    <script type="text/javascript" src="lib/plugins/ng-file-upload-shim.js"></script>
    <!-- ng-file-upload.js -->
    <script type="text/javascript" src="lib/plugins/ng-file-upload.js"></script>
    <!-- angular animate -->
    <script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.4.1/angular-animate.js"></script>
    <!-- app.js -->
    <script src="app/js/app.js" type="text/javascript"></script>

    <!-- Controllers -->
    <script src="app/controllers/loginController.js" type="text/javascript"></script> <!-- Login controller -->
    <script src="app/controllers/chatRoomController.js" type="text/javascript"></script> <!-- chatRoom controller -->

    <!-- Services -->
    <script src="app/services/sendImageService.js" type="text/javascript"></script>
    <br>
  </body>
</html>
