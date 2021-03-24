<template>
<div dir="rtl">
    <b-navbar toggleable="md" class="py-4 px-5 bg-dark" type="dark" variant="info">
      <b-navbar-brand class="font-weight-bold" href="#" style="font-size:1.7rem">
        <img src="../assets/Goobin.png" alt="Vector" width="30px">
        گوبین
        </b-navbar-brand>
      <b-navbar-toggle target="nav-collapse">
        <template #default="{ expanded }">
        <i v-if="expanded" class="bi-x" style="color:white"></i>
        <i v-else class="bi-list" style="color:white"></i>
      </template>
      </b-navbar-toggle>
      <b-collapse class="border-bottom-primary" id="nav-collapse" is-nav>
      <b-navbar-nav>
      <b-nav-item-dropdown lazy text="محصولات" right style="color: white !important;">
          <b-dropdown-item href="#">چت</b-dropdown-item>
          <b-dropdown-item href="#">وبینار</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item class="mx-2">درباره</b-nav-item>
        <b-nav-item class="mx-2">مشتری ها</b-nav-item>
        <b-nav-item class="mx-2">جوایز</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav class="mr-auto">
        <b-nav-item class="px-3 font-weight-bold">لاگین</b-nav-item>
      <b-dropdown-divider/>
        <button class="btn btn-outline-light px-4 font-weight-bold" style="font-size:1.4rem">شروع</button>
      </b-navbar-nav>
      </b-collapse>
    </b-navbar>
</div>
</template>

<style scoped>
  .nav-link,
  .navbar-nav{
    color:rgba(255,255,255,1) !important;
    font-size: 1.3rem;
  }
</style>