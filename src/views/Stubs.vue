<template>
  <div>
    <Header />
    <Lists />
    <CreateListModal />
  </div>
</template>

<script>
import Header from '../stubs/Header.vue';
import Lists from '../stubs/Lists.vue';
import CreateListModal from '../stubs/CreateListModal.vue';

export default {
  name: 'stubs',
  components: {
    Header,
    Lists,
    CreateListModal,
  }
}
</script>
