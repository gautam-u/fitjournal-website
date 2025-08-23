---
layout: default
title: Privacy Policy
include_in_header: true
permalink: /privacy-policy/
---

<div class="content" style="max-width: 800px; margin: 0 auto;">
  <div class="text-center mb-2xl">
    <h1>Privacy Policy</h1>
    <p>Your privacy is our priority. Here's how Home Workout - FitJournal protects your personal information.</p>
    <p style="font-size: 0.9rem; color: var(--color-text-tertiary); margin-bottom: 0;">Last updated: {{ site.time | date: '%B %d, %Y' }}</p>
  </div>

  <div class="card" style="background: linear-gradient(135deg, var(--color-primary-green), var(--color-primary-blue)); color: white; margin-bottom: var(--spacing-2xl);">
    <div style="text-align: center;">
      <i class="fas fa-shield-alt" style="font-size: 3rem; margin-bottom: var(--spacing-lg); opacity: 0.9;"></i>
      <h2 style="color: white; margin-bottom: var(--spacing-lg);">Privacy-First Design</h2>
      <p style="color: rgba(255, 255, 255, 0.9); font-size: 1.1rem; margin-bottom: 0;">Home Workout - FitJournal is built from the ground up with your privacy in mind. Your fitness data stays on your device, always.</p>
    </div>
  </div>

  <div class="grid grid-2" style="margin-bottom: var(--spacing-4xl);">
    <div class="card">
      <h3><i class="fas fa-mobile-alt" style="color: var(--color-primary-blue); margin-right: var(--spacing-sm);"></i>Local Data Storage</h3>
      <p>All your workout data, preferences, and personal information are stored locally on your device using iOS secure storage mechanisms.</p>
      <ul style="margin-left: var(--spacing-lg); color: var(--color-text-secondary);">
        <li>No cloud storage of personal data</li>
        <li>No remote servers processing your information</li>
        <li>Data encrypted using iOS security features</li>
      </ul>
    </div>
    
    <div class="card">
      <h3><i class="fas fa-heart" style="color: var(--color-primary-red); margin-right: var(--spacing-sm);"></i>HealthKit Integration</h3>
      <p>FitJournal integrates with Apple HealthKit to sync your workout data with the Health app, but this data never leaves your device.</p>
      <ul style="margin-left: var(--spacing-lg); color: var(--color-text-secondary);">
        <li>Health data access requires your explicit permission</li>
        <li>You can revoke access at any time in iOS Settings</li>
        <li>Data syncs locally between FitJournal and Health app</li>
      </ul>
    </div>
  </div>

  <div class="card" style="margin-bottom: var(--spacing-2xl);">
    <h2>What We Don't Collect</h2>
    <div class="grid grid-2" style="margin-top: var(--spacing-lg);">
      <div>
        <h4 style="color: var(--color-primary-red);">❌ Personal Information</h4>
        <p style="margin-bottom: var(--spacing-lg);">No names, emails, or contact information unless you voluntarily contact us for help.</p>
        
        <h4 style="color: var(--color-primary-red);">❌ Health Data</h4>
        <p style="margin-bottom: 0;">Your workout data, body measurements, and health metrics stay on your device.</p>
      </div>
      <div>
        <h4 style="color: var(--color-primary-red);">❌ Usage Analytics</h4>
        <p style="margin-bottom: var(--spacing-lg);">We don't track how you use the app or collect behavioral data.</p>
        
        <h4 style="color: var(--color-primary-red);">❌ Location Data</h4>
        <p style="margin-bottom: 0;">FitJournal doesn't access or store your location information.</p>
      </div>
    </div>
  </div>

  <div class="card" style="margin-bottom: var(--spacing-2xl);">
    <h2>Technical Details</h2>
    <div style="margin-top: var(--spacing-lg);">
      <h4>Data Storage</h4>
      <p>FitJournal uses iOS Core Data and Keychain services to store your information securely on your device. This data is included in your device backups but remains encrypted and inaccessible to us.</p>
      
      <h4>App Updates</h4>
      <p>When you update FitJournal through the App Store, no personal information is transmitted to us. The App Store handles the update process independently.</p>
      
      <h4>Crash Reports</h4>
      <p>If you opt in to share crash data with Apple, technical information about app crashes may be sent to Apple and shared with us. This data does not include your personal fitness information.</p>
    </div>
  </div>

  <div class="card" style="margin-bottom: var(--spacing-2xl);">
    <h2>Your Rights</h2>
    <p>Since all data is stored on your device, you have complete control:</p>
    <ul style="margin-left: var(--spacing-lg); margin-top: var(--spacing-md);">
      <li><strong>Access:</strong> All your data is accessible within the app</li>
      <li><strong>Export:</strong> Data can be exported through Apple Health's export feature</li>
      <li><strong>Delete:</strong> Simply delete the app to remove all data</li>
      <li><strong>Portability:</strong> Your data syncs with Apple Health for use with other apps</li>
    </ul>
  </div>

  <div class="card">
    <h2>Contact Us</h2>
    <p>If you have questions about this privacy policy or FitJournal's privacy practices:</p>
    <div style="margin-top: var(--spacing-lg);">
      <a href="mailto:{{ site.email_address }}" class="btn btn-primary" style="margin-right: var(--spacing-md);">
        <i class="fas fa-envelope"></i>
        {{ site.email_address }}
      </a>
    </div>
    <p style="font-size: 0.9rem; color: var(--color-text-tertiary); margin-top: var(--spacing-lg); margin-bottom: 0;">We typically respond within 24-48 hours.</p>
  </div>
</div>
