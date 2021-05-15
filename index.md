<!DOCTYPE html>
<html>
<title>MattMX - Home</title>
<head>
    <div class="blurred-box">
        <img src="icon.png" class="user-icon">
        <div class="user-name"><font face="Arial Black" size="15"><b>COMING SOON</b></font></div>
    </div>
    <div class="links">
        <a href="https://discord.gg/4UP6SgGGr3" target="_blank"><img src="https://discord.com/assets/1c8a54f25d101bdc607cec7228247a9a.svg" width="30px" height="30px" /></a>
        <a href="https://www.youtube.com/channel/UCAVYIWz1R7RLQwns4oofcKw" target="_blank"><img src="youtube.png" width="35px" height="27px" /></a>
    </div>
    <div id="fixedheader">
        <font face="verdana">
            <a href="index.html">
            &emsp;<b>MX</b>&emsp;|&emsp; MattMX. &emsp;&emsp;
                </a>
            <ul>
                <li>
                    Projects
                    <ul>
                        <li><a href="clientsideteams.html">ClientSideTeams</a></li>
                        <li><a href="https://www.curseforge.com/minecraft/mc-mods/clientbot" target="_blank">ChatBot</a></li>
                        <li><a href="store-other.html">Inferno Client</a></li>
                    </ul>
                </li>
            </ul>
        </font>
    </div>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        html {
            width: 100vw;
            height: 100vh;
        }

        body {
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
            background-position: top;
            background-image: url(main_bg.png);
            width: 100%;
            height: 100%;
            font-family: Arial, Helvetica;
            letter-spacing: 0.02em;
            font-weight: 400;
            -webkit-font-smoothing: antialiased;
        }

        .blurred-box {
            position: relative;
            width: 500px;
            height: 150px;
            padding-top: 50px;
            padding-left: 50px;
            padding-right: 50px;
            top: calc(50% - 50px);
            left: calc(50% - 275px);
            background: inherit;
            box-shadow: inset 0 0 0 200px rgba(0,0,0,0.5);
            border-radius: 2px;
            overflow: hidden;
            text-align: left;
        }

        .user-icon {
            float: left;
            height: 75px;
            width: 75px;
            font-family: Veranda;
            animation-name: fadein;
            animation-duration: 4s;
        }

        .links {
            right: 20px;
            bottom: 20px;
            width: 200px;
            height: 20px;
            position: fixed;
            color: white;
            padding: 30px;
            text-align: right;
            background-color: transparent;
        }

        div a {
            text-decoration: none;
            color: inherit;
            padding: 8px;
            display: inline-block;
        }

        ul {
            display: inline;
        }

            ul li {
                display: inline-block;
            }

                ul li:hover {
                    animation-name: fadein;
                    animation-duration: 0.5s;
                }

                    ul li:hover ul {
                        display: block;
                    }

                ul li ul {
                    position: absolute;
                    width: 200px;
                    display: none;
                }

                    ul li ul li {
                        background: #FFF;
                        display: block;
                    }

                        ul li ul li a {
                            display: block !important;
                        }

                        ul li ul li:hover {
                            background: #FFF;
                        }

        .user-name {
            float: right;
            color: white;
            animation-name: fadein;
            animation-duration: 4s;
        }

        div#fixedheader {
            position: fixed;
            top: 0px;
            left: 0px;
            width: 100%;
            height: 4%;
            box-shadow: inset 0 0 0 200px rgba(0,0,0,0.5);
            color: white;
            padding: 10px;
            opacity: 1;
            transition: .5s ease;
        }

            div#fixedheader:hover {
                box-shadow: inset 0 0 0 200px rgba(255,255,255,1);
                color: black;
            }
        @keyframes fadein {
            from {
                opacity: 0;
            }

            to {
                opacity: 1.0;
            }
    </style>
</head>
</html>
