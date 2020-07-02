<template>
    <div>
        <footer class="bg-light py-5">
            <div class="container">
                <div class="small text-center text-muted">Copyright © {{date}} - Halford .N. Nze</div>
            </div>
        </footer>
    </div>
</template>

<script>
    export default {
        name: "footer",

        data(){
            return{
                'date' : new Date().getFullYear()
            }
        }
    }
</script>

<style scoped>

</style>