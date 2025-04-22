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
    <template #heading>Welcome to Bumblebee Studio</template>
    Bumblebee Studio is a web chat digital agency. We help businesses and organizations deploy,
    configure, and customize advanced chat bot solutions—including retrieval-augmented generation
    (RAG) bots—tailored to your needs. <br />
    <strong>Let us handle your conversational AI, so you can focus on your business!</strong>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Features</template>
    <ul>
      <li>⚡ Fast, responsive chat experience</li>
      <li>🤖 AI-powered answers and automation</li>
      <li>🎨 Customizable to match your brand</li>
      <li>📊 Analytics and insights</li>
      <li>🔒 Secure and privacy-focused</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Easy Integration</template>
    Our team integrates Bumblebee Studio chat bots with all major frameworks and platforms, ensuring
    a seamless experience for your users. <br />
    <a href="https://www.bbbstudio.au/docs" target="_blank" rel="noopener"
      >See how we can help you integrate conversational AI</a
    >.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Support & Community</template>
    Need help or want to share feedback? <br />
    <a href="mailto:support@bbbstudio.au">Contact our team</a> or join our
    <a href="https://discord.gg/bumblebee" target="_blank" rel="noopener">Discord community</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>About Bumblebee Studio</template>
    Bumblebee Studio is dedicated to making AI accessible and delightful for everyone. <br />
    <a href="https://www.bbbstudio.au/" target="_blank" rel="noopener">Learn more about us</a>.
  </WelcomeItem>
</template>
