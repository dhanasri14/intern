
<!DOCTYPE html>
<html lang="en">

<head>

    <!-- Basic -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <!-- Mobile Metas -->
    <meta name="viewport" content="width=device-width, maximum-scale=1, initial-scale=1, user-scalable=0">

    <!-- Site Metas -->
    <title>Food Funday Restaurant - One page HTML Responsive</title>
    <meta name="keywords" content="">
    <meta name="description" content="">
    <meta name="author" content="">

    <!-- Site Icons -->
    <link rel="shortcut icon" href="images/favicon.ico" type="image/x-icon" />
    <link rel="apple-touch-icon" href="images/apple-touch-icon.png">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <!-- Site CSS -->
    <link rel="stylesheet" href="css/style.css">
    <!-- Responsive CSS -->
    <link rel="stylesheet" href="css/responsive.css">
    <!-- color -->
    <link id="changeable-colors" rel="stylesheet" href="css/colors/orange.css" />

    <!-- Modernizer -->
    <script src="js/modernizer.js"></script>

    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->

</head>

<body>
    <div id="loader">
        <div id="status"></div>
    </div>
    <div id="site-header">
        <header id="header" class="header-block-top">
            <div class="container">
                <div class="row">
                    <div class="main-menu">
                        <!-- navbar -->
                        <nav class="navbar navbar-default" id="mainNav">
                            <div class="navbar-header">
                                <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                                    <span class="sr-only">Toggle navigation</span>
                                    <span class="icon-bar"></span>
                                    <span class="icon-bar"></span>
                                    <span class="icon-bar"></span>
                                </button>
                                <div class="logo">
                                    <a class="navbar-brand js-scroll-trigger logo-header" href="#">
                                        <img src="d:\intern\imglogo-removebg-preview.png" alt="">
                                    </a>
                                </div>
                            </div>
                            <div id="navbar" class="navbar-collapse collapse">
                                <ul class="nav navbar-nav navbar-right">
                                    <li class="active"><a href="#banner">Home</a></li>
                                    <li><a href="#about">About us</a></li>
                                    <li><a href="#menu">Menu</a></li>
                                    <li><a href="#our_team">Team</a></li>
                                    <li><a href="#gallery">Gallery</a></li>
                                    <li><a href="#blog">Blog</a></li>
                                    <li><a href="#pricing">pricing</a></li>
                                    <li><a href="#reservation">Reservaion</a></li>
                                    <li><a href="#footer">Contact us</a></li>
                                </ul>
                            </div>
                            <!-- end nav-collapse -->
                        </nav>
                        <!-- end navbar -->
                    </div>
                </div>
                <!-- end row -->
            </div>
            <!-- end container-fluid -->
        </header>
        <!-- end header -->
    </div>
	<!-- end site-header -->
	
    <div id="banner" class="banner full-screen-mode parallax">
        <div class="container pr">
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <div class="banner-static">
                    <div class="banner-text">
                        <div class="banner-cell">
                            <h1>Eat with  <span class="typer" id="some-id" data-delay="200" data-delim=":" data-words="Friends:Family:Officemates" data-colors="red"></span><span class="cursor" data-cursorDisplay="_" data-owner="some-id"></span></h1>
                            <h2>Gastronomic Journey Of Italian Cuisine</h2>
                            <p>A Good Food,Can Turn Any Day Around </p>
                            <div class="book-btn">
                                <a href="#reservation" class="table-btn hvr-underline-from-center">Book my Table</a>
                            </div>
                            <a href="#about">
                                <div class="mouse"></div>
                            </a>
                        </div>
                        <!-- end banner-cell -->
                    </div>
                    <!-- end banner-text -->
                </div>
                <!-- end banner-static -->
            </div>
            <!-- end col -->
        </div>
        <!-- end container -->
    </div>
    <!-- end banner -->

    <div id="about" class="about-main pad-top-100 pad-bottom-100">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <h2 class="block-title"> About Us </h2>
                        <h3>IT STARTED LIKE...</h3>
                        <p> Olive n' Basil Curates an Expiremental Dining Expirence. Our chef together with staffs,personally engae and assist each table with our menu choices. </p>
                        <p> New world of Olive n'Basil now invites you with its tempting experience and memorable conversations cooked the traditional way. </p>
                    </div>
                </div>
                <!-- end col -->
                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12">
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <div class="about-images">
                            <img class="about-main" src="images/about-main.jpg" alt="About Main Image">
                            <img class="about-inset" src="d:\intern\abtimg2.jpeg" alt="About Inset Image">
                        </div>
                    </div>
                </div>
                <!-- end col -->
            </div>
            <!-- end row -->
        </div>
        <!-- end container -->
    </div>

    <div class="special-menu pad-top-100 parallax">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <h2 class="block-title color-white text-center"> Today's Special </h2>
                        <h5 class="title-caption text-center"> True, authentic and filling, slide your finger over an extensive list of Italian gourmet dishes, an extensive list of wines and set sail on an Italian rendezvous that will linger on for a long time, even after you've stepped out. </h5>
                    </div>
                    <div class="special-box">
                        <div id="owl-demo">
                            <div class="item item-type-zoom">
                                <a href="#" class="item-hover">
                                    <div class="item-info">
                                        <div class="headline">
                                            SICILIAN BASIL PESTO
                                            <div class="line"></div>
                                            <div class="dit-line">Ligurian pesto—it's rich with nuts, basil, olive oil, garlic, and cheese.</div>
                                        </div>
                                    </div>
                                </a>
                                <div class="item-img">
                                    <img src="d:\intern\ts1.jpeg" alt="sp-menu">
                                </div>
                            </div>
                            <div class="item item-type-zoom">
                                <a href="#" class="item-hover">
                                    <div class="item-info">
                                        <div class="headline">
                                            MARINARA
                                            <div class="line"></div>
                                            <div class="dit-line"> It is made with tomatoes, basil, olive oil, garlic and oregano, capers, and salted anchovies.</div>
                                        </div>
                                    </div>
                                </a>
                                <div class="item-img">
                                    <img src="d:\intern\ts2.jpeg" alt="sp-menu">
                                </div>
                            </div>
                            <div class="item item-type-zoom">
                                <a href="#" class="item-hover">
                                    <div class="item-info">
                                        <div class="headline">
                                            AGILIO OLIO
                                            <div class="line"></div>
                                            <div class="dit-line">  The most traditional form, it's just cooked pasta tossed in garlic, olive oil, and pasta water.</div>
                                        </div>
                                    </div>
                                </a>
                                <div class="item-img">
                                    <img src="d:\intern\ts3.jpeg" alt="sp-menu">
                                </div>
                            </div>
                            <div class="item item-type-zoom">
                                <a href="#" class="item-hover">
                                    <div class="item-info">
                                        <div class="headline">
                                            SALMON STEAK
                                            <div class="line"></div>
                                            <div class="dit-line">It is considered a delicacy, and it is also a species that is difficult to farm.</div>
                                        </div>
                                    </div>
                                </a>
                                <div class="item-img">
                                    <img src="d:\intern\ts4.jpeg" alt="sp-menu">
                                </div>
                            </div>
                            <div class="item item-type-zoom">
                                <a href="#" class="item-hover">
                                    <div class="item-info">
                                        <div class="headline">
                                            SUNDRIED TOMATO PESTO
                                            <div class="line"></div>
                                            <div class="dit-line">This quick sun dried tomatoes, garlic, fresh basil, pine nuts, Parmesan cheese and olive oil.</div>
                                        </div>
                                    </div>
                                </a>
                                <div class="item-img">
                                    <img src="d:\intern\ts5.jpeg" alt="sp-menu">
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- end special-box -->
                </div>
                <!-- end col -->
            </div>
            <!-- end row -->
        </div>
        <!-- end container -->
    </div>
    <!-- end special-menu -->

    <div id="menu" class="menu-main pad-top-100 pad-bottom-100">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <h2 class="block-title text-center">
						Our Menu 	
					</h2>
                        <p class="title-caption text-center">Life is a combination of magic and pasta!. </p>
                    </div>
                    <div class="tab-menu">
                        <div class="slider slider-nav">
                            <div class="tab-title-menu">
                                <h2>STARTERS</h2>
                                <p> <i class="flaticon-canape"></i> </p>
                            </div>
                            <div class="tab-title-menu">
                                <h2>MAIN DISHES</h2>
                                <p> <i class="flaticon-dinner"></i> </p>
                            </div>
                            <div class="tab-title-menu">
                                <h2>CHAATS</h2>
                                <p> <i class="flaticon-desert"></i> </p>
                            </div>
                            <div class="tab-title-menu">
                                <h2>SHORT BYTES</h2>
                                <p> <i class="flaticon-coffee"></i> </p>
                            </div>
                        </div>
                        <div class="slider slider-single">
                            <div>
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img1.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>JALAPENO CHEESE BALL</h3>
                                            <p>
                                                Soft cheese centre with chunks of spicy jalapeno chilli and corn, wrapped in a crispy crumb coating..
                                            </p>
                                        </div>
                                        <span class="offer-price">$4.5</span>
                                    </div>
                                </div>
                                <!-- end col -->
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img2.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>CLASSIC FRIES</h3>
                                            <p>
                                                The origin of french fries is uncertain. According to one tradition, they first appeared in France, where they were likely a snack sold by street peddlers.
                                            </p>
                                        </div>
                                        <span class="offer-price">$10</span>
                                    </div>
                                </div>
                                <!-- end col -->
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img3.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>MOZARELLA CHEESE STICKS</h3>
                                            <p>
                                                The only ingredients here are mozzarella cheese, Italian breadcrumbs, and egg. 
                                            </p>
                                        </div>
                                        <span class="offer-price">$10</span>
                                    </div>
                                </div>
                                <!-- end col -->
                            </div>
                            <div>
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img4.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>ChEESY WHITE</h3>
                                            <p>
                                                White sauce is a very versatile sauce that you can use to prepare numerous tasty dishes like lasagna, baked pasta.
                                            </p>
                                        </div>
                                        <span class="offer-price">$5.5</span>
                                    </div>
                                </div>
                                <!-- end col -->
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img5.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>PESTO</h3>
                                            <p>
                                                This fresh and fragrant pasta sauce is served uncooked, so choose a pasta shape that won't overwhelm it.
                                            </p>
                                        </div>
                                        <span class="offer-price">$12</span>
                                    </div>
                                </div>
                                <!-- end col -->
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="images/menu-item-thumbnail-06.jpg" alt="" class="img-responsive">
                                        <div>
                                            <h3>PINK SAUCE PASTA</h3>
                                            <p>
                                                Pink Sauce Pasta is cooked pasta tossed with equal parts red marinara sauce and white alfredo sauce which combine to make – you got it – a pink-hued sauce.
                                            </p>
                                        </div>
                                        <span class="offer-price">$4.5</span>
                                    </div>
                                </div>
                                <!-- end col -->
                            </div>
                            <div>
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img7.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>DAHI PAPDI</h3>
                                            <p>
                                                Dahi papri chaat is unbelievably easy to make, it’s jam-packed with combinations of flavors and everyone loves it.
                                            </p>
                                        </div>
                                        <span class="offer-price">$2.5</span>
                                    </div>
                                </div>
                                <!-- end col -->
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="images/menu-item-thumbnail-08.jpg" alt="" class="img-responsive">
                                        <div>
                                            <h3>SEV PAPDI</h3>
                                        <p>
                                            Sev puri is essentially made of crispy papdi (flat puri) which is loaded with diced potatoes, chickpeas, onions and various types of chutneys. 
                                            </p>
                                        </div>
                                        <span class="offer-price">$9.5</span>
                                    </div>
                                </div>
                                <!-- end col -->
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img9.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>DESSERTS</h3>
                                            <p>
                                                A dessert is a type of food that is eaten after lunch or dinner, and sometimes after a light meal or snack.
                                            </p>
                                        </div>
                                        <span class="offer-price">$15</span>
                                    </div>
                                </div>
                                <!-- end col -->
                            </div>
                            <div>
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img10.jpeg" alt="" class="img-responsive">
                                    <div>
                                        <h3>NACHOS WITH SALSA</h3>
                                        <p>
                                            It has  parsley, mint, basil, and oregano also taste terrific mixed with fresh vegetables and fruits.
                                            </p>
                                        </div>
                                        <span class="offer-price">$12</span>
                                    </div>
                                </div>
                                <!-- end col -->
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img11.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>CHEESE GARLIC BREAD</h3>
                                            <p>
                                                Garlic bread can be a delicious appetizer on its own or served with dips like marinara sauce or aioli
                                            </p>
                                        </div>
                                        <span class="offer-price">$6.5</span>
                                    </div>
                                </div>
                                <!-- end col -->
                                <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 ">
                                    <div class="offer-item">
                                        <img src="d:\intern\img12.jpeg" alt="" class="img-responsive">
                                        <div>
                                            <h3>MASALA GARLIC BREAD</h3>
                                            <p>
                                                It can be a delicious accompaniment to pasta dishes, such as spaghetti or lasagna. 
                                            </p>
                                        </div>
                                        <span class="offer-price">$8.5</span>
                                    </div>
                                </div>
                                <!-- end col -->
                            </div>
                        </div>
                    </div>
                    <!-- end tab-menu -->
                </div>
                <!-- end col -->
            </div>
            <!-- end row -->
        </div>
        <!-- end container -->
    </div>
    <!-- end menu -->

    <div id="our_team" class="team-main pad-top-100 pad-bottom-100 parallax">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <h2 class="block-title text-center">
						Our Team 	
					</h2>
                    <p class="title-caption text-center">The illustrious career boasts a splendid amalgamation of diverse culinary backgrounds, underscoring the breadth and depth of his culinary prowess. </p>
                </div>
                <div class="team-box">

                    <div class="row">
                        <div class="col-md-4 col-sm-6">
                            <div class="sf-team">
                                <div class="thumb">
                                    <a href="#"><img src="d:\intern\img13.jpeg" alt=""></a>
                                </div>
                                <div class="text-col">
                                    <h3>Birjesh Kumar</h3>
                                    <p> Chef Birjesh Kumar is the Executive Chef at Le Meridien Gurgaon.
                                        With a remarkable tenure spanning more than 23 years in the dynamic hospitality industry.</p>
                                    <ul class="team-social">
                                        <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                                        <li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                                        <li><a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-md-4 col-sm-6">
                            <div class="sf-team">
                                <div class="thumb">
                                    <a href="#"><img src="d:\intern\img14.jpg" alt=""></a>
                                </div>
                                <div class="text-col">
                                    <h3>Alessio Banchero</h3>
                                    <p>JW Marriott New Delhi Aerocity has appointed Chef Alessio Banchero as the Italian Chef de Cuisine."Chefs don't make mistakes; they make new dishes." -

                                        Every meal must be perfectly plated.</p>
                                    <ul class="team-social">
                                        <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                                        <li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                                        <li><a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-md-4 col-sm-6">
                            <div class="sf-team">
                                <div class="thumb">
                                    <a href="#"><img src="d:\intern\img15.jpeg" alt=""></a>
                                </div>
                                <div class="text-col">
                                    <h3>Iginio Massari</h3>
                                    <p>Ignio Massari had fairly humble beginnings, as a worker in a bakery.Italian cuisine has a great variety of different ingredients like ranging from fruits, vegetables, grains, cheeses, meats and fish.A great chef is an artist that I truly respect.  learning to be a good chef.</p>
                                    <ul class="team-social">
                                        <li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                                        <li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                                        <li><a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <!-- end col -->
                    </div>
                    <!-- end row -->

                </div>
                <!-- end team-box -->

            </div>
            <!-- end col -->
        </div>
        <!-- end row -->
    </div>
    <!-- end container -->
