<template>
    <div>
        <div class="container">
            <googleImage />
            <form class="form-search">
                <button>
                    <span class="fa fa-search"></span>
                </button>
                <input
                    type="search"
                    placeholder="Pesquise..."
                />
                <button>
                    <span class="fa fa-microphone"></span>
                </button>
            </form>
            <otherOptions />
        </div>
    </div>
</template>

<script>
import googleImage from "./googleImage";
import otherOptions from "./otherOptions";
export default {
    components: {
        googleImage,
        otherOptions
    }
}
</script>

<style scoped>
.container {
    position: relative;
    top: 50px;
    display: flex;
    flex-flow: column;
    justify-content: center;
    align-items: center;
}

.form-search {
    width: 40vw;
    border: 1px solid #dddddd;
    border-radius: 50px;
    padding: 12px;
    display: flex;
    justify-content: space-between;
}

.form-search:hover {
    box-shadow: 0px 2px 7px #cccccc;
}

.form-search button {
    position: relative;
    color: grey;
    border: none;
    font-size: 15px;
    background-color: #ffffff;
}

.form-search button:nth-child(1){
    left: 5px;
}

.form-search button:nth-child(3){
    right: 5px;
}

.form-search input {
    border: none;
    width: 87%;
}

@media screen and (max-width: 750px){
    .form-search {
        width: 83vw;
    }
}
</style>