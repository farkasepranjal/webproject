<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Web</title>
  <link rel="shortcut icon" type="image/x-icon" href="https://www.nicepng.com/png/full/363-3634614_website-designing-web-logo.png" >
  <!-- CSS only -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
  <!-- JavaScript Bundle with Popper -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
    crossorigin="anonymous"></script>
  



</head>

<body>
  <nav class="navbar navbar-expand-lg bg-info">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <h2><b>Web</b></h2>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="home.html"><b>Home</b></a>

          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html"><b>About</b></a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              <b>Topics</b>
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="technology.html">TECHNOLOGY</a></li>
              <li><a class="dropdown-item" href="technews.html">TECH. NEWS</a></li>
              <li><a class="dropdown-item" href="trends.html">TRENDS</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">Support</a></li>
              <li><a class="dropdown-item" href="#">Write for us</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contactus.html"><b>Contact Us</b></a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-success" type="submit">Search</button>
        </form>
        <div class="mx-2">
          <!-- Button trigger modal -->
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
            Signup
          </button>

          <!-- Modal -->
          <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
            aria-hidden="true">
            <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <h5 class="modal-title" id="exampleModalLabel">Web  Signup</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Mobile no.</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label"> re-enter Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label"> confirm Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>

                  </div>

                  <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>

                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>



        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#cexampleModal">
          Login

        </button>

        <!-- Modal -->
        <div class="modal fade" id="cexampleModal" tabindex="-1" aria-labelledby="cexampleModalLabel"
          aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="cexampleModalLabel">Web Login</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <div class="mb-3 row">
                  <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
                  <div class="col-sm-10">
                    <input type="text" class="form-control" id="staticEmail">
                  </div>
                </div>
                <div class="mb-3 row">
                  <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                  <div class="col-sm-10">
                    <input type="password" class="form-control" id="inputPassword">
                  </div>
                </div>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
    </div>
    </div>
  </nav>
  <div class="mx-4"></div>
  </div>
  </div>
  </nav>
  <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" class="active"
        aria-current="true" aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" class="active"
        aria-current="true" aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="https://images.pexels.com/photos/1591060/pexels-photo-1591060.jpeg?auto=compress&cs=tinysrgb&w=1600"
          width="600px" height="700px" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h1>Welcome to Web</h1>
          <p>Technology News,Development,and Trends</p>
          <button type="button" class="btn btn-primary">TECHNOLOGY</button>
          <button type="button" class="btn btn-secondary">TECH. NEWS</button>
          <button type="button" class="btn btn-success">TRENDS</button>

        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://getwallpapers.com/wallpaper/full/6/7/c/1173072-widescreen-developer-wallpaper-hd-1920x1080.jpg"
          width="600px" height="700px" class="d-block w-100" alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h1>Welcome to Web </h1>
          <p>Technology News,Development,and Trends</p>
          <button type="button" class="btn btn-primary">TECHNOLOGY</button>
          <button type="button" class="btn btn-secondary">TECH. NEWS</button>
          <button type="button" class="btn btn-success">TRENDS</button>
        </div>
      </div>
      <div class="carousel-item">
        <img src="https://cdn.99images.com/photos/wallpapers/3d-abstract/computer%20android-iphone-desktop-hd-backgrounds-wallpapers-1080p-4k-bm522.jpg" width="600px" height="700px" class="d-block w-100"
          alt="...">
        <div class="carousel-caption d-none d-md-block">
          <h1>Welcome to Web</h1>
          <p>Technology News,Development,and Trends</p>
          <button type="button" class="btn btn-primary">TECHNOLOGY</button>
          <button type="button" class="btn btn-secondary">TECH. NEWS</button>
          <button type="button" class="btn btn-success">TRENDS</button>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <br>


  <div class="mx-4">
    <div class="row featurette">
        <div class="col-md-7">
            <h2 class="featurette-heading fw-normal lh-1">TECHnology <span class="text-muted">“Technology is best
                    when it brings people together.” ...

                </span></h2>
            <p class="lead">The core purpose of technology is meant to be an exchange of information, which is
                probably why 74% of consumers feel that technology helps to keep them better informed. Every piece
                of technology is meant to be a way to provide information, whether it be about news or your personal
                life, which is why technology is continuing to get “smarter” as it develops. If companies want to
                stay relevant, they should make sure that keep their consumers informed as they continue their
                technological advancements.

            </p>
        </div>
        <div class="col-md-5">
            <img src="https://images.wallpaperscraft.com/image/single/chip_circuit_processor_140251_300x168.jpg"
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500"
                height="500" alt="">

            <title>Placeholder</title>
            <rect width="100%" height="100%" fill="#eee"></rect><text x="50%" y="50%" fill="#aaa" dy=".3em"></text>
            </svg>

        </div>
    </div>
    <hr class="featurette-divider">
    <div class="row featurette">
        <div class="col-md-7 order-md-2">
            <h2 class="featurette-heading fw-normal lh-1">Coding<span class="text-muted">“Any fool can write code
                    that a computer can understand. Good programmers write code that humans can understand.” </span>
            </h2>
            <p class="lead">A key part in developing new technologies is making technologies easier to use on the
                go. Smartwatches are phones on your wrist, laptops are becoming more like tablets because they take
                up less space, and companies are creating apps so that you can shop on the go, which is making
                delivery and pick-up popular alternatives. These developments are rising because 64% of consumers
                enjoy the fact that technology gives them more freedom of mobility.

            </p>
        </div>
        <div class="col-md-5 order-md-1">
            <img src="https://c4.wallpaperflare.com/wallpaper/204/67/597/technics-design-technology-wallpaper-preview.jpg"
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500"
                height="500" role="img" aria-label="Placeholder: 500x500" preserveAspectRatio="xMidYMid slice"
                focusable="false" alt="">

            <rect width="100%" height="100%" fill="#eee"></rect><text x="50%" y="50%" fill="#aaa" dy=".3em"></text>
            </svg>

        </div>
    </div>
    <hr class="featurette-divider">
    <div class="row featurette">
        <div class="col-md-7">
            <h2 class="featurette-heading fw-normal lh-1">TECH. Trends <span class="text-muted"> “If it keeps up,
                    man will atrophy all his limbs but the push-button finger.”
                </span></h2>
            <p class="lead">Technology has developed so much even within the last 20 years alone that it is
                difficult to think of how we used to survive without it. From anything from streaming services to
                messaging applications to smart speakers to health trackers. New technologies are helping to create
                a better quality of life according to about two-thirds (64%) of consumers.

            </p>
        </div>
        <div class="col-md-5">
            <img src="https://c4.wallpaperflare.com/wallpaper/624/21/247/microsoft-windows-windows-10-technology-hi-tech-wallpaper-preview.jpg"
                class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500"
                height="500" alt="">

            <title>Placeholder</title>
            <rect width="100%" height="100%" fill="#eee"></rect><text x="50%" y="50%" fill="#aaa" dy=".3em"></text>
            </svg>

        </div>
    </div>
