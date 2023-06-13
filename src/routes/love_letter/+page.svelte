<script>
    import Link from "$components/Link.svelte";
    import Button from "$components/Button.svelte";
</script>

<div class="section grid md:grid-cols-2 gap-10 py-20">
    <div class="flex flex-col justify-center" data-aos="fade-right">
        <div>
            <h1 class="text-5xl font-bold">Love Letter</h1>
            <p class="my-8 text-slate-700 dark:text-white">
                A full stack multiplayer web browser game based on the card game
                <Link
                    text="Love Letter™"
                    url="https://www.zmangames.com/en/games/love-letter/"
                />. Built using <Link text="React" url="https://react.dev" />, <Link
                    text="Bulma"
                    url="https://bulma.io/"
                />, <Link text="Express" url="https://expressjs.com/" />, and <Link
                    text="Socket.IO"
                    url="https://socket.io/"
                />. Deployed on <Link text="Vercel" url="https://vercel.com/" />
                and <Link text="Fly.io" url="https://fly.io/" />. The game can
                be played both on a computer and on a mobile device. It also has
                bot support.
            </p>
            <Button
                text="Play now!"
                url="https://love-letter-resume.vercel.app/"
            />
        </div>
    </div>
    <img src="images/love_letter.png" alt="Love Letter" data-aos="fade-left" />
</div>

<div class="section bg-slate-100 dark:bg-slate-800">
    <h1 class="text-4xl font-bold text-center mb-10" data-aos="fade-down">
        Gameplay
    </h1>
    <p class="text-stone-300 mb-8" data-aos="fade-up">
        The gameplay is based on the card game
        <Link
            text="Love Letter™"
            url="https://www.zmangames.com/en/games/love-letter/"
        /> and is very straightforward. The players simply have to choose a card
        to play, and optionally choose a target for example via a modal dialog on
        their turn. The UI has been designed to be intuitive so that even new players
        can start playing the game right away with minimal guidance. Playtesters
        were able to navigate the UI and play the game without any frustrations.
        For example, every time when the user plays a card, a confirmation dialog
        is shown to prevent misclicks and to remind the user that it is an irreversible
        action.
    </p>
</div>

<!-- <div class="section">
    <h1 class="text-4xl font-bold text-center mb-10" data-aos="fade-down">
        My Projects
    </h1>
    <div class="grid md:grid-cols-3 gap-10">
        <Project
            name="Bayview Battle Royale"
            description="A Minecraft server built with Java, Kotlin, and the Spigot API, featuring guns, a variety of gamemodes, bots, and purchasable cosmetics"
            url="/bbr"
            ><img
                slot="image"
                src="images/bbr.png"
                alt="Bayview Battle Royale"
            /></Project
        >
        <Project
            name="Love Letter"
            description="A full stack multiplayer web browser game based on the card game Love Letter™. Built using React, Bulma, Express, and Socket.IO. Deployed on Vercel and Fly.io"
            ><img
                slot="image"
                src="images/love_letter.png"
                alt="Love Letter"
            /></Project
        >
        <Project
            name="Alice Mazes"
            description="A React app where users can play, edit, or have it automatically solve logic mazes invented by Robert Abbott"
            ><img
                slot="image"
                src="images/alice_maze.png"
                alt="Alice Mazes"
            /></Project
        >
        <Project
            name="Hackermatch"
            description="A Tinder-like matching web app for hackers to easily find teammates for hackathons. Built with jQuery, Materialize, Node.js, Express, Heroku, and Firebase"
            ><img
                slot="image"
                src="images/hacker_match.png"
                alt="Hackermatch"
            /></Project
        >
        <Project
            name="Alchemy"
            description="A desktop game app inspired by games like Little Alchemy and Doodle God with full modding/addon support. Written in Java using the Processing Library."
            url="https://github.com/lidickson1/Alchemy2"
            ><img
                slot="image"
                src="https://cdn.discordapp.com/attachments/269226485951234068/664307072564985876/screenshot.png"
                alt="Alchemy"
            /></Project
        >
    </div>
</div> -->
