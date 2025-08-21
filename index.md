---
layout: default
title: FitJournal - Privacy-First Fitness Tracking for iOS
---

<div class="hero animate-fade-in-up">
  <h1 class="text-gradient">Smart Home Workouts,<br>Your Privacy First</h1>
  <p class="mb-2xl">Experience the future of fitness with intelligent workout planning, live timer controls, and AI-powered exercise suggestions. Create personalized training plans that adapt to your progress — all while keeping your data private and secure on your device.</p>
  
  <div style="display: flex; justify-content: center; margin-bottom: var(--spacing-4xl);">
    <a href="{{ site.appstore_link | default: '#' }}" class="btn btn-primary btn-large">
      <i class="fab fa-apple"></i>
      Download on App Store
    </a>
  </div>
</div>

<div class="screenshots">
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/home.png' | relative_url }}" alt="Today's Workout - Smart Exercise Selection with AI Suggestions">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/smart-workout.png' | relative_url }}" alt="Active Workout - Live Timer with Set Tracking and Progress">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/workout-plan-days.png' | relative_url }}" alt="Smart Workout Plan - Customize Exercise Sets and Difficulty">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/workout-style.png' | relative_url }}" alt="Workout Style Selection - Flexible Training Options">
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
        <i class="fas fa-stopwatch"></i>
      </div>
      <h3>Live Workout Timer</h3>
      <p>Built-in workout timer with pause, stop, and settings controls. Track your workout duration in real-time with precise timing.</p>
    </div>
    
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-magic"></i>
      </div>
      <h3>AI-Powered Suggestions</h3>
      <p>Smart exercise recommendations that learn from your performance. Get intelligent suggestions to level up your workout intensity.</p>
    </div>
    
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-cogs"></i>
      </div>
      <h3>Flexible Workout Styles</h3>
      <p>Choose between full-body workouts or muscle group splits. Customize your training days and structure to match your lifestyle.</p>
    </div>
  </div>
</section>
