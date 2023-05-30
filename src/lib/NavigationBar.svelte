<header>
    <div class="featurebar">
        <div class="feature_items">
            <p>Music fitchart</p>
            <p>Lifetime warranty</p>
            <p>Superior quality</p>
            <p>Endless applications</p>
        </div>
        <div class="feature_info">
            <p>+31 (0)88 0234 600</p>
            <p class="partnerlogin">Partner login</p>
        </div>
    </div>
    <div class="navigationbar">
        <nav>
            <img src="/logo.png" alt="Logo of SKB Europe" />
            <div class="navlinks">
                <a href="">Products</a>
                <a href="">Applications</a>
                <a href="">News & Events</a>
                <a href="">Contact</a>
            </div>
        </nav>
        <div class="search">
            <p>Can we help you?</p>
        </div>
    </div>
</header>

<style lang="scss">
    header {
        width: 100%;
    }

    .featurebar {
        display: flex;
        justify-content: space-around;
        background: black;
        color: white;
    }

    .feature_items {
        display: flex;
        justify-content: space-between;
        margin: 1rem;
        gap: 4rem;
    }

    .feature_info {
        display: flex;
        justify-content: space-between;
        gap: 2rem;
        margin: 1rem;
    }

    .navigationbar {
        display: flex;
        justify-content: space-around;
        margin-top: 2rem;
    }

    nav {
        display: flex;
        justify-content: space-between;
        gap: 2rem;
        align-items: center;
    }
    .navlinks {
        display: flex;
        justify-content: space-between;
        gap: 1rem;
    }

    .partnerlogin {
        background-color: red;
    }
</style>
