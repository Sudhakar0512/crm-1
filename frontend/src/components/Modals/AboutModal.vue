<template>
  <Dialog v-model="show" :options="{ size: 'sm' }">
    <template #body>
      <div class="p-4 pt-5">
        <div class="flex justify-center">
          <div class="flex flex-col items-center">
            <CRMLogo class="mb-3 size-12" />
            <h3 class="font-semibold text-xl text-ink-gray-9">Pumo CRM</h3>
          </div>
        </div>
        <hr class="border-t my-3 mx-2" />
        <p class="text-center text-sm text-ink-gray-7 mb-4 px-4">
          End-to-end management solution for our internal purposes — streamlined and efficient workflow with Pumo CRM.
        </p>
        
      </div>
    </template>
  </Dialog>
</template>
<script setup>
import { Tooltip } from 'frappe-ui'
import CRMLogo from '@/components/Icons/CRMLogo.vue'
import LucideGlobe from '~icons/lucide/globe'
import LucideGitHub from '~icons/lucide/github'
import LucideHeadset from '~icons/lucide/headset'
import LucideBug from '~icons/lucide/bug'
import LucideBookOpen from '~icons/lucide/book-open'
import TelegramIcon from '@/components/Icons/TelegramIcon.vue'

let show = defineModel()

let links = []
</script>
