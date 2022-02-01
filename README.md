[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6725536&assignment_repo_type=AssignmentRepo)
# full-projects-starter


## structure

index.html -> html code
css/* -> styling
js/* -> javascript code
js/* -> javascript directory

@media(min-width:300px) {

    body {
        margin: 0;
        padding: 0;

        background: white;
        color: #cdcdcd;
        font-family: "Avenir Next", "Avenir", sans-serif;
    }

    .header {
        margin: 0;
        width: 100%;
        height: 400px;
        position: relative;
        transform: translate(0, -30px);
    }

    .headertext {
        color: white;
        position: relative;
        transform: translate(10%, -150%);
    }

    #menuToggle {
        display: block;
        position: fixed;
        top: 2%;
        left: 2%;

        z-index: 1;

        -webkit-user-select: none;
        user-select: none;
    }

    #menuToggle a {
        text-decoration: none;
        color: #232323;

        transition: color 0.3s ease;
    }

    #menuToggle a:hover {
        color: blue;
    }


    #menuToggle input {
        display: block;
        width: 40px;
        height: 32px;
        position: absolute;
        top: -7px;
        left: -5px;

        cursor: pointer;

        opacity: 0;
        z-index: 2;

        -webkit-touch-callout: none;
    }


    #menuToggle span {
        display: block;
        width: 33px;
        height: 4px;
        margin-bottom: 5px;
        position: relative;

        background: white;
        border-radius: 3px;

        z-index: 1;

        transform-origin: 4px 0px;

        transition: transform 0.5s cubic-bezier(0.77, 0.2, 0.05, 1.0),
            background 0.5s cubic-bezier(0.77, 0.2, 0.05, 1.0),
            opacity 0.55s ease;
    }

    #menuToggle span:first-child {
        transform-origin: 0% 0%;
    }

    #menuToggle span:nth-last-child(2) {
        transform-origin: 0% 100%;
    }

    #menuToggle input:checked~span {
        opacity: 1;
        transform: rotate(45deg) translate(-2px, -1px);
        background: black;
    }


    #menuToggle input:checked~span:nth-last-child(3) {
        opacity: 0;
        transform: rotate(0deg) scale(0.2, 0.2);
    }

    #menuToggle input:checked~span:nth-last-child(2) {
        transform: rotate(-45deg) translate(0, -1px);
    }

    #menu {
        position: absolute;
        width: 300px;
        margin: -100px 0 0 -50px;
        padding: 50px;
        padding-top: 125px;

        background: #ededed;
        list-style-type: none;
        -webkit-font-smoothing: antialiased;

        transform-origin: 0% 0%;
        transform: translate(-100%, 0);

        transition: transform 0.5s cubic-bezier(0.77, 0.2, 0.05, 1.0);
    }

    #menu li {
        padding: 10px 0;
        font-size: 22px;
    }

    #menuToggle input:checked~ul {
        transform: none;
    }

    .content {
        text-align: center;
        color: black;
    }

    button {
        border: 3px solid yellow;
        background-color: white;
        color: yellow;
        width: 70%;
        border-radius: 15px;
        padding: 5px;
    }

    button:active {
        border: 3px solid yellow;
        background-color: yellow;
        color: white;
    }

    .item {
        margin-left: 4%;
        margin-right: 4%;
    }

    .aboutslide {
        margin-left: 20%;
        margin-right: 20%;
    }

    .aboutslide img {
        border-radius: 15px;
        padding: 10px;
    }

    .news {
        background-color: lightyellow;
    }

    .cantine {
        background-color: white;
        color: black;
        margin: 4%;
    }

    .cantine img {
        padding: 5px;
    }

    #footer {
        width: 100%;
        background-color: lightsteelblue;
        color: black;

    }

    .contact {
        display: flex;
        justify-content: space-evenly;
    }


    .tel {}

    a.button {
        -webkit-appearance: button;
        -moz-appearance: button;
        appearance: button;
        border-radius: 15px;
        text-decoration: none;
        color: initial;
        padding: 5px 10px;
        background-color: yellow;
        text-align: center;
        width: 70%;
    }
}