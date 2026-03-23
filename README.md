<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">

<style>
    body {
        background-color: #0d1117;
        color: #c9d1d9;
        font-family: Arial, sans-serif;
    }

    h1 {
        text-align: center;
        font-size: 2.5em;
        color: #58a6ff;
        animation: fadeIn 2s ease-in-out;
    }

    .container {
        text-align: center;
        margin-top: 20px;
        animation: fadeIn 2s ease-in-out;
    }

    .icons img {
        transition: transform 0.3s ease, filter 0.3s ease;
        margin: 10px;
    }

    .icons img:hover {
        transform: scale(1.2);
        filter: drop-shadow(0 0 8px #58a6ff);
    }

    .card {
        background: #161b22;
        padding: 20px;
        border-radius: 10px;
        margin: 20px auto;
        width: 80%;
        box-shadow: 0 0 15px rgba(88,166,255,0.2);
        transition: transform 0.3s ease;
    }

    .card:hover {
        transform: translateY(-5px);
    }

    .links img {
        transition: transform 0.3s ease;
    }

    .links img:hover {
        transform: scale(1.15);
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(10px);}
        to { opacity: 1; transform: translateY(0);}
    }
</style>

<h1>🚀 Welcome to my Profile</h1>

<div class="container">
    <div class="card">
        <p>
            My name is <strong>Gustavo Pöpper</strong> 👨‍💻 <br><br>
            I’m studying <strong>Systems Analysis and Development</strong>.
        </p>

        <p>
            💡 Technologies I work with:
        </p>

        <div class="icons">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="60"/>
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" width="60"/>
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="60"/>
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" width="60"/>
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="60"/>
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="60"/>
        </div>

        <p>
            📚 Currently learning: <strong>JavaScript & Web Development</strong>
        </p>
    </div>

    <div class="card">
        <h3>🌐 Connect with me</h3>

        <div class="links">
            <a href="https://www.linkedin.com/in/gustavopopper/">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="50"/>
            </a>

            <a href="https://github.com/poppergustavo/ProjectX">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="50"/>
            </a>
        </div>
    </div>
</div>
