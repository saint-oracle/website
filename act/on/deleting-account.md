---
layout: default
title: Deleting Your act/on Account
---

<style>
  .legal-container {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 16px;
  }
  
  .legal-card {
    position: relative;
    border-radius: 16px;
    --md-elevation-level: 2;
    background: var(--md-sys-color-surface, #fff);
    padding: 32px;
  }
  
  .legal-content h1 {
    color: var(--md-sys-color-on-surface, #1C1B1F);
    margin-bottom: 24px;
  }
  
  .legal-content h2 {
    color: var(--md-sys-color-on-surface-variant, #49454F);
    margin-top: 24px;
    margin-bottom: 12px;
  }
  
  .legal-content h3 {
    color: var(--md-sys-color-on-surface-variant, #49454F);
    margin-top: 16px;
    margin-bottom: 8px;
  }
  
  .legal-content p, .legal-content ul {
    color: var(--md-sys-color-on-surface-variant, #49454F);
    line-height: 1.6;
  }
  
  .legal-content ul {
    margin-left: 20px;
  }
  
  .back-button {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 10px 24px;
    margin-top: 24px;
    border-radius: 20px;
    background: var(--md-sys-color-primary, #339fc4ff);
    color: var(--md-sys-color-on-primary, #fff);
    text-decoration: none;
    font-weight: 500;
    transition: all 0.2s ease;
  }
  
  .back-button:hover {
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    transform: translateY(-1px);
  }
  
  .legal-footer {
    margin-top: 32px;
    padding-top: 24px;
    border-top: 1px solid var(--md-sys-color-outline-variant, #CAC4D0);
    font-style: italic;
    color: var(--md-sys-color-on-surface-variant, #49454F);
  }
  
  @media (max-width: 768px) {
    .legal-card {
      padding: 24px 16px;
    }
  }
</style>

<div class="legal-container">
  <div class="legal-card surface">
    <md-elevation></md-elevation>
    
    <div class="legal-content">
      <h1 class="md-typescale-headline-large">Deleting Your Account</h1>
      
      <p class="md-typescale-body-large">
        <strong>How to delete your act/on account and its associated data</strong>
      </p>

      <p class="md-typescale-body-large">
        The act/on app stores only the data needed to run the app including:
      </p>
      <ul class="md-typescale-body-large">
        <li>Email address</li>
        <li>App settings (from the Settings tab)</li>
        <li>Any lists, sections, and items created by you in the app</li>
      </ul>
      
      <p class="md-typescale-body-large">
        You can easily delete all your account data, right from within the app.
      </p>

      <h2 class="md-typescale-title-large">If you are signed in...</h2>
      <p class="md-typescale-body-large">
        Assuming you've actually connected an account using one of the third party authentication methods, go to the "Account" tab and press the "Delete account and data" button. You will be required to confirm on the next page. Once you do, your data will be immediately deleted and your authenticated status revoked.
      </p>

      <h2 class="md-typescale-title-large">If you are NOT signed in...</h2>
      <p class="md-typescale-body-large">
        If you have signed in before, and you wish to delete your data, you'll need to sign in using the same auth account provider (Google, Apple, etc) that you did originally. Once you do, you'll be able to delete all remote data from the Account tab, by pressing the "Delete account and data" button and following the succeeding prompts.
      </p>

      <h2 class="md-typescale-title-large">If you have never signed in...</h2>
      <p class="md-typescale-body-large">
        If you have never connected an account, nothing gets sent to our servers, and there is nothing to delete. You can, however, delete all data off of your device by pressing the "Delete local data" button from the Account tab.
      </p>

      <h2 class="md-typescale-title-large">If you have already deleted the app...</h2>
      <p class="md-typescale-body-large">
        If you have already deleted the app and do not wish to re-download it, you can request that all of your data is deleted by sending an email to:
      </p>
      
      <div style="display: flex; align-items: center; gap: 12px; margin-top: 12px;">
        <span class="md-typescale-body-large" style="font-family: monospace; background: var(--md-sys-color-surface-variant, #E7E0EC); padding: 8px 12px; border-radius: 8px;">
          saintoracleofficial@gmail.com
        </span>
        <button onclick="navigator.clipboard.writeText('saintoracleofficial@gmail.com').then(() => { this.textContent = 'Copied!'; setTimeout(() => this.textContent = 'Copy', 2000); })" 
                style="background: var(--md-sys-color-primary, #339fc4ff); color: var(--md-sys-color-on-primary, #fff); border: none; padding: 8px 16px; border-radius: 8px; cursor: pointer; font-size: 14px; font-weight: 500; transition: all 0.2s; min-width: 80px;">
          Copy
        </button>
        <a href="mailto:saintoracleofficial@gmail.com?subject=Account%20Deletion%20Request" 
           style="background: var(--md-sys-color-primary, #339fc4ff); color: var(--md-sys-color-on-primary, #fff); text-decoration: none; padding: 8px 16px; border-radius: 8px; font-size: 14px; font-weight: 500; transition: all 0.2s;"
           onmouseover="this.style.transform='translateY(-1px)'; this.style.boxShadow='0 2px 8px rgba(0,0,0,0.15)';"
           onmouseout="this.style.transform=''; this.style.boxShadow='';">
          Send Email
        </a>
      </div>

      <div class="legal-footer">
        <p class="md-typescale-body-medium">Last updated: {{ "now" | date: "%B %d, %Y" }}</p>
      </div>

      <a href="/" class="back-button md-typescale-label-large">
        ← Back to Home
      </a>
    </div>
  </div>
</div>