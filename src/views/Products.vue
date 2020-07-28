<template>
    <div>
        <h1>這是產品列表</h1>
        <ProductList>這也是產品列表</ProductList>
    </div>
</template>

<script>
// @ is an alias to /src
import ProductList from '@/components/Products.vue';

export default {
  name: 'Products',
  components: {
    ProductList,
  },
};
</script>
