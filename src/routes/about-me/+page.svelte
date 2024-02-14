<script>
    import Header from "$lib/Header.svelte";
    import Footer from "$lib/Footer.svelte";
    import Nav from "$lib/Nav.svelte";
</script>

<Header title="About me" subtitle="Emma is amazing" />
<Nav />

<main class="content section">
    <h2 class="title">My Summer Activities</h2>

    <div class="columns is-link">
        <div class="column">
            <h4>Summer Activity 1</h4>
            <p>
                I went to the river with my friend and we got the car stuck.
                While we were digging ourselves out, I got eaten alive by
                mosqitoes. So I was very itchy.
            </p>
            <img src="river.jpeg" alt=" a river" />
        </div>
        <div class="column">
            <h4>Summer Activity 2</h4>
            <p>
                We went to the lakes and went biscuiting. My arms and legs were
                very sore, but i didn't fall off so it was a win.
            </p>
            <img src="lakes.jpeg" alt=" a lake" />
        </div>
        <div class="column">
            <h4>Summer Activity 3</h4>
            <p>
                For new years I went to Wanaka and it was very fun because it
                was basically a concert and the music was very good.
            </p>
            <img src="wanaka.jpeg" alt=" a concert basically" />
        </div>
    </div>
</main>

<Footer />
