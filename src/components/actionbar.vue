<template>
    <div>
        <nav class="actionbar">
            <a href="#">Gmail</a>
            <a href="#">Imagens</a>
            <a href="#">
                <span class="glyphicon glyphicon-th"></span>
            </a>
            <img src="../assets/profile.jpg" alt="profile-image"/>
        </nav>
    </div>
</template>

<style scoped>

.actionbar {
    width: 100vw;
    display: flex;
    flex-flow: row nowrap;
    justify-content: flex-end;
}

.actionbar a {
    position: relative;
    top: 20px;
    margin-right: 15px;
    color: #212121;
    font-size: 13px;
    font-weight: 470;
    font-family: arial;
    text-decoration: none;
}

.actionbar a:hover {
    text-decoration: underline;
}

.actionbar a:nth-child(3){
    top: 17px;
    font-size: 17px;
    color: grey;
}

.actionbar img {
    cursor: pointer;
    position: relative;
    top: 10px;
    width: 35px;
    height: 35px;
    margin-right: 15px;
    border-radius: 50%;
}
</style>