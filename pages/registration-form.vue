<script setup lang="ts">
</script>

<template>
  <h1>登録フォーム</h1>
  <div>
    <form action="">
      <TextField id="name" label="お名前" class="text-field" />
      <TextField type="email" id="email" label="メールアドレス" hint="数字と大文字をそれぞれ1文字以上含めて、8文字以上で入力してください。"
        class="text-field" />
      <TextField type="password" id="password" label="パスワード" class="text-field" />
    </form>
  </div>
</template>

<style scoped>
.text-field {
  margin-top: var(--space-32);
}
</style>
