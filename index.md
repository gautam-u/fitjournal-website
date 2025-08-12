---
layout: default
title: FitJournal - Privacy-First Fitness Tracking for iOS
---

<div class="hero animate-fade-in-up">
  <h1 class="text-gradient">Smart Home Workouts,<br>Your Privacy First</h1>
  <p class="mb-2xl">Create personalized workout plans with intelligent exercise selection, smart progression tracking, and exercise shuffling — all while keeping your data private and secure on your device.</p>
  
  <div style="display: flex; justify-content: center; margin-bottom: var(--spacing-4xl);">
    <a href="{{ site.appstore_link | default: '#' }}" class="btn btn-primary btn-large">
      <i class="fab fa-apple"></i>
      Download on App Store
    </a>
  </div>
</div>

<div class="screenshots">
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/home.png' | relative_url }}" alt="Equipment Selection - Choose Your Available Equipment">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/progress.png' | relative_url }}" alt="Smart Exercise Plan - AI-Powered Exercise Recommendations">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/smart_workout.png' | relative_url }}" alt="Dynamic Workout Interface with Exercise Shuffling">
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
        <i class="fas fa-magic"></i>
      </div>
      <h3>Smart Workout Intelligence</h3>
      <p>AI-powered exercise shuffling and progressive overload suggestions that adapt to your performance and keep workouts fresh.</p>
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
