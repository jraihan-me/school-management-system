<template>
  <div class="wrapper">
    <navbar/>
    <sidebar/>
    <div class="content-wrapper">
      <dashboard-content />
    </div>
  </div>
</template>
<script>
import navbar from './header/navbar';
import sidebar from './sidebar/sidebar';
import dashboardContent from './dashboard/dashboardContent';
export default {
    components : {
      navbar,
      sidebar,
      dashboardContent
    }
}
</script>