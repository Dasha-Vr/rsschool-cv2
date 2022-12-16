 # DARIA SHELUDYAKOVA
 ## CONTACTS:
 ## ABOUT ME:
 ## SKILLS:
 ## CODE EXAMPLE:
 ## WORK EXPERIENCE:
 ## EDUCATION
 ## ENGLISH:

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style.css" type="text/css" rel="stylesheet">
    <link href="normalize.css" type="text/css" rel="stylesheet">
    <link rel="icon" href="Smiley.ico">
    <title>CV</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;500;700&display=swap" rel="stylesheet">
</head>

<body>
    <header class="header">
        <div class="container">
            <nav class="navigation">
                <ul class="list">
                    <li class="menu">Contacts</li>
                    <li class="menu">About me</li>
                    <li class="menu"><a href="#skills">Skills</a></li>
                    <li class="menu">Code example</li>
                    <li class="menu">Education</li>
                    <li class="menu">English</li>
                </ul>
            </nav>
        </div>
    </header>
    <main class="main">
        <div class="container">
            <section class="photo-and-name">
                <div class="photo-name">
                    <img class="photo" src="image.jpg" alt="photo">
                    <div class="name-subtitle">
                        <h1 class="name">Daria Sheludiakova</h1>
                        <h4 class="subtitle">student</h4>
                    </div>
                </div>
            </section>
            <section class="contacts-and-about">
                <div class="contacts-about">
                    <div class="contacts">
                        <ul class="list-of-contacts">
                            <div class="list-title-contacts">CONTACTS</div>
                            <li class="contact">Moscow, Russia</li>
                            <li class="contact">Email: <a class="contact-link"
                                    href="mailto:dasha-sheludyakova@yandex.ru">dasha-sheludyakova@yandex.ru</a></li>
                            <li class="contact">Github: <a class="contact-link"
                                    href="https://github.com/Dasha-Vr">Dasha-Vr</a></li>
                            <li class="contact">Discord: <a class="contact-link"
                                    href="https://discordapp.com/users/896698553064366120/">Da_sha</a></li>
                        </ul>
                    </div>
                    <div class="about">
                        <h2 class="list-title">ABOUT ME</h2>
                        <p class="text"> Я начала учиться програмированию полгода назад. Вначале изучала питон, потом
                            поняла что мне больше подходит джава скипт.
                            Мне очень нравится верстать сайты надеюсь когда-нибудь научиться это делать на
                            профессиональном уровне.
                            Кроме програмирования увлекаюсь фотографией и поэзией.</p>
                    </div>
                </div>
            </section>
            <section class="skills-and-code">
                <div class="skills" id="skills">
                    <h2 class="list-title">SKILLS</h2>
                    <ul class="list-of-skills">
                        <li class="name-of-skill">Web-development: <p class="skill">HTML5, CSS3, JavaScript, Python</p>
                        </li>
                        <li class="name-of-skill">Version control:<p class="skill">GIT, Github</p>
                        </li>
                    </ul>
                </div>
                <div class="code-ex">
                    <h2 class="list-title">CODE EXAMPLE</h2>

                    <pre class="code"><code>function nthFibo(n) {
    let line = [0, 1];
    let v = 0;
        while (v < n) {
        a = line[line.length -1];
        b = line[line.length -2];
        v = a + b;
        line.push(v);
        }
    return line;
    }
    </code></pre>

                </div>

            </section>
        </div>
    </main>

</body>

</html>