</div>


<br>
<br>
<br>
<br>
<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="home.html" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="about.html" class="nav-link px-2 text-muted">About</a></li>
      <li class="nav-item"><a href="topics.html" class="nav-link px-2 text-muted">Topics</a></li>
      <li class="nav-item"><a href="contactus.html" class="nav-link px-2 text-muted">Contact Us</a></li>

    </ul>
    <p class="text-center text-muted">© 2022 Web Company, Inc</p>
  </footer>
</div>





</body>

</html>


<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web</title>
    <link rel="shortcut icon" type="image/x-icon"
        href="https://www.nicepng.com/png/full/363-3634614_website-designing-web-logo.png">
    <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <!-- JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
        crossorigin="anonymous"></script>
</head>

<body>
    <nav class="navbar navbar-expand-lg bg-info">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <h2><b>Web</b></h2>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="blog.html"><b>Home</b></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html"><b>About</b></a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            <b>Topics</b>
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="technology.html">TECHNOLOGY</a></li>
                            <li><a class="dropdown-item" href="technews.html">TECH. NEWS</a></li>
                            <li><a class="dropdown-item" href="trends.html">TRENDS</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Support</a></li>
                            <li><a class="dropdown-item" href="#">Write for us</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contactus.html"><b>Contact Us</b></a>
                    </li>
                </ul>
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-success" type="submit">Search</button>
                </form>
                <div class="mx-2">
                    <!-- Button trigger modal -->
                    <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
                        Signup
                    </button>

                    <!-- Modal -->
                    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
                        aria-hidden="true">
                        <div class="modal-dialog">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <h5 class="modal-title" id="exampleModalLabel">Web Signup</h5>
                                    <button type="button" class="btn-close" data-bs-dismiss="modal"
                                        aria-label="Close"></button>
                                </div>
                                <div class="modal-body">
                                    <div class="mb-3 row">
                                        <label for="inputEmail" class="col-sm-2 col-form-label">Mobile no.</label>
                                        <div class="col-sm-10">
                                            <input type="text" class="form-control" id="inputEmail">
                                        </div>
                                        <div class="mb-3 row">
                                            <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
                                            <div class="col-sm-10">
                                                <input type="text" class="form-control" id="inputEmail">
                                            </div>
                                        </div>
                                        <div class="mb-3 row">
                                            <label for="inputEmail" class="col-sm-2 col-form-label"> re-enter
                                                Email</label>
                                            <div class="col-sm-10">
                                                <input type="text" class="form-control" id="inputEmail">
                                            </div>
                                        </div>
                                        <div class="mb-3 row">
                                            <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                                            <div class="col-sm-10">
                                                <input type="password" class="form-control" id="inputPassword">
                                            </div>
                                        </div>
                                        <div class="mb-3 row">
                                            <label for="inputPassword" class="col-sm-2 col-form-label"> confirm
                                                Password</label>
                                            <div class="col-sm-10">
                                                <input type="password" class="form-control" id="inputPassword">
                                            </div>

                                        </div>

                                        <div class="modal-footer">
                                            <button type="button" class="btn btn-secondary"
                                                data-bs-dismiss="modal">Close</button>
                                            <button type="button" class="btn btn-primary"
                                                data-bs-dismiss="modal">submit</button>

                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>



                    <!-- Button trigger modal -->
                    <button type="button" class="btn btn-primary" data-bs-toggle="modal"
                        data-bs-target="#cexampleModal">
                        Login

                    </button>

                    <!-- Modal -->
                    <div class="modal fade" id="cexampleModal" tabindex="-1" aria-labelledby="cexampleModalLabel"
                        aria-hidden="true">
                        <div class="modal-dialog">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <h5 class="modal-title" id="cexampleModalLabel">Web Login</h5>
                                    <button type="button" class="btn-close" data-bs-dismiss="modal"
                                        aria-label="Close"></button>
                                </div>
                                <div class="modal-body">
                                    <div class="mb-3 row">
                                        <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
                                        <div class="col-sm-10">
                                            <input type="text" class="form-control" id="staticEmail">
                                        </div>
                                    </div>
                                    <div class="mb-3 row">
                                        <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                                        <div class="col-sm-10">
                                            <input type="password" class="form-control" id="inputPassword">
                                        </div>
                                    </div>
                                </div>
                                <div class="modal-footer">
                                    <button type="button" class="btn btn-secondary"
                                        data-bs-dismiss="modal">Close</button>
                                    <button type="button" class="btn btn-primary"
                                        data-bs-dismiss="modal">submit</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" class="active"
                aria-current="true" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" class="active"
                aria-current="true" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://images.pexels.com/photos/1591060/pexels-photo-1591060.jpeg?auto=compress&cs=tinysrgb&w=1600"
                    width="600px" height="700px" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h1>Welcome to Web </h1>
                    <p>Technology News,Development,and Trends</p>
                    <button type="button" class="btn btn-primary">TECHNOLOGY</button>
                    <button type="button" class="btn btn-secondary">TECH. NEWS</button>
                    <button type="button" class="btn btn-success">TRENDS</button>

                </div>
            </div>
            <div class="carousel-item">
                <img src="https://getwallpapers.com/wallpaper/full/6/7/c/1173072-widescreen-developer-wallpaper-hd-1920x1080.jpg"
                    width="600px" height="700px" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h2>Welcome to Web Development</h2>
                    <p>Technology News,Development,and Trends</p>
                    <button type="button" class="btn btn-primary">TECHNOLOGY</button>
                    <button type="button" class="btn btn-secondary">TECH. NEWS</button>
                    <button type="button" class="btn btn-success">TRENDS</button>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://cdn.99images.com/photos/wallpapers/3d-abstract/computer%20android-iphone-desktop-hd-backgrounds-wallpapers-1080p-4k-bm522.jpg"
                    width="600px" height="700px" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                    <h2>Welcome to Web Development</h2>
                    <p>Technology News,Development,and Trends</p>
                    <button type="button" class="btn btn-primary">TECHNOLOGY</button>
                    <button type="button" class="btn btn-secondary">TECH. NEWS</button>
                    <button type="button" class="btn btn-success">TRENDS</button>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <br>


    <div class="mx-4">
        <div class="row featurette">
            <div class="col-md-7">
                <h2 class="featurette-heading fw-normal lh-1">TECHnology <span class="text-muted">“Technology is best
                        when it brings people together.” ...

                    </span></h2>
                <p class="lead">The core purpose of technology is meant to be an exchange of information, which is
                    probably why 74% of consumers feel that technology helps to keep them better informed. Every piece
                    of technology is meant to be a way to provide information, whether it be about news or your personal
                    life, which is why technology is continuing to get “smarter” as it develops. If companies want to
                    stay relevant, they should make sure that keep their consumers informed as they continue their
                    technological advancements.

                </p>
            </div>
            <div class="col-md-5">
                <img src="https://images.wallpaperscraft.com/image/single/chip_circuit_processor_140251_300x168.jpg"
                    class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500"
                    height="500" alt="">

                <title>Placeholder</title>
                <rect width="100%" height="100%" fill="#eee"></rect><text x="50%" y="50%" fill="#aaa" dy=".3em"></text>
                </svg>

            </div>
        </div>
        <hr class="featurette-divider">
        <div class="row featurette">
            <div class="col-md-7 order-md-2">
                <h2 class="featurette-heading fw-normal lh-1">Coding<span class="text-muted">“Any fool can write code
                        that a computer can understand. Good programmers write code that humans can understand.” </span>
                </h2>
                <p class="lead">A key part in developing new technologies is making technologies easier to use on the
                    go. Smartwatches are phones on your wrist, laptops are becoming more like tablets because they take
                    up less space, and companies are creating apps so that you can shop on the go, which is making
                    delivery and pick-up popular alternatives. These developments are rising because 64% of consumers
                    enjoy the fact that technology gives them more freedom of mobility.

                </p>
            </div>
            <div class="col-md-5 order-md-1">
                <img src="https://c4.wallpaperflare.com/wallpaper/204/67/597/technics-design-technology-wallpaper-preview.jpg"
                    class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500"
                    height="500" role="img" aria-label="Placeholder: 500x500" preserveAspectRatio="xMidYMid slice"
                    focusable="false" alt="">

                <rect width="100%" height="100%" fill="#eee"></rect><text x="50%" y="50%" fill="#aaa" dy=".3em"></text>
                </svg>

            </div>
        </div>
        <hr class="featurette-divider">
        <div class="row featurette">
            <div class="col-md-7">
                <h2 class="featurette-heading fw-normal lh-1">TECH. Trends <span class="text-muted"> “If it keeps up,
                        man will atrophy all his limbs but the push-button finger.”
                    </span></h2>
                <p class="lead">Technology has developed so much even within the last 20 years alone that it is
                    difficult to think of how we used to survive without it. From anything from streaming services to
                    messaging applications to smart speakers to health trackers. New technologies are helping to create
                    a better quality of life according to about two-thirds (64%) of consumers.

                </p>
            </div>
            <div class="col-md-5">
                <img src="https://c4.wallpaperflare.com/wallpaper/624/21/247/microsoft-windows-windows-10-technology-hi-tech-wallpaper-preview.jpg"
                    class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500"
                    height="500" alt="">

                <title>Placeholder</title>
                <rect width="100%" height="100%" fill="#eee"></rect><text x="50%" y="50%" fill="#aaa" dy=".3em"></text>
                </svg>

            </div>
        </div>
    </div>


    <br>
