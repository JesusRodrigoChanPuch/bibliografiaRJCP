<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./css/styles.css">
    <link rel="stylesheet" href="fonts/style.css">
    <!-- link de CDN de iconos de bootstrap -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css">
    <title>Bibliografia JesúsChan</title>
</head>

<body>
    <div class="container">
        <div class="containerPartOne">
            <!-- <div class="image" style="background-image: url(img/RemGato.jpg);"></div> -->
            <div class="containerImg">
                <img src="img/RemGato.jpg" class="image" alt="Foto de perfil">
            </div>
            <div class="text">
                <h1 class="">Hola, Mi nombre es Jesus Rodrigo Chan Puch</h1>
                <h3>Soy estudiante en Ingenieria, soy mexicano,de la ciudad de Bacalar Quintana Roo </h3>
            </div>
            <a href="">
            </a>
            <div class="containerBottons">
                <a href="#AboutMe">
                    <div class="bottonpartOne">
                        About Me
                    </div>
                </a>
                <a href="#Proyects">
                    <div class="bottonpartOne">
                        Proyects
                    </div>
                </a>
                <a href="#Services">
                    <div class="bottonpartOne">
                        Services
                    </div>
                </a>
                <a href="#contactMe">
                    <div class="bottonpartOne">
                        Contact Me
                    </div>
                </a>

            </div>
        </div>
        <div class="containerAboutMe">
            <a name="AboutMe">
                <h1>About Me</h1>
            </a>
        </div>
        <div class="containerProyects">
            <a name="Proyects">
                <h1>Proyects</h1>
            </a>
        </div>
        <div class="containerServices">
            <a name="Services">
                <h1>Services</h1>
            </a>
        </div>
        <section id="contact">
            <h1> <a name="contactMe">Contact Me</a></h1>
            <div class="contact-wrapper">
                <!--  contact page -->
                <form id="contact-form" class="form-horizontal" role="form">

                    <div class="form-group">
                        <div class="col-sm-12">
                            <input type="text" class="form-control" id="name" placeholder="NAME" name="name" value=""
                                required>
                        </div>
                    </div>

                    <div class="form-group">
                        <div class="col-sm-12">
                            <input type="email" class="form-control" id="email" placeholder="EMAIL" name="email"
                                value="" required>
                        </div>
                    </div>

                    <textarea class="form-control" rows="10" placeholder="MESSAGE" name="message" required></textarea>

                    <button class="btn btn-primary send-button" id="submit" type="submit" value="SEND">
                        <div class="alt-send-button">
                            <i class="fa fa-paper-plane"></i><span class="send-text">SEND</span>
                        </div>

                    </button>

                </form>
                <!-- Left contact page -->

                <div class="direct-contact-container">

                    <ul class="contact-list">
                        <li class="list-item"><i class="fa fa-map-marker fa-2x"><span class="contact-text place">City,
                                    State</span></i></li>

                        <li class="list-item"><i class="fa fa-phone fa-2x"><span class="contact-text phone"><a
                                        href="tel: +52 983-133-04-91" title="Give me a call">(+52)
                                        983-133-04-91</a></span></i></li>

                        <li class="list-item"><i class="fa fa-envelope fa-2x"><span class="contact-text gmail"><a
                                        href="mailto:chanrodrigo8@gmail.com"
                                        title="Send me an email">chanrodrigo8@gmail.com</a></span></i></li>

                    </ul>

                    <hr>
                    <ul class="social-media-list">
                        <li><a href="#" class="contact-icon">
                                <i class="bi bi-github" aria-hidden="true"></i></a>
                        </li>
                        <li><a href="#" class="contact-icon">
                                <i class="bi bi-twitter" aria-hidden="true"></i></a>
                        </li>
                        <li><a href="#" target="_blank" class="contact-icon">
                                <i class="fa bi-instagram" aria-hidden="true"></i></a>
                        </li>
                    </ul>
                    <hr>

                    <div class="copyright">&copy; ALL OF THE RIGHTS RESERVED</div>

                </div>
            </div>
        </section>

    </div>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cabin:ital,wght@1,700&family=Hind:wght@300&display=swap');
        /* CDN de bootstrap */
        @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css");
    </style>
</body>

</html>