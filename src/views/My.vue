<template>
  <div>
    {{ $t("My.message") }}
    <button @click="$i18n.locale = 'ko_KR'">한국어</button>
    <button @click="$i18n.locale = 'en_US'">영어</button>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
