<template>
     <footer class="bg-light py-5">
            <div class="container px-4 px-lg-5"><div class="small text-center text-muted">Copyright &copy; 2022 - {{devName}}</div></div>
    </footer>
</template>

<script>
export default({
    props: {
        devName: String
    },

})
</script>
