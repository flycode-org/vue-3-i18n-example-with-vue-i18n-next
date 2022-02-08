<template>
  <h1>{{ $t("title") }}</h1>
  <p>{{ $t("description") }}</p>
  <LocaleSwitcher />
</template>

<script>
import LocaleSwitcher from "./LocaleSwitcher.vue";

export default {
  name: "HelloI18n",
  components: { LocaleSwitcher },
};
</script>
