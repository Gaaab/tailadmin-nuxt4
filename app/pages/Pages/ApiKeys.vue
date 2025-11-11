<template>
  <admin-layout>
    <div>
      <PageBreadcrumb :pageTitle="currentPageTitle" />
      <ApikeysTable />
    </div>
  </admin-layout>
</template>

<script setup>
import ApikeysTable from '@/components/api/ApiKeysTable.vue';
import PageBreadcrumb from '@/components/common/PageBreadcrumb.vue';
import AdminLayout from '@/components/layout/AdminLayout.vue';
import { ref } from 'vue';
const currentPageTitle = ref('API Keys');
</script>
