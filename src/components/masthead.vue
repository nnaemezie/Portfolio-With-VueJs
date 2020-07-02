<template>
    <div>
        <header class="masthead">
            <div class="container h-100">
                <div class="row h-100 align-items-center justify-content-center text-center">
                    <div class="col-lg-10 align-self-end">
                        <img alt="avater" src="/assets/img/profile/team4.png" class="rounded-circle" style="width: 200px;height: 200px;">
                        <h2 class="lg-heading text-uppercase text-white mt-3">Halford .N. <span class="text-primary">Nze</span></h2>
                        <hr class="divider my-4" />
                    </div>
                    <div class="col-lg-8 align-self-baseline">
                        <h5 class="bg-light p-3 skills">Web Developer, Software Engr, Gamer and More...</h5>

                        <div class="icons p-4">
                            <a href="https://github.com/nnaemezie" target="_blank">
                                <i class="fab fa-github fa-fw fa-2x text-dark"></i>
                            </a>

                            <a href="https://www.linkedin.com/in/nze-halford-a16328183" target="_blank">
                                <i class="fab fa-linkedin-in fa-fw fa-2x text-info"></i>
                            </a>

                            <a href="https://www.facebook.com/nze.halford.5" target="_blank">
                                <i class="fab fa-facebook fa-fw fa-2x text-info"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </header>
    </div>
</template>

<script>
    export default {
        name: "masthead"
    }
</script>

<style scoped>
    .icons a{
        padding: 20px;
    }
    .skills{
        border-left: 10px solid rgb(243, 96, 58);
        border-right: 10px solid rgb(243, 96, 58);
    }
</style>