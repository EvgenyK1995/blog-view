<template>
    <header class="header">
        <a href="/" class="header__logo">Что-то типа логотипа...</a>
        <button class="header__user-btn">
            <img src="../assets/user.png" alt="user" title="Вход/Регистрация" />
        </button>
    </header>
</template>
<script>
export default {
  name: 'Header'
}
</script>
<style scoped>
.header {
    background-color: #808080;
    border-radius: 0 0 40px 10px;
    box-shadow: 1px 3px 5px #A9A9A9;
    display: flex;
    height: 100px;
    justify-content: space-between;
}
.header a {
    text-decoration: none;
}
.header__logo {
    align-self: center;
    background-color: #4b6b5f;
    border-radius: 5px;
    box-shadow: 2px 2px 2px #0f0, -2px -2px 2px #0ff, 2px -2px 5px #800, -2px 2px 5px #800;
    color: #eee;
    font-size: 1.3em;
    font-weight: bold;
    margin-left: 20px;
    padding: 15px 10px;
}
.header__logo:hover {
    box-shadow: 3px 3px 4px #0f0, -3px -3px 4px #0ff, 2px -2px 5px #800, -2px 2px 5px #800;
}
.header__user-btn {
    align-self: center;
    background: none;
    border: none;
    cursor: pointer;
    margin-right: 30px;
    max-height: 50px;
}
.header__user-btn:hover {
    transform: scale(1.1);
}
.header__user-btn:focus,
.header__user-btn:active {
    outline: none;
}
.header__user-btn img {
    max-height: 50px;
}
</style>
