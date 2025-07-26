---
layout: default
title: FitJournal - Privacy-First Fitness Tracking for iOS
---

<div class="hero animate-fade-in-up">
  <h1 class="text-gradient">Your Fitness Journey,<br>Your Privacy First</h1>
  <p class="mb-2xl">Track your workouts, visualize progress, and stay motivated with FitJournal — the minimalist fitness app that keeps your data private and secure on your device.</p>
  
  <div style="display: flex; justify-content: center; margin-bottom: var(--spacing-4xl);">
    <a href="{{ site.appstore_link | default: '#' }}" class="btn btn-primary btn-large">
      <i class="fab fa-apple"></i>
      Download on App Store
    </a>
  </div>
</div>

<div class="screenshots">
  <div class="screenshot">
    <img src="/assets/screenshots/home.png" alt="Home Tab Screenshot">
  </div>
  <div class="screenshot">
    <img src="/assets/screenshots/progress.png" alt="Progress Tab Screenshot">
  </div>
  <div class="screenshot">
    <img src="/assets/screenshots/smart_workout.png" alt="Smart Workout Screenshot">
  </div>
</div>

<section class="features">
  <div class="text-center mb-2xl">
    <h2>Everything You Need for Your Fitness Journey</h2>
    <p>Track, analyze, and improve your workouts with privacy and simplicity in mind.</p>
  </div>
  
  <div class="grid grid-3">
    {% for feature in site.features %}
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-{{ feature.fontawesome_icon_name }}"></i>
      </div>
      <h3>{{ feature.title }}</h3>
      <p>{{ feature.description }}</p>
    </div>
    {% endfor %}
    
    <!-- Additional consolidated features -->
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-mobile-alt"></i>
      </div>
      <h3>Native iOS Design</h3>
      <p>Built specifically for iOS with SwiftUI, featuring beautiful native design patterns and system integration.</p>
    </div>
    
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-chart-bar"></i>
      </div>
      <h3>Smart Analytics</h3>
      <p>Visualize your progress with intuitive charts and insights that help you understand your fitness patterns.</p>
    </div>
    
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-lock"></i>
      </div>
      <h3>Complete Privacy</h3>
      <p>Your workout data stays on your device. No cloud storage, no data mining, no tracking — just pure privacy.</p>
    </div>
  </div>
</section>
