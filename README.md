body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #140c35;
        }
        header {
            background-color: #000;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h2 {
            margin: 0;
            font-size: 2.5em;
        }

        /* Contenedor principal del carrusel */
        .carousel {
            width: 100%;
            height: auto; /* Deja que el alto sea ajustado a las imágenes */
            max-height: 450px; /* Controla el tamaño máximo en altura */
            position: relative;
            overflow: hidden;
            border-radius: 0%;
        }

        /* Contenedor de imágenes */
        .carousel-images {
            display: flex;
            transition: transform 0.5s ease;
        }

        /* Estilo de cada imagen */
        .carousel-images img {
            width: 100%; /* Imagen ocupa todo el carrusel */
            flex-shrink: 0;
        }

        /* Flechas de navegación */
        .arrow {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background-color: rgba(0, 0, 0, 0.5);
            color: white;
            border: none;
            font-size: 24px;
            cursor: pointer;
            padding: 10px;
            border-radius: 50%;
            z-index: 10;
        }

        .arrow-left {
            left: 10px;
        }

        .arrow-right {
            right: 10px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: inline-block;
        }
        nav a:hover {
            background-color: #0d6b88;
        }
        .hero {
            background-image: url('https://www.yamaha.com/themes/common/images/default.jpg'); /* Cambia la URL por una imagen de Yamaha */
            background-size: cover;
            background-position: center;
            height: 400px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .hero h2 {
            font-size: 2.5em;
            margin: 0;
        }
        .section {
            padding: 20px;
            text-align: center;
        }
        .section h2 {
            margin-bottom: 15px;
        }

        .navigation {
            position: fixed; /* Fija el menú en la parte superior */
            top: 0; /* Asegura que esté en la parte superior */
            left: 0; /* Asegura que esté alineado a la izquierda */
            width: 100%; /* Ocupa todo el ancho de la pantalla */
            background-color: #032852; /* Color de fondo del menú */
            padding: 10px 10px; /* Espaciado dentro del menú */
            z-index: 1000; /* Asegura que el menú esté por encima de otros elementos */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2); /* Sombras opcionales para el menú */
            display: flex;
            justify-content: flex-start;
            align-items: left;
        }
    
        .navigation a {
            color: white;
            text-decoration: none;
            margin-right: 0px;
        }
        
        .navigation img {
            width: 40px; /* Ajusta el tamaño del logo */
        }
        
        .search-form {
            display: flex;
            align-items: center;
        }
        
        .search-form input {
            padding: 5px;
            border: 3px solid #01a6c4;
            border-radius: 5px;
            margin-left: 10px;
        }
        
        .search-form label {
            font-size: 20px;
            color: rgb(255, 255, 255);
            cursor: pointer;
            margin-left: 5px;
        }

        footer {
            background-color: #000;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        /* Estilos para el footer */
.footer {
    background-color: #032852;  /* Fondo oscuro */
    color: white;
    padding: 40px 20px;
    font-family: Arial, sans-serif;
    text-align: center;
}

.footer-content {
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
}

.footer-logo img {
    width: 100px; /* Tamaño ajustable del logo */
}

.footer-links {
    margin: 20px;
}

.footer-links a {
    color: white;
    text-decoration: none;
    margin: 0 10px;
    font-size: 16px;
    transition: color 0.3s;
}

.footer-links a:hover {
    color: #0d6b88; /* Color de hover */
}

.footer-socials {
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

.social-icon {
    color: white;
    font-size: 20px;
    margin: 0 15px;
    transition: color 0.3s;
}

.social-icon:hover {
     color: #0d6b88;/* Color de hover */
}

.footer-bottom {
    margin-top: 20px;
    font-size: 14px;
}

.footer-bottom p {
    margin: 0;
}
