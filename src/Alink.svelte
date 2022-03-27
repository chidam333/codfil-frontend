<script>
    import Router from 'svelte-hash-router';
</script>
<main>
    <div class="heading">Submit Your Links</div>
    <form action="" id="myform">
        <div class="inp"><input type="text" placeholder="Github profile link" required></div>
        <div class="inp"><input type="text" placeholder="Codechef profile link" required></div>
        <div class="inp"><input type="text" placeholder="Leetcode profile link" required></div>
        <div class="btn"><a href="#/dash1" on:click={document.getElementById('myform').submit()}>Submit !</a></div><Router/>
    </form>
</main>
<style>
    main{
        background: linear-gradient(to bottom,black,#c0871c);
        height: 84vh;
    }
    .heading{
        font-size: 3rem;
        font-family: "ele";
        display: grid;
        place-items: center;
        text-align: center;
        color: wheat;
        height: 8vh;
    }
    .inp{
        margin: 10vh 0%;
        display: grid;
        justify-items: center;
    }
    .inp input{
        border-radius: 25px;
        padding: 1%;
        width: 35vh;
        font-family: roboto;
        color: black;
    }
    .btn{
        display: grid;
        justify-items: center;
    }
    .btn a{
        text-decoration: none;
        background: black;
        color: wheat;
        border-radius: 4vh;
        padding: 2vh;
    }
</style>