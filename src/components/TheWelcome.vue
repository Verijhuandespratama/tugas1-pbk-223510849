<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>
    Saya lahir di selatpanjang 09 februari 2004, Sekarang saya tinggal di Pekanbaru Jl. Katio
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Riwayat Pendidikan</template>
    SMAN 5 PEKANBARU
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener"></a>
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a>
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"></a>

    <br />

    <code></code>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Riwayat Prestasi</template>
    Juara 1 O2SN Pencak Silat Tingkat Provinsi Tahun 2018
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Kontak Informasi</template>

    <a href="https://www.instagram.com/verijhuandespratama_" target="_blank"
      >@verijhuandespratama_</a
    >
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"></a>
    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hobi</template>
    Programming, Ngopi, Travelling
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>
  </WelcomeItem>
</template>
