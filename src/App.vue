<template>
  <q-layout view="hHh lpR fFf">
    <q-header elevated>
      <q-toolbar class="custom-toolbar">
        <div class="toolbar-center">
          <q-btn-dropdown class="custom-dropdown" label="Daftar Tugas Dimas" dropdown-icon="_">
            <q-list class="nav-list">
              <q-item clickable v-close-popup>
                <router-link to="/">
                  <q-item-section class="centered-section">
                    <q-item-label class="item-label">Cuaca</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas1">
                  <q-item-section class="centered-section">
                    <q-item-label class="item-label">Tugas 1</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas2">
                  <q-item-section class="centered-section">
                    <q-item-label class="item-label">Tugas 2</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas3">
                  <q-item-section class="centered-section">
                    <q-item-label class="item-label">Tugas 3</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas4">
                  <q-item-section class="centered-section">
                    <q-item-label class="item-label">Tugas 4</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas5">
                  <q-item-section class="centered-section">
                    <q-item-label class="item-label">Tugas 5</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas6">
                  <q-item-section class="centered-section">
                    <q-item-label class="item-label">Tugas 6</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
              <q-item clickable v-close-popup>
                <router-link to="/tugas7">
                  <q-item-section class="centered-section">
                    <q-item-label class="item-label">Tugas 7</q-item-label>
                  </q-item-section>
                </router-link>
              </q-item>
            </q-list>
          </q-btn-dropdown>
        </div>
      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view></router-view>
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  setup() {},
};
</script>

<style scoped>
.custom-toolbar {
  background-color: whitesmoke;
  color: whitesmoke;
  text-decoration: none;
  display: flex;
  justify-content: center;
  align-items: center;
}

.toolbar-center {
  display: flex;
  justify-content: center;
  text-align: center;
  width: 100%;
}

.custom-dropdown {
  color: #cd5c5c;
  background-color: whitesmoke;
}

.nav-list {
  color: #8b0000;
  background-color: whitesmoke;
  text-align: center;
}

.centered-section {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}

.q-item-section {
  color: #f5f5dc !important;
}

.item-label {
  color: #8b0000;
  text-align: center;
}
</style>
