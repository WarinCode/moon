<script>
    const url = "https://pngimg.com/uploads/moon/moon_PNG10.png";
</script>

<img src={url} alt="moon" id="the-moon">

<style>
    :root{
        --light-moon:#fdfcfc;
        --shadow:#1d1d1d;
    }
    #the-moon{
        width: 280px;
        height: 280px;
        transition: all .7s ease-in-out;
        cursor: default;
        filter: drop-shadow(9px 14px 11px var(--shadow));
    }
    #the-moon:hover{
        scale: 125%;
        filter: drop-shadow(0 0 23px var(--light-moon));
    }
</style>