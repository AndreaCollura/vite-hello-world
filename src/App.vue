:<template>
  
    <AppTitle />
    <AppJumbo/>
  
</template>

<script>
import AppTitle from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
  export default {
    name: 'App',
    components: {
      AppTitle,
      AppJumbo,
    
    }
    
    
  }
</script>

<style lang="scss" scoped>

</style>