<br>
<br>
<br>
<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="home.html" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="about.html" class="nav-link px-2 text-muted">About</a></li>
      <li class="nav-item"><a href="topics.html" class="nav-link px-2 text-muted">Topics</a></li>
      <li class="nav-item"><a href="contactus.html" class="nav-link px-2 text-muted">Contact Us</a></li>

    </ul>
    <p class="text-center text-muted">© 2022 Web Company, Inc</p>
  </footer>
</div>

</body>

</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web</title>
    <link rel="shortcut icon" type="image/x-icon" href="https://www.nicepng.com/png/full/363-3634614_website-designing-web-logo.png" >
        <!-- CSS only -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
<!-- JavaScript Bundle with Popper -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa" crossorigin="anonymous"></script>
</head>

<body><nav class="navbar navbar-expand-lg bg-info">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><h2><b>Web</b></h2></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="home.html"><b>Home</b></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="blog.html"><b>About</b></a>
          </li>
          <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              <b>Topics</b>
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="technology.html">TECHNOLOGY</a></li>
              <li><a class="dropdown-item" href="technews.html">TECH. NEWS</a></li>
              <li><a class="dropdown-item" href="trends.html">TRENDS</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Support</a></li>
              <li><a class="dropdown-item" href="#">Write for us</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contactus.html"><b>Contact Us</b></a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-success" type="submit">Search</button>
        </form>
        <div class="mx-2">
                  <!-- Button trigger modal -->
                  <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
                    Signup
                  </button>
        
                  <!-- Modal -->
                  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
                    aria-hidden="true">
                    <div class="modal-dialog">
                      <div class="modal-content">
                        <div class="modal-header">
                          <h5 class="modal-title" id="exampleModalLabel">Web  Signup</h5>
                          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                          <div class="mb-3 row">
                            <label for="inputEmail" class="col-sm-2 col-form-label">Mobile no.</label>
                            <div class="col-sm-10">
                              <input type="text" class="form-control" id="inputEmail">
                            </div>
                          <div class="mb-3 row">
                            <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
                            <div class="col-sm-10">
                              <input type="text" class="form-control" id="inputEmail">
                            </div>
                          </div>
                          <div class="mb-3 row">
                            <label for="inputEmail" class="col-sm-2 col-form-label"> re-enter Email</label>
                            <div class="col-sm-10">
                              <input type="text" class="form-control" id="inputEmail">
                            </div>
                          </div>
                          <div class="mb-3 row">
                            <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                            <div class="col-sm-10">
                              <input type="password" class="form-control" id="inputPassword">
                            </div>
                          </div>
                          <div class="mb-3 row">
                            <label for="inputPassword" class="col-sm-2 col-form-label"> confirm Password</label>
                            <div class="col-sm-10">
                              <input type="password" class="form-control" id="inputPassword">
                            </div>
        
                          </div>
        
                          <div class="modal-footer">
                            <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                            <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>
        
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                </div>
        
        
        
                <!-- Button trigger modal -->
                <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#cexampleModal">
                  Login
        
                </button>
        
                <!-- Modal -->
                <div class="modal fade" id="cexampleModal" tabindex="-1" aria-labelledby="cexampleModalLabel"
                  aria-hidden="true">
                  <div class="modal-dialog">
                    <div class="modal-content">
                      <div class="modal-header">
                        <h5 class="modal-title" id="cexampleModalLabel">Web Login</h5>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                        <div class="mb-3 row">
                          <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
                          <div class="col-sm-10">
                            <input type="text" class="form-control" id="staticEmail">
                          </div>
                        </div>
                        <div class="mb-3 row">
                          <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                          <div class="col-sm-10">
                            <input type="password" class="form-control" id="inputPassword">
                          </div>
                        </div>
                      </div>
                      <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                        <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
      </div>
    </div>
  </nav>

  <div class="p-5 mb-4 bg-light rounded-3">
    <div class="container-fluid py-5">

      <h1 class="display-5 fw-bold">“Once a new technology rolls over you, if you're not part of the steamroller, you're part of the road.”
      </h1>
      <p class="col-md-8 fs-4">Although technology has made it easier to connect with those who are further away, it has possibly hurt the relationships of those nearby. How often have you been out with someone and the entire time they are on their phone texting someone else or are on social media? Over half of consumers (57%) believes that technology is lowering the quality of relationships by reducing personal interactions. As a business or organization, it is important to have in-person interactions with your customers frequently as to ensure a strong relationship.</p>

    </div>
  </div>

  <div class="row mb-2">
    <div class="col-md-6">
      <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
        <div class="col p-4 d-flex flex-column position-static">
          <strong class="d-inline-block mb-2 text-primary">WEB</strong>
          <h3 class="mb-0">TECHnology</h3>
          <div class="mb-1 text-muted">JULY 26</div>
          <p class="card-text mb-auto">“If future generations are to remember us more with gratitude than sorrow, we must achieve more than just the miracles of technology. We must also leave them a glimpse of the world as it was created, not just as it looked when we got through with it.”
          </p>

        </div>
        <div class="col-auto d-none d-lg-block">
          <img src="https://media.istockphoto.com/photos/businessman-using-a-computer-to-webinar-online-education-on-internet-picture-id1360520508?k=20&m=1360520508&s=612x612&w=0&h=hhvHdz0Wo_R_lJAvPw9sWLFVki6ahdn-DL70PQmDqLE="  class="bd-placeholder-img" width="300" height="250"alt="" role="img" aria-label="Placeholder: Thumbnail" preserveAspectRatio="xMidYMid slice" focusable="false">


        </div>
      </div>
    </div>
    <div class="col-md-6">
      <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
        <div class="col p-4 d-flex flex-column position-static">
          <strong class="d-inline-block mb-2 text-success">WEB</strong>
          <h3 class="mb-0">TECH. NEWS</h3>
          <div class="mb-1 text-muted">JULY 26</div>
          <p class="mb-auto"></p>
          <p class="mb-auto">NASA’s James Webb Space Telescope has delivered the deepest and sharpest infrared image of the distant universe so far. Webb’s First Deep Field is galaxy cluster SMACS 0723, and it is teeming with thousands of galaxies – including the faintest objects ever observed in the infrared.

          </p>

        </div>
        <div class="col-auto d-none d-lg-block">
          <img src="https://media.istockphoto.com/photos/delighted-software-developer-feeling-happy-while-making-a-projection-picture-id983955798?k=20&m=983955798&s=612x612&w=0&h=tB5u9a-BPkqo1Ywoj1Tn4DgJujWX-t6-d0hnMLrdCnI=" class="bd-placeholder-img" width="300" height="250" alt="">


        </div>
      </div>
    </div>
  </div>


  <br>
