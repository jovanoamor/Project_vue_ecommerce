<script>
export default {
    name: "UnavailableProduct",
    props: {
        handleClick: {
            type: Function,
            required: true,
        },
        buttonName: {
            type: String,
            required: true,
        },
    },
};
</script>

<template>
    <div class="unavailable-product-container">
        <p>This product is unavailable</p>
        <button @click="handleClick">{{ buttonName }}</button>
    </div>
</template>

<style scoped src="../assets/styles/UnavailableProduct.css"></style>