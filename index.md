---
layout: default
title: HomeGym Pro - Premium Home Workouts for iOS
---

<div class="hero animate-fade-in-up">
  <h1 class="text-gradient">HomeGym Pro<br>Premium Home Workouts</h1>
  <p class="mb-xl">HomeGym Pro brings studio-quality training to your living room with adaptive workout plans, AI coaching, and HealthKit sync. Start free, then upgrade to Pro memberships for deeper analytics and curated programs — all while your data stays securely on your device.</p>
  <p class="mb-2xl" style="color: var(--color-text-secondary); max-width: 680px; margin-left: auto; margin-right: auto;">Monthly and yearly HomeGym Pro memberships unlock advanced programming, premium support, and an ever-growing library of home workout collections.</p>
  
  <div style="display: flex; justify-content: center; margin-bottom: var(--spacing-4xl);">
    <a href="{{ site.appstore_link | default: '#' }}" class="btn btn-primary btn-large">
      <i class="fab fa-apple"></i>
      Get HomeGym Pro on the App Store
    </a>
  </div>
</div>

<div class="screenshots">
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/HomeWorkout_01_PersonalizedWorkoutPlan.png' | relative_url }}" alt="Personalized Workout Plan overview in HomeGym Pro">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/HomeWorkout_02_DailyWorkouts.png' | relative_url }}" alt="Daily HomeGym Pro workouts tailored to your equipment">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/HomeWorkout_03_SmartSuggestions.png' | relative_url }}" alt="AI workout suggestions keeping each session fresh">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/HomeWorkout_04_HomeGymSetup.png' | relative_url }}" alt="HomeGym Pro setup screen highlighting home gym integration">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/HomeWorkout_08_MonthlyPremium.png' | relative_url }}" alt="Monthly Premium membership details for HomeGym Pro">
  </div>
  <div class="screenshot">
    <img src="{{ '/assets/screenshots/HomeWorkout_09_YearlyPremium.png' | relative_url }}" alt="Yearly Premium membership upgrade options in HomeGym Pro">
  </div>
</div>

<section class="features">
  <div class="text-center mb-2xl">
    <h2>Train Smarter with HomeGym Pro</h2>
    <p>On-device intelligence, adaptive programming, and seamless HealthKit sync keep every workout fast, focused, and private.</p>
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
  </div>
</section>

<section class="features">
  <div class="text-center mb-2xl">
    <h2>Flexible HomeGym Pro Memberships</h2>
    <p>Choose the upgrade path that matches your commitment and unlock the full premium experience.</p>
  </div>
  
  <div class="grid grid-2">
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-calendar-check"></i>
      </div>
      <h3>Monthly Pro Access</h3>
      <p>Stay flexible with a monthly membership that delivers advanced workouts, recovery guidance, and priority support.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-award"></i>
      </div>
      <h3>Yearly Pro Access</h3>
      <p>Commit to your goals with the best-value plan, including exclusive collections, deeper performance reporting, and seasonal challenges.</p>
    </div>
  </div>
</section>

