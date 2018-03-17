<template lang="html">
    <div class="container">
        <h2 is="sui-header" icon>
            <sui-icon name="vuejs" />
            Vue Template
            <sui-header-subheader>
                A simple boilerplate built with Vue.js, Webpack 4, and Semantic UI
            </sui-header-subheader>
        </h2>
    </div>
</template>
<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
.container {
  width: 100%;
  padding-top: 35px;
  display: flex;
  justify-content: space-around;
}
</style>

