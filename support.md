---
layout: default
title: Support
include_in_header: true
permalink: /support/
---

<div class="content" style="max-width: 700px; margin: 0 auto;">
  <div class="text-center mb-2xl">
    <h1>How Can We Help?</h1>
    <p>Get support, report issues, or share feedback about FitJournal.</p>
  </div>

  <div class="grid grid-2">
    <div class="card">
      <h3><i class="fas fa-envelope" style="color: var(--color-primary-blue); margin-right: var(--spacing-sm);"></i>Email Support</h3>
      <p>For technical issues, feature requests, or general questions:</p>
      <a href="mailto:{{ site.email_address }}" class="btn btn-primary">{{ site.email_address }}</a>
      <p style="font-size: 0.9rem; margin-top: var(--spacing-md); margin-bottom: 0; color: var(--color-text-tertiary);">We typically respond within 24-48 hours</p>
    </div>
    
    <div class="card">
      <h3><i class="fas fa-bug" style="color: var(--color-primary-red); margin-right: var(--spacing-sm);"></i>Bug Reports</h3>
      <p>Found a bug? Help us improve FitJournal by reporting it:</p>
      <a href="mailto:{{ site.email_address }}?subject=Bug Report - FitJournal" class="btn btn-secondary">Report Bug</a>
      <p style="font-size: 0.9rem; margin-top: var(--spacing-md); margin-bottom: 0; color: var(--color-text-tertiary);">Please include your device model and iOS version</p>
    </div>
  </div>

  <div class="card" style="margin-top: var(--spacing-2xl); text-align: center;">
    <h3>Frequently Asked Questions</h3>
    
    <div style="text-align: left; margin-top: var(--spacing-xl);">
      <div style="margin-bottom: var(--spacing-xl);">
        <h4 style="color: var(--color-primary-blue); margin-bottom: var(--spacing-sm);">Is my data secure?</h4>
        <p style="margin-bottom: 0;">Yes! FitJournal stores all your workout data locally on your device. We don’t collect, store, or share your personal fitness information.</p>
      </div>
      
      <div style="margin-bottom: var(--spacing-xl);">
        <h4 style="color: var(--color-primary-green); margin-bottom: var(--spacing-sm);">How do I sync with Apple Health?</h4>
        <p style="margin-bottom: 0;">FitJournal integrates seamlessly with HealthKit. Simply grant permissions when prompted, and your workout data will automatically sync with the Health app.</p>
      </div>
      
      <div style="margin-bottom: 0;">
        <h4 style="color: var(--color-primary-purple); margin-bottom: var(--spacing-sm);">Can I export my data?</h4>
        <p style="margin-bottom: 0;">Since your data is stored locally and synced with Apple Health, you can access it through the Health app’s export feature or by backing up your device.</p>
      </div>
    </div>
  </div>

  <div style="text-align: center; margin-top: var(--spacing-4xl);">
    <h3>Love FitJournal?</h3>
    <p>Help us spread the word by leaving a review on the App Store!</p>
    <a href="{{ site.appstore_link | default: '#' }}" class="btn btn-primary">
      <i class="fas fa-star"></i>
      Rate on App Store
    </a>
  </div>
</div>
