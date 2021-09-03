<!--
 * @Author: lough
 * @Date: 2021-09-03 16:31:53
 * @LastEditors: lough
 * @LastEditTime: 2021-09-03 16:43:34
 * @Description: 1
-->
<template>
  <div>
    1
  </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  name: 'EducationAnalyse',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>

</style>