</div>
<!-- end team-main -->

<div id="gallery" class="gallery-main pad-top-100 pad-bottom-100">
    <div class="container">
        <div class="row">
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                    <h2 class="block-title text-center">
					Our Gallery	
				</h2>
                    <p class="title-caption text-center">Restaurant Spotlight: Discover The Gastronomic Joys Of Italy At Le Meridien’s Stellar Restaurant Olive'n Basil </p>
                </div>
                <div class="gal-container clearfix">
                    <div class="col-md-8 col-sm-12 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#1">
                                <img src="d:\intern\img16.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="1" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="d:\intern\img17.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 1 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#2">
                                <img src="d:\intern\img18.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="2" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="d:\intern\img19.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 2 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#3">
                                <img src="d:\intern\img20.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="3" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="d:\intern\img21.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 3 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#4">
                                <img src="d:\intern\img22.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="4" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="d:\intern\img23.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 4 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#5">
                                <img src="d:\intern\img24.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="5" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="images/gallery_05.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 5 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#9">
                                <img src="images/gallery_06.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="9" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="images/gallery_06.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 6 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-8 col-sm-12 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#10">
                                <img src="images/gallery_07.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="10" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="images/gallery_07.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 7 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#11">
                                <img src="images/gallery_08.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="11" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="images/gallery_08.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 8 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#12">
                                <img src="images/gallery_09.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="12" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="images/gallery_09.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 9 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4 col-sm-6 co-xs-12 gal-item">
                        <div class="box">
                            <a href="#" data-toggle="modal" data-target="#13">
                                <img src="images/gallery_10.jpg" alt="" />
                            </a>
                            <div class="modal fade" id="13" tabindex="-1" role="dialog">
                                <div class="modal-dialog" role="document">
                                    <div class="modal-content">
                                        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
                                        <div class="modal-body">
                                            <img src="images/gallery_10.jpg" alt="" />
                                        </div>
                                        <div class="col-md-12 description">
                                            <h4>This is the 10 one on my Gallery</h4>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- end gal-container -->
            </div>
            <!-- end col -->
        </div>
        <!-- end row -->
    </div>
    <!-- end container -->
