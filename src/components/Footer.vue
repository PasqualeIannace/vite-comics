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
    <div class="container">
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
            </div>

            <div class="link">
                <h3>SHOP</h3>

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
</template>

<style scoped>
    .container {
        background-image: url(/footer-bg.jpg);
        padding: 0 4em;
        display: flex;
    }

    h3 {
        color: white;
    }

    li a {
        color: gray;
        text-decoration: none;
    }

    li {
        list-style: none;
    }

    .links {
        display: flex;
    }

    /* .logo img {
        object-fit: cover;
    } */

</style>