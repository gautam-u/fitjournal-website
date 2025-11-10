---
layout: default
title: HomeGym Pro - Smart Home Workouts for iOS
---

<div class="hero animate-fade-in-up">
  <h1 class="text-gradient">HomeGym Pro<br>Smart Home Workouts</h1>
  <p class="mb-xl">Transform your home into a personal training studio with AI-powered workout plans, smart exercise selection, and comprehensive HealthKit integration. Start with 3 free workouts per week, or unlock unlimited access with Premium.</p>
  <p class="mb-2xl" style="color: var(--color-text-secondary); max-width: 680px; margin-left: auto; margin-right: auto;">Premium membership ($2.99/month or $19.99/year) unlocks unlimited workouts, removes ads, and provides advanced analytics — all while your data stays privately on your device.</p>

  <div style="display: flex; justify-content: center; margin-bottom: var(--spacing-4xl);">
    <a href="{{ site.appstore_link | default: '#' }}" class="btn btn-primary btn-large">
      <i class="fab fa-apple"></i>
      Download on the App Store
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
    <h2>Start Free, Upgrade When Ready</h2>
    <p>Begin with 3 free workouts per week and essential features. Upgrade to Premium for unlimited workouts, advanced analytics, and an ad-free experience.</p>
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
    <h2>Simple, Transparent Pricing</h2>
    <p>Try the free tier with no trial needed. Upgrade to Premium when you're ready for unlimited workouts and advanced features.</p>
  </div>

  <div class="grid grid-2">
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-calendar-check"></i>
      </div>
      <h3>Monthly Premium - $2.99/month</h3>
      <p>Perfect for getting started. Unlimited workouts, ad-free experience, advanced analytics, and custom workout builder with AI suggestions.</p>
    </div>
    <div class="card feature-card animate-fade-in-up">
      <div class="feature-icon">
        <i class="fas fa-award"></i>
      </div>
      <h3>Yearly Premium - $19.99/year</h3>
      <p>Best value! Save 44% with annual billing. All premium features including unlimited workouts, complete ad removal, and priority support.</p>
    </div>
  </div>
</section>