</div>
<!-- end gallery-main -->

<div id="blog" class="blog-main pad-top-100 pad-bottom-100 parallax">
    <div class="container">
        <div class="row">
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <h2 class="block-title text-center">
				Our Blog 	
			</h2>
                <div class="blog-box clearfix">
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <div class="col-md-6 col-sm-6">
                            <div class="blog-block">
                                <div class="blog-img-box">
                                    <img src="images/featured-image-01.jpg" alt="" />
                                    <div class="overlay">
                                        <a href="#"><i class="fa fa-link" aria-hidden="true"></i></a>
                                    </div>
                                </div>
                                <div class="blog-dit">
                                    <p><span>25 NOVEMBER, 2023</span></p>
                                    <h2> WOW Dishes.</h2>
                                    <h5>By Dev Adhithyan</h5>
                                </div>
                            </div>
                        </div>
                        <!-- end col -->
                    </div>
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <div class="col-md-6 col-sm-6">
                            <div class="blog-block">
                                <div class="blog-img-box">
                                    <img src="images/featured-image-02.jpg" alt="" />
                                    <div class="overlay">
                                        <a href="#"><i class="fa fa-link" aria-hidden="true"></i></a>
                                    </div>
                                </div>
                                <div class="blog-dit">
                                    <p><span>6 DECEMBER, 2023</span></p>
                                    <h2>INDULGENCE!</h2>
                                    <h5>BY Krishnan </h5>
                                </div>
                            </div>
                        </div>
                        <!-- end col -->
                    </div>
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <div class="col-md-6 col-sm-6">
                            <div class="blog-block">
                                <div class="blog-img-box">
                                    <img src="images/featured-image-03.jpg" alt="" />
                                    <div class="overlay">
                                        <a href="#"><i class="fa fa-link" aria-hidden="true"></i></a>
                                    </div>
                                </div>
                                <div class="blog-dit">
                                    <p><span>4 JANUARY, 2024</span></p>
                                    <h2>EXPLORATION</h2>
                                    <h5>BY Monica</h5>
                                </div>
                            </div>
                        </div>
                        <!-- end col -->
                    </div>
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <div class="col-md-6 col-sm-6">
                            <div class="blog-block">
                                <div class="blog-img-box">
                                    <img src="images/featured-image-04.jpg" alt="" />
                                    <div class="overlay">
                                        <a href="#"><i class="fa fa-link" aria-hidden="true"></i></a>
                                    </div>
                                </div>
                                <div class="blog-dit">
                                    <p><span>12 NOVEMBER, 2024</span></p>
                                    <h2>
                                        FLAVORFUL ODYSSEY</h2>
                                    <h5>BY David</h5>
                                </div>
                            </div>
                        </div>
                        <!-- end col -->
                    </div>
                </div>
                <!-- end blog-box -->

                <div class="blog-btn-v">
                    <a class="hvr-underline-from-center" href="#">View the Blog</a>
                </div>

            </div>
            <!-- end col -->
        </div>
        <!-- end row -->
    </div>
    <!-- end container -->
