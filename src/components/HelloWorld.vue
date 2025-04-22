<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="bumblebee-bg">
    <div class="branding">
      <!-- <img src="https://www.bbbstudio.au/logo.svg" alt="Bumblebee Studio Logo" class="logo" /> -->
      <h1>Bumblebee Studio</h1>
      <h2>Innovative Chat Widget & Bot Solutions</h2>
      <p class="tagline">
        Empowering your business with seamless, interactive customer engagement.
      </p>
    </div>
    <div class="demo-highlight">
      <div class="chat-widget-demo">
        <span class="chat-bubble">Hi there! 👋<br />How can I help you today?</span>
        <span class="chat-bubble user">Show me a demo of your chat bot!</span>
      </div>
      <p class="demo-note">
        This is a live demo background for our chat widget/bot.<br />Visit
        <a href="https://www.bbbstudio.au/" target="_blank">www.bbbstudio.au</a> to learn more.
      </p>
    </div>
  </div>
</template>

<style scoped>
.bumblebee-bg {
  min-height: 60vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #fffbe6 0%, #ffe066 100%);
  padding: 2rem 1rem;
  border-radius: 24px;
  box-shadow: 0 4px 24px rgba(255, 224, 102, 0.15);
}
.branding {
  text-align: center;
  margin-bottom: 2rem;
}
.logo {
  width: 80px;
  margin-bottom: 1rem;
}
.branding h1 {
  font-size: 2.4rem;
  color: #f9b800;
  margin: 0;
  font-weight: 700;
}
.branding h2 {
  font-size: 1.4rem;
  color: #222;
  margin: 0.5rem 0 0.5rem 0;
  font-weight: 500;
}
.tagline {
  color: #555;
  font-size: 1.1rem;
  margin-bottom: 0;
}
.demo-highlight {
  background: #fffde7;
  border-radius: 16px;
  padding: 1.5rem 1rem;
  box-shadow: 0 2px 12px rgba(249, 184, 0, 0.08);
  width: 100%;
  max-width: 400px;
  text-align: center;
}
.chat-widget-demo {
  display: flex;
  flex-direction: column;
  gap: 0.7rem;
  margin-bottom: 1rem;
}
.chat-bubble {
  display: inline-block;
  background: #f9b800;
  color: #fff;
  padding: 0.7rem 1.2rem;
  border-radius: 18px 18px 18px 4px;
  font-size: 1rem;
  max-width: 90%;
  text-align: left;
  box-shadow: 0 1px 4px rgba(249, 184, 0, 0.12);
}
.chat-bubble.user {
  background: #fff;
  color: #f9b800;
  align-self: flex-end;
  border-radius: 18px 18px 4px 18px;
  border: 1px solid #f9b800;
}
.demo-note {
  font-size: 0.95rem;
  color: #888;
  margin-top: 0.5rem;
}
.demo-note a {
  color: #f9b800;
  text-decoration: underline;
}
@media (min-width: 600px) {
  .bumblebee-bg {
    min-height: 70vh;
    padding: 3rem 2rem;
  }
  .demo-highlight {
    max-width: 500px;
  }
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
