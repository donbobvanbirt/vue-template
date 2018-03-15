<template lang="html">
    <div v-bind:style="containerStyle">
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
  name: 'app',
  data() {
    return {
      containerStyle: {
        width: `100%`,
        display: 'flex',
        'justify-content': 'space-around',
        'align-items': 'center',
        height: '50%'
      }
    }
  }
}
</script>
