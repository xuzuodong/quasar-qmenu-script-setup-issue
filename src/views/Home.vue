<template>
    <div>
        <h3 class="mb-10">This is a home page!</h3>

        <q-btn
            >open

            <q-menu>
                <q-list>
                    <q-item clickable v-close-popup>
                        <q-item-section>bar</q-item-section>
                    </q-item>
                    <q-item clickable v-close-popup>
                        <q-item-section>baz</q-item-section>
                    </q-item>
                </q-list>
            </q-menu>
        </q-btn>
    </div>
</template>

<!-- <script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({})
</script> -->

<script setup lang="ts">
</script>
