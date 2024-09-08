<template>

    <div class="vulacard">
        <div class="vulacard-header">
            <h1>Login</h1>
        </div>
        <div class="vulacard-body">
            <div class="vulaInput-group">
                <label for="" class="vulaInput-label">Email</label>
                <input type="text" name="" id="" class="vulaInput-control">
            </div>
            <div class="vulaInput-group">
                <label for="" class="vulaInput-label">password</label>
                <input type="password" name="" id="" class="vulaInput-control">
            </div>

            <button class="vulaButton">Login</button>
        </div>
    </div>

</template>

<script setup lang="ts">
definePageMeta({
  layout: "auth-layout",
});
</script>
