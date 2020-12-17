<template>
    <div id="app">
        <actionbar />
        <formSearch />
        <footerBar />
    </div>
</template>

<script>
import actionbar from "./components/actionbar";
import formSearch from "./components/formSearch";
import footerBar from "./components/footerBar";
export default {
    components: {
        actionbar,
        formSearch,
        footerBar
    }
}
</script>

<style>
* {
    margin: 0px;
    padding: 0px;
    outline: none;
    box-sizing: border-box;
}
</style>