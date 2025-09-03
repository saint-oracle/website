---
layout: default
title: act/on Terms of Use
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
      <h1 class="md-typescale-headline-large">act/on Terms of Service</h1>
      
      <p class="md-typescale-body-large">
        act/on is created by Saint Oracle LLC development studios, referred to here as "Saint Oracle LLC"
      </p>

      <h2 class="md-typescale-title-large">1. Acceptance of Terms</h2>
      <p class="md-typescale-body-large">
        By accessing or using act/on (the "App" or "Service"), you agree to be bound by these Terms of Service and our Privacy Policy. If you do not agree, do not use the Service.
      </p>

      <h2 class="md-typescale-title-large">2. Definitions</h2>
      <ul class="md-typescale-body-large">
        <li>"User," "you," or "your" refers to anyone who accesses or uses the Service.</li>
        <li>"Content" means any data or materials you create, upload, or submit within the App, including but not limited to Pages, Sections, Items, and images.</li>
        <li>"Service Provider" means any third party that facilitates the operation of the Service (e.g., hosting, analytics).</li>
      </ul>

      <h2 class="md-typescale-title-large">3. Account Registration</h2>
      <ul class="md-typescale-body-large">
        <li>You can optionally register for an account in order to sync your data across devices.</li>
        <li>You are responsible for maintaining the security of your third party accounts, or if applicable, password and account data and for all activities that occur under your account.</li>
      </ul>

      <h2 class="md-typescale-title-large">4. License Grant</h2>
      <p class="md-typescale-body-large">
        Subject to these Terms, we grant you a non-exclusive, non-transferable, revocable license to use the App on your personal devices in accordance with this Agreement.
      </p>

      <h2 class="md-typescale-title-large">5. User Content</h2>
      <ul class="md-typescale-body-large">
        <li>You retain ownership of all Content you submit or create in the App.</li>
        <li>You grant Saint Oracle LLC and the act/on app permission to access, store, and display your Content solely to operate, provide, and improve the Service.</li>
      </ul>

      <h2 class="md-typescale-title-large">6. Acceptable Use</h2>
      <p class="md-typescale-body-large">You agree not to:</p>
      <ul class="md-typescale-body-large">
        <li>Use the Service for any unlawful purpose.</li>
        <li>Interfere with or disrupt the Service or servers/networks.</li>
        <li>Attempt to gain unauthorized access to any part of the Service.</li>
      </ul>

      <h2 class="md-typescale-title-large">7. Optional Cloud Sync</h2>
      <p class="md-typescale-body-large">
        When you enable sync, your Content is stored in the act/on cloud, hosted by Supabase.
      </p>

      <h2 class="md-typescale-title-large">8. Fees and Payment</h2>
      <ul class="md-typescale-body-large">
        <li>Using the app locally is free.</li>
        <li>When syncing across devices, a paid, recurring subscription plan is required.</li>
        <li>We may introduce additional paid features or subscription plans in the future; if so, you will have the option to opt in, and payment terms will be clearly stated.</li>
      </ul>

      <h2 class="md-typescale-title-large">9. Intellectual Property</h2>
      <p class="md-typescale-body-large">
        The App and its original content, features, and functionality are and will remain the exclusive property of Saint Oracle LLC and its licensors.
      </p>

      <div class="legal-footer">
        <p class="md-typescale-body-medium">Last updated: {{ "now" | date: "%B %d, %Y" }}</p>
      </div>

      <a href="/" class="back-button md-typescale-label-large">
        ← Back to Home
      </a>
    </div>
  </div>
</div>