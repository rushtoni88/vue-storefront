<template>
  <router-link to="/compare" class="compare-icon no-underline inline-flex" v-if="hasCompare">
    <i class="material-icons md-18">compare</i>
  </router-link>
</template>

<script>
import { coreComponent } from 'lib/themes'

export default {
  mixins: [coreComponent('core/blocks/Header/CompareIcon')]
}
</script>
