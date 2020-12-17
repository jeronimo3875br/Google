<template>
    <div>
        <footer>
            <h5>Brasil</h5>
            <hr>
            <div class="container-links">
                <div class="container-links-1">
                    <a href="#">Publicidade</a>
                    <a href="#">Negócios</a>
                    <a href="#">Sobre</a>
                    <a href="#">Como funciona?</a>
                </div>
                <div class="container-links-2">
                    <a href="#">Privacidade</a>
                    <a href="#">Termos</a>
                    <a href="#">Configuração</a>
                </div>
            </div>
        </footer>
    </div>
</template>

<style scoped>
footer {
    position: absolute;
    bottom: 0;
    width: 100vw;
    padding: 7px;
    background-color: #f2f2f2;
    border-top: 1px solid #cccccc;
}

footer .container-links {
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
    margin-bottom: 7px;
}

footer .container-links .container-links-1 a {
    margin-left: 20px;
}

footer .container-links .container-links-2 a {
    margin-right: 20px;
}


footer h5 {
    margin-left: 20px;
    color: grey;
}

footer hr {
    background-color: #cccccc;
    height: 0.5px;
}

footer a {
    color: grey;
    margin-left: 10px;
}

@media screen and (max-width: 750px){
    footer .container-links .container-links-2 {
        margin-left: 10px;
    }
}
</style>