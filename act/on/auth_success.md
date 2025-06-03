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
  setTimeout(() => {
    // Grab the full query string (e.g. "?token=abc&user_id=123")
    const queryString = window.location.search;

    // Construct the deep link URL with query string
    const deepLink = `acton://auth_success${queryString}`;

    // Redirect to app
    window.location.href = deepLink;
  }, 1000);
</script>
