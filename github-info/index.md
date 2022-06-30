﻿<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=Edge" />
        <meta name="description" />
        <meta name="keywords" content="static content generator,static site generator,static site,HTML,web development,.NET,C#,Razor,Markdown,YAML" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="shortcut icon" href="/Remora.Discord/assets/img/favicon.ico" type="image/x-icon">
        <link rel="icon" href="/Remora.Discord/assets/img/favicon.ico" type="image/x-icon">
        <title>Remora.Discord Documentation - Github Info</title>
        <link href="/Remora.Discord/assets/css/highlight.css" rel="stylesheet">
        <link href="/Remora.Discord/assets/css/bootstrap/bootstrap.css" rel="stylesheet" />
        <link href="/Remora.Discord/assets/css/adminlte/AdminLTE.css" rel="stylesheet" />
        <link href="/Remora.Discord/assets/css/theme/theme.css" rel="stylesheet" />
        <link href="//fonts.googleapis.com/css?family=Roboto+Mono:400,700|Roboto:400,400i,700,700i" rel="stylesheet">
        <link href="/Remora.Discord/assets/css/font-awesome.min.css" rel="stylesheet" type="text/css">
        <link href="/Remora.Discord/assets/css/override.css" rel="stylesheet" />
        <script src="/Remora.Discord/assets/js/jquery-2.2.3.min.js"></script>
        <script src="/Remora.Discord/assets/js/bootstrap.min.js"></script>        
        <script src="/Remora.Discord/assets/js/app.min.js"></script>         
        <script src="/Remora.Discord/assets/js/highlight.pack.js"></script>   
        <script src="/Remora.Discord/assets/js/jquery.slimscroll.min.js"></script>
        <script src="/Remora.Discord/assets/js/jquery.sticky-kit.min.js"></script>
        <script src="/Remora.Discord/assets/js/mermaid.min.js"></script>
        <script src="/Remora.Discord/assets/js/svg-pan-zoom.min.js"></script>
        <!--[if lt IE 9]>
        <script src="/Remora.Discord/assets/js/html5shiv.min.js"></script>
        <script src="/Remora.Discord/assets/js/respond.min.js"></script>
        <![endif]-->  

        
    </head>
    <body class="hold-transition wyam layout-boxed  ">    
        <div class="top-banner"></div>
        <div class="wrapper with-container">
            <!-- Header -->
            <header class="main-header">   
                     
                <a href="/Remora.Discord/" class="logo">
                            <span>Remora.Discord Documentation</span>
                </a>   
                         
                <nav class="navbar navbar-static-top" role="navigation">
                    <!-- Sidebar toggle button-->
                        <a href="#" class="sidebar-toggle visible-xs-block" data-toggle="offcanvas" role="button">
                            <span class="sr-only">Toggle side menu</span>
                            <i class="fa fa-chevron-circle-right"></i>
                        </a>
                                        
                    <div class="navbar-header">
                        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse">
                            <span class="sr-only">Toggle side menu</span>
                            <i class="fa fa-chevron-circle-down"></i>
                        </button>
                    </div>
            
                    <!-- Collect the nav links, forms, and other content for toggling -->
                    <div class="collapse navbar-collapse pull-left" id="navbar-collapse">
                        <ul class="nav navbar-nav">                            
                                    <li><a href="/Remora.Discord/guides">Guides</a></li>
        <li><a href="/Remora.Discord/info">Info</a></li>
        <li><a href="/Remora.Discord/README">README</a></li>
        <li><a href="/Remora.Discord/Remora.Discord.Caching.Redis">Remora</a></li>
        <li><a href="/Remora.Discord/Remora.Discord.Rest">Remora</a></li>
        <li><a href="/Remora.Discord/Remora.Discord.API.Abstractions">Remora</a></li>
        <li><a href="/Remora.Discord/Remora.Discord.Gateway">Remora</a></li>
        <li><a href="/Remora.Discord/Remora.Discord.Caching.Abstractions">Remora</a></li>
        <li><a href="/Remora.Discord/Remora.Discord.Unstable">Remora</a></li>
        <li><a href="/Remora.Discord/Remora.Discord.Caching">Remora</a></li>
        <li><a href="/Remora.Discord/Remora.Discord.API">Remora</a></li>
        <li><a href="/Remora.Discord/api">API</a></li>
 
                        </ul>       
                    </div>
                    <!-- /.navbar-collapse -->
                
                    <!-- Navbar Right Menu -->
                </nav>
            </header>
            
            <!-- Left side column. contains the logo and sidebar -->
            <aside class="main-sidebar ">
                <section class="infobar" data-spy="affix" data-offset-top="60" data-offset-bottom="200"> 
                    	
    <div id="infobar-headings"></div>

                </section>
                <section class="sidebar">    
                                     
                    

                    <ul class="sidebar-menu">
                        

                <li><a href="/Remora.Discord/github-info/CONTRIBUTING">CONTRIBUTING</a></li>

                    </ul>
                            
                </section>                
            </aside>
            
            <!-- Content Wrapper. Contains page content -->
            <div class="content-wrapper">
                



		<section class="content-header">
			<h1>Github Info</h1>
		</section>
	<section class="content">
		
	</section>
                
            </div>           
            
            <!-- Footer -->
            <footer class="main-footer">
            </footer>
            
        </div>
        <div class="wrapper bottom-wrapper">
            <footer class="bottom-footer">
                Generated by <a href="https://wyam.io">Wyam</a>
            </footer>
        </div>
        <a href="javascript:" id="return-to-top"><i class="fa fa-chevron-up"></i></a>
        
        <script>           
            // Close the sidebar if we select an anchor link
            $(".main-sidebar a[href^='#']:not('.expand')").click(function(){
                $(document.body).removeClass('sidebar-open');
            });
            
            $(document).ready(function() {
                mermaid.initialize(
                {
                    flowchart:
                    {
                        useMaxWidth: false
                    },
					startOnLoad: false,
					cloneCssStyles: false
                });     
                mermaid.init(undefined, ".mermaid");

                // Remove the max-width setting that Mermaid sets
                var mermaidSvg = $('.mermaid svg');
                mermaidSvg.addClass('img-responsive');
                mermaidSvg.css('max-width', '');

                // Make it scrollable
				var target = document.querySelector(".mermaid svg");
				if(target !== null)
				{
					var panZoom = window.panZoom = svgPanZoom(target, {
						zoomEnabled: true,
						controlIconsEnabled: true,
						fit: true,
						center: true,
                        maxZoom: 20,
                        zoomScaleSensitivity: 0.6
					});			                          

                    // Do the reset once right away to fit the diagram
                    panZoom.resize();
                    panZoom.fit();
                    panZoom.center();
                    
                    $(window).resize(function(){
                        panZoom.resize();
                        panZoom.fit();
                        panZoom.center();
                    });
				}
                
                $('pre code').each(function(i, block) {
                    hljs.highlightBlock(block);
                });  
            });

            hljs.initHighlightingOnLoad();

            // Back to top
            $(window).scroll(function() {
                if ($(this).scrollTop() >= 200) {        // If page is scrolled more than 50px
                    $('#return-to-top').fadeIn(1000);    // Fade in the arrow
                } else {
                    $('#return-to-top').fadeOut(1000);   // Else fade out the arrow
                }
            });
            $('#return-to-top').click(function() {      // When arrow is clicked
                $('body,html').animate({
                    scrollTop : 0                       // Scroll to top of body
                }, 500);
            });
        </script>
    </body>
</html>