<br>
<br>
<br>
<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="home.html" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="about.html" class="nav-link px-2 text-muted">About</a></li>
      <li class="nav-item"><a href="topics.html" class="nav-link px-2 text-muted">Topics</a></li>
      <li class="nav-item"><a href="contactus.html" class="nav-link px-2 text-muted">Contact Us</a></li>

    </ul>
    <p class="text-center text-muted">© 2022 Web Company, Inc</p>
  </footer>
</div>
    
</body>
</html>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web</title>
    <link rel="shortcut icon" type="image/x-icon" href="https://www.nicepng.com/png/full/363-3634614_website-designing-web-logo.png" >
    <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
      integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <!-- JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
      crossorigin="anonymous"></script>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-info">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><h2><b>Web</b></h2></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="home.html"><b>Home</b></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="about.html"><b>About</b></a>
              </li>
              <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle active" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  <b>Topics</b>
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="technology.html">TECHNOLOGY</a></li>
                  <li><a class="dropdown-item" href="technews.html">TECH. NEWS</a></li>
                  <li><a class="dropdown-item" href="trends.html">TRENDS</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Support</a></li>
                  <li><a class="dropdown-item" href="#">Write for us</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="blog.html"><b>Contact Us</b></a>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-success" type="submit">Search</button>
            </form>
            <div class="mx-2">
                      <!-- Button trigger modal -->
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
            Signup
          </button>

          <!-- Modal -->
          <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
            aria-hidden="true">
            <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <h5 class="modal-title" id="exampleModalLabel">Web  Signup</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Mobile no.</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label"> re-enter Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label"> confirm Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>

                  </div>

                  <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>

                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
            </div>



        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#cexampleModal">
          Login

        </button>

        <!-- Modal -->
        <div class="modal fade" id="cexampleModal" tabindex="-1" aria-labelledby="cexampleModalLabel"
          aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="cexampleModalLabel">Web Login</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <div class="mb-3 row">
                  <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
                  <div class="col-sm-10">
                    <input type="text" class="form-control" id="staticEmail">
                  </div>
                </div>
                <div class="mb-3 row">
                  <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                  <div class="col-sm-10">
                    <input type="password" class="form-control" id="inputPassword">
                  </div>
                </div>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>
              </div>
            </div>
          </div>
        </div>
      </div>
          </div>
        </div>
      </nav>

      <br>


      <div class="row" data-masonry="{&quot;percentPosition&quot;: true }" style="position: relative; height: 1068px;">
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 0px;">
          <div class="card">
            <img src="https://thumbs.dreamstime.com/b/internet-information-technology-concept-laptop-computer-showing-data-processing-screen-122397310.jpg"class="bd-placeholder-img card-img-top" width="100%" height="240" alt="" role="img" aria-label="Placeholder: Card image" preserveAspectRatio="xMidYMid slice" focusable="false">

            <div class="card-body">
              <h5 class="card-title">Technology means</h5>
              <p class="card-text">Technology is the application of scientific knowledge to the practical aims of human life or, as it is sometimes phrased, to the change and manipulation of the human environment.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 0px;">
          <div class="card p-3">
            <figure class="p-3 mb-0">
              <blockquote class="blockquote">
                <p> “Just because something doesn’t do what you planned it to do doesn’t mean it’s useless.” ― Thomas Edison

                </p>
              </blockquote>

              
            </figure>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 201px;">
          <div class="card">
            <img src="https://thumbs.dreamstime.com/b/analytics-dashboard-information-technology-laptop-219153214.jpg" class="bd-placeholder-img card-img-top" width="80%" height="200" alt="" role="img" aria-label="Placeholder: Image cap" preserveAspectRatio="xMidYMid slice" focusable="false">


            <div class="card-body">
              <h5 class="card-title">Types of technologies</h5>
              <p class="card-text">There are three kinds of technological innovations such as the Semi- Radical, Incremental and Disruptive. This kind of technology typically relies on the existing knowledge about technology. However, it uses knowledge in such ways that it differs importantly into the past.</p>

            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 386px;">
          <div class="card text-bg-primary text-center p-3">
            <figure class="mb-0">
              <blockquote class="blockquote">
                <p>“It has become appallingly obvious that our technology has exceeded our humanity.” ― Albert Einstein

                </p>
              </blockquote>

            </figure>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 525px;">
          <div class="card text-center">
            <div class="card-body">
              <h5 class="card-title">Technology in daily uses of lifes</h5>
              <p class="card-text">Other examples of everyday electrical technology includes microwaves, hairdryers, phones, computers, tablets, toasters, dishwashers, refrigerators, washing machines, digital clocks, thermostats, and so many others.</p>
              <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 579px;">
          <div class="card">
            <img src="https://thumbs.dreamstime.com/b/information-technology-related-word-cloud-handwritten-bl-concept-blackboard-56028965.jpg" class="bd-placeholder-img card-img" width="100%" height="400" alt="" role="img" aria-label="Placeholder: Card image" preserveAspectRatio="xMidYMid slice" focusable="false">


          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 703px;">
          <div class="card p-3 text-end">
            <figure class="mb-0">
              <blockquote class="blockquote">
                <p> “Technology is nothing. What’s important is that you have a faith in people, that they’re basically good and smart, and if you give them tools, they’ll do wonderful things with them.” ― Steve Jobs

                </p>
              </blockquote>

            </figure>
          </div>
        </div>
        <br>

        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 842px;">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">How technologies change our lifes</h5>
              <p class="card-text">Modern technology has paved the way for multi-functional devices like the smartwatch and the smartphone. Computers are increasingly faster, more portable, and higher-powered than ever before. With all of these revolutions, technology has also made our lives easier, faster, better, and more fun.</p>
              <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
            </div>
          </div>
        </div>
      </div>

      <br>
