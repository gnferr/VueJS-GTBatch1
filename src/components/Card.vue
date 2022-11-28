<template>
    <div class="card border-light">
        <a href=""><img :src="require('@/assets/' + cardImg + '.png')"></a>
        <div class="card-body">
            <p class="fw-bold">{{ cardTitle }}</p>
            <p>IDR {{ cardPrice }}</p>
        </div>
    </div>
</template>
<script>
export default {
    name: 'CardComponent',
    props: ['cardImg', 'cardTitle', 'cardPrice']
}
</script>