<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
        crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet">
    <title>Ejemplo estilización</title>
    <style>
        body {
            font-family: 'Lobster', cursive;
        }

        .container {
            border: solid 5px;
            -webkit-border-radius: 40px 10px;
            border-radius: 40px 10px;
            -webkit-box-shadow: 44px -4px 52px 4px rgba(0, 0, 0, 0.75);
            -moz-box-shadow: 44px -4px 52px 4px rgba(0, 0, 0, 0.75);
            box-shadow: 44px -4px 52px 4px rgba(0, 0, 0, 0.75);
            padding: 20px;
        }

        .degradado {
            background: rgba(113, 239, 205, 1);
            background: -moz-linear-gradient(left, rgba(113, 239, 205, 1) 0%, rgba(113, 239, 205, 1) 35%, rgba(34, 226, 169, 1) 46%, rgba(189, 224, 148, 1) 73%, rgba(189, 224, 148, 1) 100%);
            background: -webkit-gradient(left top, right top, color-stop(0%, rgba(113, 239, 205, 1)), color-stop(35%, rgba(113, 239, 205, 1)), color-stop(46%, rgba(34, 226, 169, 1)), color-stop(73%, rgba(189, 224, 148, 1)), color-stop(100%, rgba(189, 224, 148, 1)));
            background: -webkit-linear-gradient(left, rgba(113, 239, 205, 1) 0%, rgba(113, 239, 205, 1) 35%, rgba(34, 226, 169, 1) 46%, rgba(189, 224, 148, 1) 73%, rgba(189, 224, 148, 1) 100%);
            background: -o-linear-gradient(left, rgba(113, 239, 205, 1) 0%, rgba(113, 239, 205, 1) 35%, rgba(34, 226, 169, 1) 46%, rgba(189, 224, 148, 1) 73%, rgba(189, 224, 148, 1) 100%);
            background: -ms-linear-gradient(left, rgba(113, 239, 205, 1) 0%, rgba(113, 239, 205, 1) 35%, rgba(34, 226, 169, 1) 46%, rgba(189, 224, 148, 1) 73%, rgba(189, 224, 148, 1) 100%);
            background: linear-gradient(to right, rgba(113, 239, 205, 1) 0%, rgba(113, 239, 205, 1) 35%, rgba(34, 226, 169, 1) 46%, rgba(189, 224, 148, 1) 73%, rgba(189, 224, 148, 1) 100%);
            filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#71efcd', endColorstr='#bde094', GradientType=1);
        }
        .degradado2 {
            background: rgba(240,47,23,1);
            background: -moz-linear-gradient(left, rgba(240,47,23,1) 0%, rgba(240,47,23,1) 24%, rgba(15,98,161,1) 59%, rgba(246,41,12,1) 61%, rgba(242,242,8,1) 66%, rgba(241,111,92,1) 89%, rgba(241,111,92,1) 100%);
            background: -webkit-gradient(left top, right top, color-stop(0%, rgba(240,47,23,1)), color-stop(24%, rgba(240,47,23,1)), color-stop(59%, rgba(15,98,161,1)), color-stop(61%, rgba(246,41,12,1)), color-stop(66%, rgba(242,242,8,1)), color-stop(89%, rgba(241,111,92,1)), color-stop(100%, rgba(241,111,92,1)));
            background: -webkit-linear-gradient(left, rgba(240,47,23,1) 0%, rgba(240,47,23,1) 24%, rgba(15,98,161,1) 59%, rgba(246,41,12,1) 61%, rgba(242,242,8,1) 66%, rgba(241,111,92,1) 89%, rgba(241,111,92,1) 100%);
            background: -o-linear-gradient(left, rgba(240,47,23,1) 0%, rgba(240,47,23,1) 24%, rgba(15,98,161,1) 59%, rgba(246,41,12,1) 61%, rgba(242,242,8,1) 66%, rgba(241,111,92,1) 89%, rgba(241,111,92,1) 100%);
            background: -ms-linear-gradient(left, rgba(240,47,23,1) 0%, rgba(240,47,23,1) 24%, rgba(15,98,161,1) 59%, rgba(246,41,12,1) 61%, rgba(242,242,8,1) 66%, rgba(241,111,92,1) 89%, rgba(241,111,92,1) 100%);
            background: linear-gradient(to right, rgba(240,47,23,1) 0%, rgba(240,47,23,1) 24%, rgba(15,98,161,1) 59%, rgba(246,41,12,1) 61%, rgba(242,242,8,1) 66%, rgba(241,111,92,1) 89%, rgba(241,111,92,1) 100%);
            filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f02f17', endColorstr='#f16f5c', GradientType=1 );

        }

        .img-container>img {
            max-width: 100%;
        }
    </style>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
            aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home
                        <span class="sr-only">(current)</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="https://google.com">Busca otra cosa</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true"
                        aria-expanded="false">
                        Dropdown
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">Action</a>
                        <a class="dropdown-item" href="#">Another action</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">Something else here</a>
                    </div>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#">Disabled</a>
                </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
            </form>
        </div>
    </nav>
    <div class="container degradado">
        <h1>ejemplo web estilizada con lorem ipsum</h1>
        <div class="row">
            <div class="col-4">
                <p>On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized
                    by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and
                    trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness
                    of will, which is the same as saying through shrinking from toil and pain. These cases are perfectly
                    simple and easy to distinguish. In a free hour, when our power of choice is untrammelled and when nothing
                    prevents our being able to do what we like best, every pleasure is to be welcomed and every pain avoided.
                    But in certain circumstances and owing to the claims of duty or the obligations of business it will frequently
                    occur that pleasures have to be repudiated and annoyances accepted. The wise man therefore always holds
                    in these matters to this principle of selection: he rejects pleasures to secure other greater pleasures,
                    or else he endures pains to avoid worse pains.</p>
            </div>
            <div class="col-5">
                <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti
                    atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique
                    sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum
                    facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil
                    impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus.
                    Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates
                    repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut
                    aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.</p>
            </div>
            <p>
                At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti
                quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa
                qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et
                expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus
                id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus
                autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae
                sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus
                maiores alias consequatur aut perferendis doloribus asperiores repellat.
            </p>
        </div>
    </div>
    <div class="container degradado2">
        <h1>ejemplo web estilizada con lorem ipsum</h1>
        <div class="row">
            <div class="col-4">
                <p>Ningún otro acontecimiento deportivo logra captar la atención del mundo como lo hace la Copa Mundial de la FIFA.
                    Desde su primera edición, celebrada en Uruguay en 1930, la competición de la FIFA por excelencia no ha dejado de crecer en prestigio y popularidad.
                    La singular idea de hacer que las mejores selecciones del planeta compitiesen por el título de campeonas del mundo fue posible gracias a un grupo de visionarios administradores futbolísticos franceses, dirigidos en 1920 por el innovador Jules Rimet. El trofeo original, de oro, recibió el nombre de Jules Rimet y se disputó tres veces en la década de los 30, antes de que la Segunda Guerra Mundial interrumpiese la competición durante doce años.
                    Tras su reanudación, la Copa Mundial progresó con rapidez hasta adquirir su indiscutible condición de mayor acontecimiento deportivo, de una única disciplina, del mundo moderno. Disputada en Europa y en América sucesivamente desde 1958, la Copa Mundial marcó un nuevo hito cuando, en mayo de 1996, el Comité Ejecutivo de la FIFA decidió que la edición de 2002 fuese organizada conjuntamente por Corea y Japón.
                    Desde 1930, los 16 torneos sólo han tenido siete campeones distintos. No obstante, la Copa Mundial se ha visto marcada por momentos sorprendentes que han contribuido a escribir la historia del fútbol, como el triunfo de Estados Unidos sobre Inglaterra en 1950, la derrota de Italia ante Corea del Norte en 1966, el ascenso de Camerún en los años 80 o su victoria sobre Argentina, defensora del título, en el primer partido de la edición de 1990.
                    En la actualidad, la Copa Mundial consigue hipnotizar a todo el público del planeta. El torneo celebrado en Francia en 1998 logró una audiencia global de más de 3.700 millones de personas, de las cuales aproximadamente 1.300 millones siguieron la final. Más de 2,7 millones de espectadores acudieron a presenciar los 64 partidos disputados en los estadios franceses.
                    Sin embargo, tras todos estos años y después de todos los cambios que se han producido, el centro de atención de la Copa Mundial de la FIFA sigue siendo el mismo: el reluciente trofeo de oro, que encarna las aspiraciones de cualquier futbolista.</p>
            </div>
            <div class="col-8 img-container">
                    <img src="https://www.eluniverso.com/sites/default/files/styles/powgallery_800/public/fotos/2018/04/mundial-rusia-2018-el-universo.jpg?itok=EBNNVs9K" alt="">
            </div>
            <p>
                Si quieres saber mas informacion de lo que esta pasando a pocos dias del mundial,
                la tabla de los grupos , y ademas todas las novedades en el mismo tiempo de mundial da clic 
                en donde dice Clic aqui y te enviara a la pagina oficial del mundial de ¡RUSIA2018!
            </p>

            <a href="https://es.fifa.com/worldcup/">Clic aquí</a>
        </div>
    </div>

    

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
        crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T"
        crossorigin="anonymous"></script>
</body>

</html>
