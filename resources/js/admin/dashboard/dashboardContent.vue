<template>
    <div>
        <content-header :title="title"/>
        <!-- Main content -->
        <section class="content">
        <div class="container-fluid">
            <secondary-header/>
        </div>
        </section>
        <!-- /.content -->
    </div>
</template>
<script>
import secondaryHeader from '../header/secondaryHeader'; 
import contentHeader from '../header/contentHeader';
export default {
    data: function () {
        return{
            title : "Dashboard"
        }
    },
     components : {
         secondaryHeader,
         contentHeader
     }
}
</script>