<script>
import Navbar from './Navbar.svelte'
</script>

<header>
<Navbar />
<div class="center">
    <h1>Ivan Hart</h1>
    <hr width="300" color="#fff">
    <p>Frontend Developer</p>
</div>
</header>

<style>
header {
    background-image: url('../assets/header-background.svg');
    height: 100vh;
}
.center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100%;
    color: #fff;
}
.center h1 {
    font-size: 4.5em;
}
hr {
    margin-block: 10px;
}
</style>