<br>
<br>
<br>
<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="home.html" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="about.html" class="nav-link px-2 text-muted">About</a></li>
      <li class="nav-item"><a href="topics.html" class="nav-link px-2 text-muted">Topics</a></li>
      <li class="nav-item"><a href="contactus.html" class="nav-link px-2 text-muted">Contact Us</a></li>

    </ul>
    <p class="text-center text-muted">© 2022 Web Company, Inc</p>
  </footer>
</div>


    
</body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web</title>
    <link rel="shortcut icon" type="image/x-icon" href="https://www.nicepng.com/png/full/363-3634614_website-designing-web-logo.png" >
    <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
      integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <!-- JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
      crossorigin="anonymous"></script>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-info">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><h2><b>Web</b></h2></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="home.html"><b>Home</b></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="about.html"><b>About</b></a>
              </li>
              <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle active" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  <b>Topics</b>
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="technology.html">TECHNOLOGY</a></li>
                  <li><a class="dropdown-item" href="technews.html">TECH.NEWS</a></li>
                  <li><a class="dropdown-item" href="trends.html">TRENDS</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Support</a></li>
                  <li><a class="dropdown-item" href="#">Write for us</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="blog.html"><b>Contact Us</b></a>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-success" type="submit">Search</button>
            </form>
            <div class="mx-2">
                      <!-- Button trigger modal -->
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
            Signup
          </button>

          <!-- Modal -->
          <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
            aria-hidden="true">
            <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <h5 class="modal-title" id="exampleModalLabel">Web  Signup</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Mobile no.</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label"> re-enter Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label"> confirm Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>

                  </div>

                  <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>

                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
            </div>



        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#cexampleModal">
          Login

        </button>

        <!-- Modal -->
        <div class="modal fade" id="cexampleModal" tabindex="-1" aria-labelledby="cexampleModalLabel"
          aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="cexampleModalLabel">Web Login</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <div class="mb-3 row">
                  <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
                  <div class="col-sm-10">
                    <input type="text" class="form-control" id="staticEmail">
                  </div>
                </div>
                <div class="mb-3 row">
                  <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                  <div class="col-sm-10">
                    <input type="password" class="form-control" id="inputPassword">
                  </div>
                </div>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>
              </div>
            </div>
          </div>
        </div>
      </div>
          </div>
        </div>
      </nav>

      <br>



    
    <div class="row" data-masonry="{&quot;percentPosition&quot;: true }" style="position: relative; height: 1068px;">
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 0px;">
          <div class="card">
            <img src="https://thumbs.dreamstime.com/b/data-information-statistics-technology-analysis-concept-67826746.jpg" class="bd-placeholder-img card-img-top" width="80%" height="250"alt="">

            <div class="card-body">
              <h5 class="card-title"> Positive and Negative of Technology</h5>
              <p class="card-text">Positive effects of Technology. Less expense, better efficiency, communication channels, increase in networks, etc. Negative effects of Technology. Social isolation, job loss, adverse health effects, scams, etc.</p>
            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 0px;">
          <div class="card p-3">
            <figure class="p-3 mb-0">
              <blockquote class="blockquote">
                <p>“We are stuck with technology when what we really want is just stuff that works.” ― Douglas Adams

                </p>
              </blockquote>

            </figure>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 201px;">
          <div class="card">
            <img src="https://thumbs.dreamstime.com/b/cyber-security-data-protection-information-safety-encryption-internet-technology-business-concept-virtual-screen-padlock-105624804.jpg" class="bd-placeholder-img card-img-top" width="80%" height="200" alt="">

    
            <div class="card-body">
              <h5 class="card-title">Positive impact of technology on society</h5>
              <p class="card-text">Other ways technology is seen to have a positive effect on society include increased knowledge and understanding, improvements in industry and jobs and an interconnectedness of the world as a result of globalization.</p>

            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 386px;">
          <div class="card text-bg-primary text-center p-3">
            <figure class="mb-0">
              <blockquote class="blockquote">
                <p> “Man is a slow, sloppy, and brilliant thinker; computers are fast, accurate, and stupid.” ― John Pfeiffer</p>
              </blockquote>

            </figure>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 525px;">
          <div class="card text-center">
            <div class="card-body">
              <h5 class="card-title">Can technology save the world</h5>
              <p class="card-text">More people using digital devices for communicating and storing information means that there is less reliance on paper, which reduces deforestation. Since trees are an important source of oxygen and also absorb carbon dioxide, this further reduces climate change.</p>
