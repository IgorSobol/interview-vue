<template>
  <a-layout-content :style="{ padding: '0 50px', marginBottom: '50px'}">
    <div :style="{ background: '#fff', padding: '24px', minHeight: '280px' }">
      <CreateListModal />
      <div :style="{ marginBottom: '30px' }" class="gutter-example">
        <a-row :gutter="16">
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
        </a-row>

        <a-row :gutter="16">
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
        </a-row>

        <a-row :gutter="16">
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
          <a-col class="gutter-row" :span="6">
            <div class="gutter-box">
              <Card />
            </div>
          </a-col>
        </a-row>
      </div>
      <Pagination />
    </div>
  </a-layout-content>
</template>

<script>
import Card from './Card.vue'
import Pagination from './Pagination.vue'
import CreateListModal from '../stubs/CreateListModal.vue'

export default {
  name: 'Lists',
  components: {
    Card,
    Pagination,
    CreateListModal,
  }
}
</script>