</div>
<!-- end blog-main -->

<div id="pricing" class="pricing-main pad-top-100 pad-bottom-100">
    <div class="container">
        <div class="row">
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                <h2 class="block-title text-center">
					Pricing 	
				</h2>
                <p>"Indulge in Taste, Reserve in Style – Your Culinary Journey Awaits with Seamless Seat Booking at Olive n' Basil!".</p>
            </div>
            <div class="panel-pricing-in">
                <!-- item -->
                <div class="col-md-4 col-sm-4 text-center">
                    <div class="panel panel-pricing">
                        <div class="panel-heading">
                            <div class="pric-icon">
                                <img src="images/store.png" alt="" />
                            </div>
                            <h3>Basic</h3>
                        </div>
                        <div class="panel-body text-center">
                            <p><strong>$300/<span>2hours</span></strong></p>
                        </div>
                        <ul class="list-group text-center">
                            <li class="list-group-item"><i class="fa fa-check"></i> Decorations</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Seatings</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Starters</li>
                            <li class="list-group-item"><i class="fa fa-times"></i> Foods</li>
                            <li class="list-group-item"><i class="fa fa-times"></i> 20 Tables</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Car Parkings</li>
                        </ul>
                        <div class="panel-footer">
                            <a class="btn btn-lg btn-block hvr-underline-from-center" href="#">Purchase Now!</a>
                        </div>
                    </div>
                </div>
                <!-- /item -->

                <!-- item -->
                <div class="col-md-4 col-sm-4 text-center">
                    <div class="panel panel-pricing">
                        <div class="panel-heading">
                            <div class="pric-icon">
                                <img src="images/food.png" alt="" />
                            </div>
                            <h3>Pro</h3>
                        </div>
                        <div class="panel-body text-center">
                            <p><strong>$600/<span>3hours</span></strong></p>
                        </div>
                        <ul class="list-group text-center">
                            <li class="list-group-item"><i class="fa fa-check"></i> Decorations</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Cakes,Starters</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Seatings</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Variety of Dishes</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Car Parkings</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Games For kids</li>
                        </ul>
                        <div class="panel-footer">
                            <a class="btn btn-lg btn-block hvr-underline-from-center" href="#">Purchase Now!</a>
                        </div>
                    </div>
                </div>
                <!-- /item -->

                <!-- item -->
                <div class="col-md-4 col-sm-4 text-center">
                    <div class="panel panel-pricing">
                        <div class="panel-heading">
                            <div class="pric-icon">
                                <img src="images/coffee.png" alt="" />
                            </div>
                            <h3>Platinum</h3>
                        </div>
                        <div class="panel-body text-center">
                            <p><strong>$900/<span>5Hours</span></strong></p>
                        </div>
                        <ul class="list-group text-center">
                            <li class="list-group-item"><i class="fa fa-check"></i> Decorations</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Seatings</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Welcome Drinks</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Cakes,Return Gifts</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Banners, Games</li>
                            <li class="list-group-item"><i class="fa fa-check"></i> Parkings,Delicious Foods</li>
                        </ul>
                        <div class="panel-footer">
                            <a class="btn btn-lg btn-block hvr-underline-from-center" href="#">Purchase Now!</a>
                        </div>
                    </div>
                </div>
                <!-- /item -->
            </div>
        </div>
        <!-- end row -->
    </div>
    <!-- end container -->
