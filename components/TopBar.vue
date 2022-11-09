<template>
  <SfTopBar class="topbar">
    <!-- <template #left>
      <SfButton class="sf-button--text">{{ $t('Help & FAQs') }}</SfButton>
    </template> -->
    <template #center>
      <p>Tylko oryginalne produkty</p>
      <!-- <SfButton class="topbar__button sf-button--text">{{ $t('Find out more') }}</SfButton> -->
    </template>
    <!-- <template #right>
      <LocaleSelector />
    </template> -->
  </SfTopBar>
</template>

<script>
import { SfButton, SfTopBar } from "@storefront-ui/vue"
// import LocaleSelector from "./LocaleSelector"

export default {
  components: {
    SfTopBar,
    SfButton,
    // LocaleSelector,
  },
}
</script>
<style lang="scss" scoped>
.topbar {
  position: relative;
  z-index: 2;
  height: 41px;
  background-color: var(--c-black);
  color: var(--c-white);
  /* &__button {
    margin: 0 0 0 var(--spacer-xs);
  } */
}
</style>
