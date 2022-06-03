<template>
    <html lang="en">

    <body>

        <div id="root">
            <div class="App">
                <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
                    <a class="navbar-brand" id="logo-link" href="/">
                        <img src="../assets/images/mainlayout/okr.png" alt="OKRs.app" class="header-logo"></a>
                    <div class="collapse navbar-collapse">
                        <ul class="nav navbar-nav ml-auto">
                            <li class="nav-item">
                                <router-link class="nav-link"  :to="{name:'signup'}">Sign up</router-link>
                            </li>
                            <li class="nav-item">
                            <router-link class="nav-link"  :to="{name:'login'}">Login</router-link>

                            </li>
                        </ul>
                    </div>
                </nav>
                <main class="Dashboard">
                    <div id="landing">
                        <header class="masthead text-center mt-4">
                            <div class="overlay"></div>
                            <div class="container">
                                <div class="row">
                                    <div class="col-lg-6 order-lg-2">
                                        <img class="demo-gif" src="../assets/images/mainlayout/landing.gif"
                                            alt="">
                                    </div>
                                    <div class="col-lg-6 order-lg-1">
                                        <h1 class="mb-4">Reach your personal goals with OKRs</h1>
                                        <p class="mb-4 landing-lead-in">Objectives and Key Results (OKRs) are used by
                                            some of the most successful companies in the world. Should you accept any
                                            less?<br>
                                            No prior knowledge needed - we'll get you started with OKRs today.
                                        </p>
                                        <div class="col-xl-4 button-container">
                                            <a class="signup-button" href="/signup">
                                                <router-link
                                                    class="btn btn-block btn-lg btn-primary btn-signup" :to="{name:'signup'}">Sign Up</router-link>
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </header>
                        <section class="features-icons bg-light text-center">
                            <div class="container">
                                <div class="row">
                                    <div class="col-lg-4">
                                        <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
                                            <img class="img-fluid selling-point-icon mb-3"
                                                src="../assets/images/mainlayout/simple.png" alt="simpleImg">
                                            <h3>Simple</h3>
                                            <p class="lead mb-0">
                                                No experience with Objectives and Key Results (OKRs) required. We'll set
                                                you up with everything you need.
                                            </p>
                                        </div>
                                    </div>
                                    <div class="col-lg-4">
                                        <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
                                            <img class="img-fluid selling-point-icon mb-3"
                                                src="../assets/images/mainlayout/effective.png" alt="effectiveImg">
                                            <h3>Effective</h3>
                                            <p class="lead mb-0">
                                                A simple dashboard and helpful reminders make it easy to check in on
                                                your OKRs every week.
                                            </p>
                                        </div>
                                    </div>
                                    <div class="col-lg-4">
                                        <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
                                            <img class="img-fluid selling-point-icon mb-3"
                                                src="../assets/images/mainlayout/rewarding.png" alt="rewardingImg">
                                            <h3>Rewarding</h3>
                                            <p class="lead mb-0">
                                                Making progress every week feels great! You'll get into the habit
                                                quickly when you see the results.
                                            </p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </section>
                        <section class="showcase">
                            <div class="container-fluid p-0">
                                <div class="row no-gutters">
                                    <div class="col-lg-6 order-lg-2 text-white showcase-img">
                                        <img class="illo" src="../assets/images/mainlayout/freelancers.gif" alt="freelancingImg">
                                    </div>
                                    <div class="col-lg-6 order-lg-1 my-auto showcase-text">
                                        <h2>For Freelancers</h2>
                                        <p class="lead mb-0">It can be hard to set goals when you have no-one to help
                                            you. And even harder to follow up! With OKRs you get a simple framework that
                                            you can use to keep track of your goals every week.</p>
                                    </div>
                                </div>
                                <div class="row no-gutters">
                                    <div class="col-lg-6 text-white showcase-img"><img class="illo"
                                            src="../assets/images/mainlayout/startups.gif" alt="startupImg"></div>
                                    <div class="col-lg-6 my-auto showcase-text">
                                        <h2>Startup Founders</h2>
                                        <p class="lead mb-0">You have ambitious goals, but are you using the right
                                            framework? OKRs can help you get specific on your goals, and ultimately help
                                            you make your vision a reality.</p>
                                    </div>
                                </div>
                                <div class="row no-gutters">
                                    <div class="col-lg-6 order-lg-2 text-white showcase-img"><img class="illo"
                                            src="../assets/images/mainlayout/anyone.gif" alt="anyoneImg"></div>
                                    <div class="col-lg-6 order-lg-1 my-auto showcase-text">
                                        <h2>Anyone!</h2>
                                        <p class="lead mb-0">OKRs are a surprisingly powerful tool. Even for your
                                            personal life, you can set objectives for your health, career, and just
                                            about anything! Forget New Year's resolutions - adopt OKRs instead and
                                            you'll see actual results.</p>
                                    </div>
                                </div>
                            </div>
                        </section>
                        <section class="testimonials text-center bg-light">
                            <div class="container">
                                <h2 class="mb-5">What users say about OKR</h2>
                                <div class="row">
                                    <div class="col-lg-4">
                                        <div class="testimonial-item mx-auto mb-5 mb-lg-0"><img
                                                class="img-fluid rounded-circle mb-3"
                                                src="../assets/images/mainlayout/user1.jpg" alt="">
                                            <h5>Illustrator</h5>
                                            <p class="font-weight-light mb-0">"This app has helped me reach my personal
                                                goals over the last year - I highly recommend it!"</p>
                                        </div>
                                    </div>
                                    <div class="col-lg-4">
                                        <div class="testimonial-item mx-auto mb-5 mb-lg-0"><img
                                                class="img-fluid rounded-circle mb-3"
                                                src="../assets/images/mainlayout/user2.png" alt="">
                                            <h5>Product Manager</h5>
                                            <p class="font-weight-light mb-0">"I honestly don't know how I managed my
                                                personal goals before I found this app. I can't wait for the team
                                                version."</p>
                                        </div>
                                    </div>
                                    <div class="col-lg-4">
                                        <div class="testimonial-item mx-auto mb-5 mb-lg-0"><img
                                                class="img-fluid rounded-circle mb-3"
                                                src="../assets/images/mainlayout/fuser3.png" alt="">
                                            <h5>Data Scientist</h5>
                                            <p class="font-weight-light mb-0">"I didn't really know how to set personal
                                                goals in a useful way. With OKRs.app I can even follow up on them
                                                weekly!"</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </section>
                        <section class="call-to-action text-white text-center">
                            <div class="overlay"></div>
                            <div class="container">
                                <div class="row">
                                    <div class="col-xl-9 mx-auto">
                                        <h2 class="mb-4 text-white">Ready to get started with OKRs?</h2>
                                    </div>
                                    <div class="col-xl-4 mx-auto"><a class="signup-button" href="/signup"><button
                                                type="submit" class="btn btn-block btn-lg btn-primary btn-signup">Sign
                                                Up</button></a></div>
                                </div>
                            </div>
                        </section>
                        <section>
                            <div class="overlay"></div>
                            <div class="container">
                                <div class="row">
                                    <div class="col-xl-9 mx-auto m-4"><a class="landing-what-are-okrs"
                                            href="https://learn.okrs.app/what-are-okrs/" target="_blank"
                                            rel="noopener noreferrer">Explore for OKR...</a></div>
                                </div>
                            </div>
                        </section>
                    </div>
                </main>
                <footer>
                    <p>Made in Nepal<span aria-label="fire" role="img">🔥</span>. © 2022 <a href="/about">Track OKR</a>.</p>
                </footer>
            </div>
        </div>
    </body>

    </html>
