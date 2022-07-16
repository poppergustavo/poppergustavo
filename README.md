### Welcome to my Profile.

My name is <strong>Gustavo Pöpper</strong> and I am currently studying Systems Analysis and Development. I have knowledge in HTML5, ORACLE SQL PL/SQL, Java, Delphi, Git and GitHub. I'm currently studying <strong>Javascript</strong>.

- 📫 My E-mail: gustavo.popper@philips.com

##

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">

<div style="display: inline-block" onclick="disable"><br>
    <a href="https://www.devmedia.com.br/o-que-e-o-html5/25820"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="100" height="50"/></a>
    <a href="https://www.oracle.com/br/database/technologies/appdev/plsql.html"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" width="100" height="50"/></a>
    <a href="https://www.java.com/pt-BR/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="100" height="50"/></a>
    <a href="https://www.javascript.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" width="100" height="50"/></a>
    <a href="https://git-scm.com"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="100" height="50"/></a>
    <a href="https://github.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg" width="100" height="50"/></a>
</div>
  
##

Connect with me on LinkeIn:

<div style="display: inline-block"><br>
    <a href="https://www.linkedin.com/in/gustavopopper/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="100" height="50" /></a>
</div>

<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Qquicker',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
