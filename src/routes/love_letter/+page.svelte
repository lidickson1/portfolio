<script>
    import Link from "$components/Link.svelte";
    import Button from "$components/Button.svelte";
    import Carousel from "$components/Carousel.svelte";
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
        User Interface
    </h1>
    <p class="text-slate-700 dark:text-slate-300 mb-8" data-aos="fade-up">
        The UI has been designed to be intuitive so that even new players can
        start playing the game right away with minimal guidance. Playtesters
        were able to navigate the UI and play the game without any frustrations.
        The website also supports light and dark theme right out of the box, and
        is playable both on desktop and mobile.
        <!-- For example, every time when the user plays a card, a confirmation dialog
        is shown to prevent misclicks and to remind the user that it is an irreversible
        action. -->
    </p>
    <Carousel>
        <img src="images/love_letter/themes.png" alt="" />
        <img src="images/love_letter/mobile.png" alt="" />
    </Carousel>
</div>

<div class="section">
    <h1 class="text-4xl font-bold text-center mb-10" data-aos="fade-down">
        Bot Support
    </h1>
    <p class="text-slate-700 dark:text-slate-300 mb-8" data-aos="fade-up">
        The room's host can choose to add as many bots as they want if they want
        to have more players. These bots will play cards like a normal player.
        This makes it a perfect app to kill time when you're bored.
    </p>
    <img src="images/love_letter/bots.png" alt="" />
</div>
