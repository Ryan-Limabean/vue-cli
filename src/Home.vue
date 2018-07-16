<template>
 <div>
  <app-servers v-for="server in 5"></app-servers>
  </div>
</template>


<script>
  import ServerStatus from './ServerStatus.vue';

    export default {
    components: {
        'app-server-status': ServerStatus
    }
    
}
</script>
