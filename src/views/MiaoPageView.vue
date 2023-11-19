<script setup>
import PageHeader from '@/components/PageHeader.vue';
import AdvocateComponent from '@/components/AdvocateComponent.vue';
import LatestEvents from '@/components/LatestEvents.vue';
import PolicyIssues from '@/components/PolicyIssues.vue';
import DonateForm from '../components/DonateForm.vue';
import FooterNavbar from '../components/PageHeader/FooterNavbar.vue';
</script>
<template>
  <PageHeader />
  <AdvocateComponent />
  <LatestEvents />
  <PolicyIssues />
  <DonateForm />
  <PageSlogan />
  <PageFooter />
  <FooterNavbar />
</template>
<style lang="scss" scoped></style>