>
            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 579px;">
          <div class="card">
            <img src="https://thumbs.dreamstime.com/b/futuristic-blue-user-interface-schematic-electronic-draft-server-room-information-communication-technology-background-template-165468397.jpg" class="bd-placeholder-img card-img-top" width="800%" height="400" alt="">

          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 703px;">
          <div class="card p-3 text-end">
            <figure class="mb-0">
              <blockquote class="blockquote">
                <p> “Technology is the knack of so arranging the world that we do not experience it.” ― Rollo May

                </p>
              </blockquote>

            </figure>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 842px;">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Is technology helpfull or harmfull</h5>
              <p class="card-text"> Technology is a part of our lives. It can have some negative effects, but it can also offer many positive benefits and play an important role in education, health, and general welfare.</p>
              <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
            </div>
          </div>
        </div>
      </div>

      <br>
<br>
<br>
<br>
<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="home.html" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="about.html" class="nav-link px-2 text-muted">About</a></li>
      <li class="nav-item"><a href="topics.html" class="nav-link px-2 text-muted">Topics</a></li>
      <li class="nav-item"><a href="contactus.html" class="nav-link px-2 text-muted">Contact Us</a></li>

    </ul>
    <p class="text-center text-muted">© 2022 Web Company, Inc</p>
  </footer>
