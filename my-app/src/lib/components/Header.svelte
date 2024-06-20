<header>
    <div class="header-logo">
        <h1>R</h1>
        <div>
            <p>Rayan</p>
            <p>Web Developer</p>
        </div>
    </div>
    <div class="header-navigation">
        <a href="Home">Home</a>
        <a href="Info">Info</a>
    </div>
    <div class="header-socials">
        <a href="GitHub">GitHub</a>
        <a href="Linkedin">Linkedin</a>
    </div>
</header>



<style>

header {
    display: flex;
    justify-content: space-between;
    margin: 1rem;
}

.header-logo {
    display: flex;
    flex-direction: row;
    
}

h1 {
    color: white;
    font-size: 50px;
}

p {
    color: white;
    transform: translateY(80%);
}

.header-navigation {
    display: flex;
    flex-direction: row;
    justify-content: center;
    background-color: rgb(36, 35, 35);
    border-radius: 15px;
    padding: 1rem;
}

div a {
    text-decoration: none;
    color: white;
    transform: translateY(10%);
}

.header-socials {
    transform: translateY(30%);
}

</style>