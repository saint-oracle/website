---
layout: default
title: Auth Success
permalink: /act/on/auth_success
---

<div style="display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; min-height: 80vh; padding: 24px;">

  <img src="/assets/images/cues_logo_and_text.png" alt="act/on logo" style="width: 120px; height: 120px; object-fit: contain; margin-bottom: 24px;" />

  <h1 class="md-typescale-headline-small" style="margin-bottom: 16px;">Authentication successful 🎉 </h1>

  <p class="md-typescale-body-medium" style="max-width: 400px;">
    Welcome to <strong>act/on</strong> — your private space to get things done.<br />
    You can close this tab.
  </p>

</div>

<script>
// Try to open the app automatically after short delay
setTimeout(() => {
  window.location.href = "acton://auth_success";
}, 1000);
</script>
