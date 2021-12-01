<template>
    <form action="javascript:void(0)">
        <input type="text" id="email_input" placeholder="email">
        <input type="text" id="password_input" placeholder="password">
        <input type="submit" id="login_submit" value="Login">
    </form>
</template>

<script>
    export default {
        name: "page-login"
    }
</script>

<style scoped>
page-login {
    width: 100%;
    display: grid;
    place-items: center;
}
input {
    margin: 10px;
}
</style>