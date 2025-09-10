---
layout: default
title: Contact Us
---

<div class="contact-page">
  <div class="contact-container">
    <h1 class="md-typescale-display-small">Contact Us</h1>

    <div class="contact-info">
      <p class="md-typescale-body-medium">
        Email us at:
      </p>

      <div class="email-container">
        <code class="email-text">contact@saintoracle.com</code>

        <div class="button-group">
          <button onclick="navigator.clipboard.writeText('contact@saintoracle.com').then(() => { this.textContent = 'Copied!'; setTimeout(() => this.textContent = 'Copy', 2000); })"
                  class="md-outlined-button">
            Copy
          </button>
        </div>
      </div>
    </div>

    <div class="back-link">
      <a href="/" class="md-typescale-body-medium">← Back to Home</a>
    </div>

  </div>
</div>

<style>
.contact-page {
  display: flex;
  justify-content: center;
  padding: 2rem 1rem;
}

.contact-container {
  max-width: 600px;
  width: 100%;
  text-align: center;
}

.contact-container h1 {
  margin-bottom: 0rem;
}

.contact-container > p {
  margin-bottom: 2rem;
  color: var(--md-sys-color-on-surface-variant);
}

.contact-info {
  background: var(--md-sys-color-surface-container-lowest);
  border-radius: 12px;
  padding: 2rem;
  margin-bottom: 2rem;
}

.email-container {
  margin-top: 1rem;
}

.email-text {
  display: inline-block;
  font-size: 1.1rem;
  padding: 0.5rem 1rem;
  background: var(--md-sys-color-surface-container);
  border-radius: 8px;
  margin-bottom: 1.5rem;
  word-break: break-all;
}

.button-group {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.md-outlined-button,
.md-filled-button {
  padding: 0.75rem 1.5rem;
  border-radius: 20px;
  font-family: inherit;
  font-size: 0.875rem;
  font-weight: 500;
  text-decoration: none;
  cursor: pointer;
  transition: all 0.2s ease;
  border: none;
}

.md-outlined-button {
  background: transparent;
  color: var(--md-sys-color-primary);
  border: 1px solid var(--md-sys-color-outline);
}

.md-outlined-button:hover {
  background: var(--md-sys-color-primary-container);
}

.md-filled-button {
  background: var(--md-sys-color-primary);
  color: var(--md-sys-color-on-primary);
  display: inline-block;
}

.md-filled-button:hover {
  background: var(--md-sys-color-primary-container);
  color: var(--md-sys-color-on-primary-container);
}

.back-link {
  margin-top: 2rem;
}

.back-link a {
  color: var(--md-sys-color-primary);
  text-decoration: none;
}

.back-link a:hover {
  text-decoration: underline;
}

@media (max-width: 480px) {
  .button-group {
    flex-direction: column;
  }
  
  .md-outlined-button,
  .md-filled-button {
    width: 100%;
  }
}
</style>
