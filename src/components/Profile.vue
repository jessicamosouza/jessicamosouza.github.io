<template>
    <div id="wrapper">
        <div class="content center is-large">
            <h1 class="is-1 mt-5">{{ msg }}</h1>
            <p class="is-2">Software Engineer & BSc Computer Science Student</p>
            <div class="columns is-centered navbar-menu">
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
                        href="https://linkedin.com/in/jessicamosouza"
                        target="_blank"
                        rel="noopener"
                    ><i class="fa-brands fa-linkedin"></i></a
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

<style>
i {
    color: #000000;
}

.center {
    display: flex;
    flex-direction: column;
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
    margin: 0 0 30px;
}

@media screen and (min-width: 1px) {
    .columns {
        display: flex;
    }

    .navbar-menu {
        box-shadow: 0 0;
    }
}



</style>