</div>


    
</body>
</html>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web</title>
    <link rel="shortcut icon" type="image/x-icon" href="https://www.nicepng.com/png/full/363-3634614_website-designing-web-logo.png" >
    <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
      integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <!-- JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
      crossorigin="anonymous"></script>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-info">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><h2><b>Web</b></h2></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="home.html"><b>Home</b></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="about.html"><b>About</b></a>
              </li>
              <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle active" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  <b>Topics</b>
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="technology.html">TECHNOLOGY</a></li>
                  <li><a class="dropdown-item" href="technews.html">TECH.NEWS</a></li>
                  <li><a class="dropdown-item" href="trends.html">TRENDS</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Support</a></li>
                  <li><a class="dropdown-item" href="#">Write for us</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="blog.html"><b>Contact Us</b></a>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-success" type="submit">Search</button>
            </form>
            <div class="mx-2">
                      <!-- Button trigger modal -->
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
            Signup
          </button>

          <!-- Modal -->
          <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
            aria-hidden="true">
            <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <h5 class="modal-title" id="exampleModalLabel">Web  Signup</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Mobile no.</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label"> re-enter Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label"> confirm Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>

                  </div>

                  <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>

                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
            </div>



        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#cexampleModal">
          Login

        </button>

        <!-- Modal -->
        <div class="modal fade" id="cexampleModal" tabindex="-1" aria-labelledby="cexampleModalLabel"
          aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="cexampleModalLabel">Web Login</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <div class="mb-3 row">
                  <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
                  <div class="col-sm-10">
                    <input type="text" class="form-control" id="staticEmail">
                  </div>
                </div>
                <div class="mb-3 row">
                  <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                  <div class="col-sm-10">
                    <input type="password" class="form-control" id="inputPassword">
                  </div>
                </div>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>
              </div>
            </div>
          </div>
        </div>
      </div>
          </div>
        </div>
      </nav>
      <br>


      <div class="row" data-masonry="{&quot;percentPosition&quot;: true }" style="position: relative; height: 1068px;">
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 0px;">
          <div class="card">
            <img src="https://enterprisetalk.com/wp-content/uploads/2019/09/Five-Emerging-Tech-Trends-for-2020-696x392.jpg" class="bd-placeholder-img card-img-top" width="80%" height="200" alt="">

            <div class="card-body">
              <h5 class="card-title">Technology importance</h5>
              <p class="card-text">Information technology is important in our lives because it helps to deal with every day's dynamic things. Technology offers various tools to boost development and to exchange information. Both these things are the objective of IT to make tasks easier and to solve many problems.
              </p>
            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 0px;">
          <div class="card p-3">
            <figure class="p-3 mb-0">
              <blockquote class="blockquote">
                <p>“Technology is a useful servant but a dangerous master.” ― Christian Lous Lange

                </p>
              </blockquote>
              
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 201px;">
          <div class="card">
            <img src="https://www.eletimes.com/wp-content/uploads/2022/01/istockphoto-1271150287-170667a.jpg" class="bd-placeholder-img card-img-top" width="80%" height="200" alt="">

            <div class="card-body">
              <h5 class="card-title">Technology in future</h5>
              <p class="card-text">It can invite unique perspectives. It can provide empowerment, knowledge, awareness, access, and community. As we develop the technology of the future, we can work towards creating a better world long term. This means many different things as technology merges with all parts of our lives</p>

            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 386px;">
          <div class="card text-bg-primary text-center p-3">
            <figure class="mb-0">
              <blockquote class="blockquote">
                <p>“Science and technology revolutionize our lives, but memory, tradition, and myth frame our response.” ― Arthur Schlesinger

                </p>
              </blockquote>

            </figure>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 525px;">
          <div class="card text-center">
            <div class="card-body">
              <h5 class="card-title">Technology changing the world</h5>
              <p class="card-text">Modern technology has paved the way for multi-functional devices like the smartwatch and the smartphone. Computers are increasingly faster, more portable, and higher-powered than ever before. With all of these revolutions, technology has also made our lives easier, faster, better, and more fun.</p>
              
            </div>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 50%; top: 579px;">
          <div class="card">
            <img src="https://miro.medium.com/max/1400/1*J2HkyOiYbQdQ6BEbUQFEwg.jpeg" class="bd-placeholder-img card-img-top" width="80%" height="400"alt="">

          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 703px;">
          <div class="card p-3 text-end">
            <figure class="mb-0">
              <blockquote class="blockquote">
                <p>“I might love my e-reader, but I’d never pass up the chance to browse real books.” ― Nichole Chase</p>
              </blockquote>

            </figure>
          </div>
        </div>
        <div class="col-sm-6 col-lg-4 mb-4" style="position: absolute; left: 0%; top: 842px;">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Positive effect of technology</h5>
              <p class="card-text">Better time management thanks to productivity apps. Improved health thanks to easy access to fitness routine, biometric devices, and diet management software. Easier and cheaper communication with friends and family. Increased job opportunities due to the introduction of remote working.</p>
              <p class="card-text"><small class="text-muted">Last updated 2 mins ago</small></p>
            </div>
          </div>
        </div>
      </div>


      <br>
