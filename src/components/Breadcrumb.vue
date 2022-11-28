<template>
    <nav aria-label="breadcrumb">
        <ol class="breadcrumb p-4">
            <li class="breadcrumb-item "><a href="#" class="text-dark">Home</a></li>
            <li class="breadcrumb-item"><a href="#" class="text-dark">Office Room</a></li>
            <li class="breadcrumb-item" aria-current="page"><b>Detail</b></li>
        </ol>
    </nav>
</template>
<script>
export default {
    name: 'BreadcrumbComponent',
    props: {
        msg: String
    }
}
</script>

<style scoped>
li a {
    text-decoration: none;
}
</style>