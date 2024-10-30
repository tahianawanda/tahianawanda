<h1 align="center">Hola, soy Tahiana Wanda D' Astolfo <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>



## <picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 50px></picture> About me

<picture><img align="right" src="https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/Right_Side.gif?raw=true" width = 250px></picture>

<br><br>
```php
<?php

class Bio {
    private $data;

    public function __construct() {
        $this->data = [
            "- ⚡ Breve biografía:"                    => "Una especie de híbrido entre metalero-synthWave-cyberPunk-melómano-adicto a los equipos-músico amateur-viajero-amante de la comida-gamer-programador-amante de los gatos-aficionado a los deportes",
            "- 🔭 Actualmente trabajando en:"          => "Tredicom como Desarrollador de Software Senior --- UAdeC como Profesor de Medio Tiempo",
            "- 🌱 Actualmente aprendiendo:"            => "Golang, MongoDB, RabbitMQ, K8s, GCP (Tecnologías de mi empresa) --- Mejorando mis habilidades en Front End para el stack MERN (Objetivo personal)",
            "- 👯 Busco colaborar en:"                 => "Proyectos relacionados con Python, Golang y Docker",
            "- 🤔 Busco ayuda con:"                    => "Cualquier cosa relacionada con lo que estoy aprendiendo actualmente 😅",
            "- 💬 Pregúntame sobre:"                   => "Python, PHP, Laravel, SQL, Diseño y Arquitectura de Software, Desarrollo Web y SEO",
            "- 📫 Cómo contactarme:"                   => "https://github.com/AnhellO#you-can-reach-me-at-alien",
        ];
    }

    public function getBio() {
        return $this->data;
    }
}

function main() {
    $bio = new Bio();
    foreach ($bio->getBio() as $key => $value) {
        echo "$key: $value\n";
    }
}

main();
?>

```
<h2 align="center">Lenguajes y otras tecnologias</h1>
