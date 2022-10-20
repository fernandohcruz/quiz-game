<template>
    <div class="test">
        This is a product page TEST
    </div>
    <div class="test2">
        <button type="button">I'm a button</button>
    </div>
</template>
<script>
export default {

}
</script>
<style lang="scss">
.test {
    width: 940px;
    background-color: #000000;
    font-size: 100px;
    color: #ffffff;
}

.test2 {
    button {
        font-size: x-large;
        width: 500px;
        margin-top: 100px;
        background-color: #43f4f4;
        color: #ffffff;
        transition: 1s;
        cursor: pointer;
    }

    button:hover {
        background-color: #000000;
        transform: rotate(360deg) scale(2);
    }
}
</style>