</div>
<!-- end pricing-main -->

<div id="reservation" class="reservations-main pad-top-100 pad-bottom-100">
    <div class="container">
        <div class="row">
            <div class="form-reservations-box">
                <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <h2 class="block-title text-center">
					Reservations			
				</h2>
                    </div>
                    <h4 class="form-title">BOOKING FORM</h4>
                    <p>PLEASE FILL OUT ALL REQUIRED* FIELDS. THANKS!</p>

                    <form id="contact-form" method="post" class="reservations-box" name="contactform" action="https://themewagon.github.io/food-funday/mail.php">
                        <div class="col-lg-6 col-md-6 col-sm-6 col-xs-12">
                            <div class="form-box">
                                <input type="text" name="form_name" id="form_name" placeholder="Name" required="required" data-error="Firstname is required.">
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-lg-6 col-md-6 col-sm-6 col-xs-12">
                            <div class="form-box">
                                <input type="email" name="email" id="email" placeholder="E-Mail ID" required="required" data-error="E-mail id is required.">
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-lg-6 col-md-6 col-sm-6 col-xs-12">
                            <div class="form-box">
                                <input type="text" name="phone" id="phone" placeholder="contact no.">
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-lg-6 col-md-6 col-sm-6 col-xs-12">
                            <div class="form-box">
                                <select name="no_of_persons" id="no_of_persons" class="selectpicker">
                                    <option selected disabled>No. Of persons</option>
                                    <option>1</option>
                                    <option>2</option>
                                    <option>3</option>
                                </select>
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-lg-6 col-md-6 col-sm-6 col-xs-12">
                            <div class="form-box">
                                <input type="text" name="date-picker" id="date-picker" placeholder="Date" required="required" data-error="Date is required." />
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-lg-6 col-md-6 col-sm-6 col-xs-12">
                            <div class="form-box">
                                <input type="text" name="time-picker" id="time-picker" placeholder="Time" required="required" data-error="Time is required." />
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-lg-6 col-md-6 col-sm-6 col-xs-12">
                            <div class="form-box">
                                <select name="preferred_food" id="preferred_food" class="selectpicker">
                                    <option selected disabled>preferred food</option>
                                    <option>Indian</option>
                                    <option>Continental</option>
                                    <option>Mexican</option>
                                </select>
                            </div>
                        </div>
                        <!-- end col -->
                        <div class="col-lg-6 col-md-6 col-sm-6 col-xs-12">
                            <div class="form-box">
                                <select name="occasion" id="occasion" class="selectpicker">
                                    <option selected disabled>Occasion</option>
                                    <option>Wedding</option>
                                    <option>Birthday</option>
                                    <option>Anniversary</option>
                                </select>
                            </div>
                        </div>
                        <!-- end col -->

                        <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                            <div class="reserve-book-btn text-center">
                                <button class="hvr-underline-from-center" type="submit" value="SEND" id="submit">BOOK MY TABLE </button>
                            </div>
                        </div>
                        <!-- end col -->
                    </form>
                    <!-- end form -->
                </div>
                <!-- end col -->
            </div>
            <!-- end reservations-box -->
        </div>
        <!-- end row -->
    </div>
    <!-- end container -->
