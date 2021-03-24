<template>
<div dir="rtl">
    <b-navbar toggleable="md" class="py-4 px-5 bg-dark" type="dark" variant="info">
      <b-navbar-brand class="font-weight-bold" href="#">
        <img src="../assets/Goobin.png" alt="Vector" width="30px">
        گوبین
        </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse">
        <!-- <template #default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up">baz</b-icon>
        <b-icon v-else icon="chevron-bar-down">baste</b-icon>
      </template> -->
      </b-navbar-toggle>
      <b-collapse class="border-bottom-light" id="nav-collapse" is-nav>
      <b-navbar-nav>
      <b-nav-item-dropdown lazy text="محصولات" right style="color:rgba(255,255,255,1)">
          <b-dropdown-item href="#">چت</b-dropdown-item>
          <b-dropdown-item href="#">وبینار</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item class="mx-2">درباره</b-nav-item>
        <b-nav-item class="mx-2">مشتری ها</b-nav-item>
        <b-nav-item class="mx-2">جوایز</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav class="mr-auto">
        <b-nav-item class="px-3">لاگین</b-nav-item>
        <button class="btn btn-outline-light font-weight-bold">شروع</button>
      </b-navbar-nav>
      </b-collapse>
    </b-navbar>
</div>
</template>

<style scoped>
  .nav-link{
    color:rgba(255,255,255,1) !important;
  }
</style>