<br>
<br>
<br>
<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="home.html" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="about.html" class="nav-link px-2 text-muted">About</a></li>
      <li class="nav-item"><a href="topics.html" class="nav-link px-2 text-muted">Topics</a></li>
      <li class="nav-item"><a href="contactus.html" class="nav-link px-2 text-muted">Contact Us</a></li>

    </ul>
    <p class="text-center text-muted">© 2022 Web Company, Inc</p>
  </footer>
</div>

</body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web</title>
    <link rel="shortcut icon" type="image/x-icon" href="https://www.nicepng.com/png/full/363-3634614_website-designing-web-logo.png" >
    <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <!-- JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa" crossorigin="anonymous"></script>
    </head>
<body>
    <nav class="navbar navbar-expand-lg bg-info">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><h2><b>Web</b></h2></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="home.html"><b>Home</b></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="about.html"><b>About</b></a>
              </li>
              <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  <b>Topics</b>
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="technology.html">TECHNOLOGY</a></li>
                  <li><a class="dropdown-item" href="technews.html">TECH.NEWS</a></li>
                  <li><a class="dropdown-item" href="trends.html">TRENDS</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Support</a></li>
                  <li><a class="dropdown-item" href="#">Write for us</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link active" href="blog.html"><b>Contact Us</b></a>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-success" type="submit">Search</button>
            </form>
            <div class="mx-2">
                      <!-- Button trigger modal -->
          <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
            Signup
          </button>

          <!-- Modal -->
          <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
            aria-hidden="true">
            <div class="modal-dialog">
              <div class="modal-content">
                <div class="modal-header">
                  <h5 class="modal-title" id="exampleModalLabel">Web  Signup</h5>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Mobile no.</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label">Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputEmail" class="col-sm-2 col-form-label"> re-enter Email</label>
                    <div class="col-sm-10">
                      <input type="text" class="form-control" id="inputEmail">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>
                  </div>
                  <div class="mb-3 row">
                    <label for="inputPassword" class="col-sm-2 col-form-label"> confirm Password</label>
                    <div class="col-sm-10">
                      <input type="password" class="form-control" id="inputPassword">
                    </div>

                  </div>

                  <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>

                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
            </div>



        <!-- Button trigger modal -->
        <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#cexampleModal">
          Login

        </button>

        <!-- Modal -->
        <div class="modal fade" id="cexampleModal" tabindex="-1" aria-labelledby="cexampleModalLabel"
          aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h5 class="modal-title" id="cexampleModalLabel">Web Login</h5>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
              </div>
              <div class="modal-body">
                <div class="mb-3 row">
                  <label for="staticEmail" class="col-sm-2 col-form-label">Email</label>
                  <div class="col-sm-10">
                    <input type="text" class="form-control" id="staticEmail">
                  </div>
                </div>
                <div class="mb-3 row">
                  <label for="inputPassword" class="col-sm-2 col-form-label">Password</label>
                  <div class="col-sm-10">
                    <input type="password" class="form-control" id="inputPassword">
                  </div>
                </div>
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary" data-bs-dismiss="modal">submit</button>
              </div>
            </div>
          </div>
        </div>
      </div>
          </div>
        </div>
      </nav>
      <div class="my-4">
        <div class="mx-6">

        <br>
        <br>
  
        <div class="row">
          <div class="col">
              <label for="first name" class="form-label">First Name</label>
  
            <input type="text" class="form-control" placeholder="First name" aria-label="First name">
          </div>
          <div class="col">
              <label for="last name" class="form-label">Last Name</label>
  
            <input type="text" class="form-control" placeholder="Last name" aria-label="Last name">
          </div>
        </div>
  
        <br>
        <div class="mb-3">
            <label for="mobilenoInput1" class="form-label">Mobile no.</label>
            <input type="number" class="form-control" id="exampleFormControlInput1" placeholder="0123456789">
          </div>
          <br>
        
  
        <div class="mb-3">
          <label for="exampleFormControlInput1" class="form-label">Email address</label>
          <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
        </div>
        <br>
  

  
  <br>
  
        <div class="mb-3">
          <label for="exampleFormControlTextarea1" class="form-label">Comment or Message</label>
          <textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Comment or Message" rows="3"></textarea>
        </div>
         <button  type="button" class="btn btn-primary" data-bs-dismiss="modal">Submit</button>
  
        </div>
      </div>
    </div>
<br>
<br>
<br>
<br>
<div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="home.html" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="about.html" class="nav-link px-2 text-muted">About</a></li>
      <li class="nav-item"><a href="topics.html" class="nav-link px-2 text-muted">Topics</a></li>
      <li class="nav-item"><a href="contactus.html" class="nav-link px-2 text-muted">Contact Us</a></li>

    </ul>
    <p class="text-center text-muted">© 2022 Web Company, Inc</p>
  </footer>
</div>
    
</body>
</html>
