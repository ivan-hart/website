<script>

</script>

<nav id="navbar">
    <a href="ivanhart.dev"><img src="../assets/logo.svg" alt="logo"></a>
    <ul>
        <li><a href="top">HOME</a></li>
        <li><a href="#">GOALS</a></li>
        <li><a href="#projects">PROJECTS</a></li>
        <li><a href="#">ABOUT</a></li>
    </ul>
</nav>

<style>
    img {
        content: url('../assets/logo.svg');
        width: 4em;
    }
    nav {
        display: flex;
        position: fixed;
        width: 100%;
        justify-content: space-between;
        align-items: center;
        background-color: #00000055;
        padding: 20px;
        overflow: none;
    }
    ul {
        list-style: none;
    }
    li {
        display: inline;
        margin-inline: 15px;
    }
    a {
        color: #fff;
        font-size: 1.3em;
        text-decoration: none;
    }
    li:hover {
        outline: 1px solid #fff;
        padding: 10px;
        margin-inline: 5px;
    }
    @keyframes nav {
        from {top : 0px}
        to {top: -100px}
    }
</style>