</div>
<!-- end reservations-main -->

<div id="footer" class="footer-main">
    <div class="footer-news pad-top-100 pad-bottom-70 parallax">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                    <div class="wow fadeIn" data-wow-duration="1s" data-wow-delay="0.1s">
                        <h2 class="ft-title color-white text-center"> Newsletter </h2>
                        <p> An experiential dining experience that is personal, center stages the mood of the diners.</p>
                    </div>
                    <form>
                        <input type="email" placeholder="Enter your e-mail id">
                        <a href="#" class="orange-btn"><i class="fa fa-paper-plane-o" aria-hidden="true"></i></a>
                    </form>
                </div>
                <!-- end col -->
            </div>
            <!-- end row -->
        </div>
        <!-- end container -->
    </div>
    <!-- end footer-news -->
    <div class="footer-box pad-top-70">
        <div class="container">
            <div class="row">
                <div class="footer-in-main">
                    <div class="footer-logo">
                        <div class="text-center">
                            <img src="d:\intern\imglogo-removebg-preview.png" alt="" />
                        </div>
                    </div>
                    <div class="col-lg-3 col-md-3 col-sm-6 col-xs-12">
                        <div class="footer-box-a">
                            <h3>About Us</h3>
                            <p>The chef together with the service staff, personally engage and assist each table with their menu choices and hence, the resulting signature dishes are delightfully unique to that moment.</p>
                            <ul class="socials-box footer-socials pull-left">
                                <li>
                                    <a href="#">
                                        <div class="social-circle-border"><i class="fa  fa-facebook"></i></div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="social-circle-border"><i class="fa fa-twitter"></i></div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="social-circle-border"><i class="fa fa-google-plus"></i></div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="social-circle-border"><i class="fa fa-pinterest"></i></div>
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        <div class="social-circle-border"><i class="fa fa-linkedin"></i></div>
                                    </a>
                                </li>
                            </ul>

                        </div>
                        <!-- end footer-box-a -->
                    </div>
                    <!-- end col -->
                    <div class="col-lg-3 col-md-3 col-sm-6 col-xs-12">
                        <div class="footer-box-b">
                            <h3>Known For</h3>
                            <ul>
                                <li><a href="#">Polite Staff</a></li>
                                <li><a href="#">Quick service</a></li>
                                <li><a href="#">Ambience</a></li>
                                <li><a href="#">Taste of Cusines</a></li>
                            </ul>
                        </div>
                        <!-- end footer-box-b -->
                    </div>
                    <!-- end col -->
                    <div class="col-lg-3 col-md-3 col-sm-6 col-xs-12">
                        <div class="footer-box-c">
                            <h3>Contact Us</h3>
                            <p>
                                <i class="fa fa-map-signs" aria-hidden="true"></i>
                                <span>Sakthi Road Sivanandhapuram Saravanampatti, Near prozone mall LGP Nagar bus stop, Coimbatore, TN 641035</span>
                            </p>
                            <p>
                                <i class="fa fa-mobile" aria-hidden="true"></i>
                                <span>
								+91 78711 88800
							</span>
                            </p>
                            <p>
                                <i class="fa fa-envelope" aria-hidden="true"></i>
                                <span><a href="#">support@Olive n' Basil.com</a></span>
                            </p>
                        </div>
                        <!-- end footer-box-c -->
                    </div>
                    <!-- end col -->
                    <div class="col-lg-3 col-md-3 col-sm-6 col-xs-12">
                        <div class="footer-box-d">
                            <h3>Opening Hours</h3>

                            <ul>
                                <li>
                                    <p>Monday - Thursday </p>
                                    <span> 11:00 AM - 8:00 PM</span>
                                </li>
                                <li>
                                    <p>Friday - Saturday </p>
                                    <span>  11:00 AM - 10:30 PM</span>
                                </li>
                            </ul>
                        </div>
                        <!-- end footer-box-d -->
                    </div>
                    <!-- end col -->
                </div>
                <!-- end footer-in-main -->
            </div>
            <!-- end row -->
        </div>
        <!-- end container -->
        <div id="copyright" class="copyright-main">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
                        <h6 class="copy-title"> By continuing past this page, you agree to our Terms of Service, Cookie Policy, Privacy Policy and Content Policies. All trademarks are properties of their respective owners. 2008-2024 © Zomato™ Ltd. All rights reserved. </h6>
                    </div>
                </div>
                <!-- end row -->
            </div>
            <!-- end container -->
        </div>
        <!-- end copyright-main -->
    </div>
    <!-- end footer-box -->
</div>
<!-- end footer-main -->

<a href="#" class="scrollup" style="display: none;">Scroll</a>

<section id="color-panel" class="close-color-panel">
    <a class="panel-button gray2"><i class="fa fa-cog fa-spin fa-2x"></i></a>
    <!-- Colors -->
    <div class="segment">
        <h4 class="gray2 normal no-padding">Color Scheme</h4>
        <a title="orange" class="switcher orange-bg"></a>
        <a title="strong-blue" class="switcher strong-blue-bg"></a>
        <a title="moderate-green" class="switcher moderate-green-bg"></a>
        <a title="vivid-yellow" class="switcher vivid-yellow-bg"></a>
    </div>
</section>

<!-- ALL JS FILES -->
<script src="js/all.js"></script>
<script src="js/bootstrap.min.js"></script>
<!-- ALL PLUGINS -->
<script src="js/custom.js"></script>