</template>



<script>
</script>

<style>
.navbar,
.navbar .container,
.navbar .container-fluid,
.navbar .container-lg,
.navbar .container-md,
.navbar .container-sm,
.navbar .container-xl {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
}

.navbar {
    position: relative;
    padding: 0.5rem 1rem;
}

article,
aside,
figcaption,
figure,
footer,
header,
hgroup,
main,
nav,
section {
    display: block;
}

*,
:after,
:before {
    box-sizing: border-box;
}

.App {
    text-align: center;
    display: flex;
    min-height: 100vh;
    flex-direction: column;
}

body {
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    text-align: left;
    background-color: #fff;
}

.navbar-nav .nav-link {
    padding-right: 0;
    padding-left: 0;
}

.navbar-dark .navbar-nav .nav-link {
    color: hsla(0, 0%, 100%, .5);
}

.nav-link,
.nav-link:hover {
    font-family: Questrial, sans-serif;
}

.nav-link {
    color: #ccc !important;
}

.nav-link {
    display: block;
    padding: 0.5rem 1rem;
}

a,
a:hover {
    color: #00a180;
}

a {
    color: #007bff;
    text-decoration: none;
    background-color: initial;
}

.navbar-nav {
    display: flex;
    flex-direction: column;
    padding-left: 0;
    margin-bottom: 0;
    list-style: none;
}


.nav {
    display: flex;
    flex-wrap: wrap;
    padding-left: 0;
    margin-bottom: 0;
    list-style: none;
}

dl,
ol,
ul {
    margin-top: 0;
}

ul {
    display: block;
    list-style-type: disc;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    padding-inline-start: 40px;
}

.navbar-collapse {
    flex-basis: 100%;
    flex-grow: 1;
    align-items: center;
}
</style>