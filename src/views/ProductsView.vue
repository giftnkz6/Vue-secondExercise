<template>
    <ProductsPage>
    </ProductsPage>
</template>

<script>
    import ProductsPage from "@/components/Products.vue"
    import SpinnerComponent from "@/components/Spinner.vue"
    export default{
        name: "ProductsView",
        components:{
            ProductsPage,
            SpinnerComponent
        }
    }
</script>