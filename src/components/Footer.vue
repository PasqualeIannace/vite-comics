<script>
    export default {
        // data() {
        //     return {
        //         links: [
        //             {

        //             }
        //         ]
        //     }
        // }

        mounted() {
        console.log("Footer!")
        }
    }
</script>

<template>
    <div class="containerBg">
        <div class="desktop container">
            <div class="links">

                <div class="link">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li>
                            <a href="#">
                                Characters
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Comics
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Movies
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                TV
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Games
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Videos
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                News
                            </a>
                        </li>
                    </ul>


                    <h3 class="py1">SHOP</h3>

                    <ul>
                        <li>
                            <a href="#">
                                Shop DC
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Shop DC Collectibles
                            </a>
                        </li>
                    </ul>
                </div>

                <div class="link">
                    <h3>DC</h3>

                    <ul>
                        <li>
                            <a href="#">
                                Terms Of Use
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Privacy policy (New)
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Ad Choices
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Advertising
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Jobs
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Subscriptions
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Talent Workshops
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                CPSC Certificates
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Ratings
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Shop Help
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Contact Us
                            </a>
                        </li>
                    </ul>
                </div>

                <div class="link">
                    <h3>SITES</h3>

                    <ul>
                        <li>
                            <a href="#">
                                DC
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                MAD Magazine
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                DC Kids
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                DC Universe
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                DC Power Visa
                            </a>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="logo">
                <img src="dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>

    <!-- seconda sezione footer -->
    <div class="secondBg">
        <div class="secondContainer desktop">
            <div class="btn">
                <button>SIGN-UP NOW!</button>
            </div>

            <div class="socials">
                <h3>FOLLOW US</h3>
                <div class="socialBtn">
                    <a href="#">
                        <img src="footer-facebook.png" alt="">
                    </a>
                </div>
                <div class="socialBtn">
                    <a href="#">
                        <img src="footer-twitter.png" alt="">
                    </a>
                </div>
                <div class="socialBtn">
                    <a href="#">
                        <img src="footer-youtube.png" alt="">
                    </a>
                </div>
                <div class="socialBtn">
                    <a href="#">
                        <img src="footer-pinterest.png" alt="">
                    </a>
                </div>
                <div class="socialBtn">
                    <a href="#">
                        <img src="footer-periscope.png" alt="">
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .containerBg {
        background-image: url(/footer-bg.jpg);
    }
    .container {
        padding: 0 4em;
        display: flex;
        justify-content: space-between;
        height: 25em;
    }

    h3 {
        color: white;
    }

    li a {
        color: gray;
        text-decoration: none;
    }

    li a:hover {
        color: white;
    }

    li {
        list-style: none;
    }

    .links {
        display: flex;
    }

    .link {
        padding: 3em 0;
        margin-right: 1.5em;
    }

    .link h3 {
        padding-bottom: 1em;
    }
    .logo img {
        object-fit: cover;
        height: 25em;
        width: 35em;
    }

    /* section 2 */
    .secondBg {
        background: #303030;
    }
    .secondContainer {
        padding: 0 4em;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .socials {
        display: flex;
        align-items: center;
    }

    .socials h3 {
        color: #0082F9;
        padding: 0 1em;
    }

    .socialBtn {
        padding: 1.5em 0.5em;
    }

    button {
        color: white;
        border: 2px solid #0082F9;
        background: transparent;
        padding: 1em;
        font-weight: bold;
        font-size: 1em;
    }

</style>