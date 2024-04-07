<script setup>
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
    <h3>Education</h3>
    <template #heading>Documentation</template>
    senior high school :  <a href="http://www.smklabor.sch.id/" target="_blank" rel="noopener">SMK Labor Pekanbaru</a>
    <br>
    college : <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
  </WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>
    <h3>Skills</h3>
    Python
    <br>
    SQL
    <br>
    Microsoft Excel
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    Instagram :  <a href="https://www.instagram.com/ilhammm_d_/" target="_blank" rel="noopener"> click here</a><br>
    Github :     <a href="https://github.com/ilhammmdd" target="_blank" rel="noopener"> click here</a>
    <template #heading>Community</template>

  </WelcomeItem>
  
</template>
