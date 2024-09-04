<template>
    <AuthLayout>
        <template #content>
            <Card>
                <template #title>Simple Card</template>
                <template #content>
                    <div class="vularent__form-group">
                        
                    </div>
                </template>
            </Card>
        </template>
    </AuthLayout>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'auth-layout',
})
</script>