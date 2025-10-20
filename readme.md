# Buenas, soy Mss Munroe :wave:

![Banner](./banner.jpeg)

💻 Programadora y amante del café ☕ | Explorando mi código

## About me

- :student: Estudiante de Grado Superior DAM
- :pencil2: Aprendiendo idiomas y lenguajes de programación nuevos
- :top: **PEAK** en mi vida: dibujo + lectura
- :jack_o_lantern: Pensando en Halloween
- :joystick: Trabajando en 'Bosquea'

## Technologies

![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)


## :alien: Top Code:  *Cifrado César*


> En criptografía, el cifrado César, también conocido como cifrado por
> desplazamiento, código de César o desplazamiento de César, es una
> de las técnicas de codificación más simples y más usadas. Es un tipo
> de cifrado por sustitución en el que una letra en el texto original es
> reemplazada por otra letra que se encuentra un número fijo de
> posiciones más adelante en el alfabeto. Por ejemplo, con un
> desplazamiento de 3, la A sería sustituida por la D (situada 3 lugares
> a la derecha de la A), la B sería reemplazada por la E, etc. Para las
> últimas letras se vuelve al principio. Este Programa debe su nombre a
> Julio César, que lo usaba para comunicarse con sus generales.


```java
    // MAIN
    System.out.println("Introduce una frase: ");
    String frase = entrada.nextLine();

    System.out.println("¿Que desplazamiento quieres aplicar?");
    int desplaza = entrada.nextInt();
    ...

    //FUNCIÓN PARA ENCRIPTAR

    String codigocesar = "";
    for (int i = 0; i < origen.length(); i++) {

        char letra = origen.charAt(i);
        int posicion = (int)letra;

        if (letra==' ') {
            codigocesar= codigocesar+" ";
            continue;
        }
        if (posicion+desplazamiento>122) {
            posicion=(posicion+desplazamiento)-122;
            letra = (char)(96+posicion);
        } else {
            letra = (char)(posicion+desplazamiento); }
        codigocesar = codigocesar+letra; }
    return codigocesar;

    //FUNCIÓN PARA DESENCRIPTAR

    String desencriptado = "";
    for (int i = 0; i < codigo.length(); i++) {

        char letra = codigo.charAt(i);
        int posicion = (int)letra;

        if (letra==' ') {
            desencriptado= desencriptado+" ";
            continue;
        }
        if (posicion-desplazamiento<97) {
            posicion=(96-posicion);
            letra = (char)(122-posicion);
        } else {
            letra = (char)(posicion-desplazamiento); }
        desencriptado = desencriptado+letra; }
    return desencriptado;
```


## :dizzy: Featured Project

-  :clapper: [Frame a Movie](https://github.com/MssMunroe/FrameAMovie): Web para descubrir películas y compartir opiniones en comunidad.

## :zap: Fun facts

- Me inspiro con bandas sonoras mientras programo
- Soy fan de las historias raras y los mundos cinematográficos  
- Obsesionada con Satoru


## :bulb: Mis estadísticas

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=MssMunroe&show_icons=true&theme=radical)
![Streak](https://github-readme-streak-stats.herokuapp.com?user=MssMunroe&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=MssMunroe&layout=compact&theme=radical)
[![Trophies](https://github-profile-trophy.vercel.app/?username=MssMunroe&theme=onedark&margin-w=15)](https://github.com/ryo-ma/github-profile-trophy)


![Banner](./banner2.gif)