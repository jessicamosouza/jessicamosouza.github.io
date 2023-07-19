<template>
    <div id="wrapper">
        <div class="content center is-large">
            <h1 class="is-1 mt-5">{{ msg }}</h1>
            <p class="is-2">Software Engineer & BSc Computer Science Student</p>
            <div class="columns is-centered is-multiline navbar-menu">
                <div class="column is-narrow">
                    <a
                        href="https://github.com/jessicamosouza"
                        target="_blank"
                        rel="noopener"
                    ><i class="fa-brands fa-square-github"></i></a
                    >
                </div>
                <div class="column is-narrow">
                    <a
                        href="https://linkedin.com/in/jehhmarques"
                        target="_blank"
                        rel="noopener"
                    ><i class="fa-brands fa-linkedin"></i></a
                    >
                </div>
                <div class="column is-narrow">
                    <a
                        href="https://twitter.com/whatever_jess"
                        target="_blank"
                        rel="noopener"
                    ><i class="fa-brands fa-square-twitter"></i></a
                    >
                </div>
                <div class="column is-narrow">
                    <a
                        href="https://bsky.app/profile/jehh.dev"
                        target="_blank"
                        rel="noopener"
                    ><i class="fa-solid fa-cloud"></i></a
                    >
                </div>
                <div class="column is-narrow">
                    <a
                        href="https://hachyderm.io/@jessicasouza"
                        target="_blank"
                        rel="noopener"
                    ><i class="fa-brands fa-mastodon"></i></a
                    >
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
    name: `Profile`,
    props: {
        msg: String
    }
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
i {
    color: #000000;
}

template {
    height: 100vh;
}

.center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 98vh;
}

h1 {
    font-family: "nottinghamsans", sans-serif;
    font-weight: 600;
    text-align: center;
    margin: 0 0 24px;
}

p {
    font-family: "givonicregular", sans-serif;
    font-weight: 300;
    text-align: center;
    margin: 0 0 24px;
}

</style>
