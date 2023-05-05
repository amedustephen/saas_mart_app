# Rails 7 SaaS-enabled MarketPlace Starter App

Rails 7 starter boilerplate that you can clone and build your next online marketplace platform with Multi-tenancy SaaS component for suppliers

## Purpose

The goal is to provide a robust code base with all classic features of a SaaS-enabled B2C Marketplace already implemented. This way, you can focus your precious time and energy on added value right from the first day, instead of starting with a blank app.

Users familiar with rails should be able to build with this boilerplate without requiring extensive introduction.

    * No DSL
    * Avoid complex frontend functionality
    * Simplicity over efficiency

## Core Features

* Static pages

    * Home page - landing page to convince visitors to use the platform or buy products/services from partner suppliers
    * Landing page - for tenants(suppliers) that convince them why to join the platform
    * Classic pages - such as "about", "contact us", "terms", "policy", "faqs" 

* User authentication & authorization

    * Authentication through [Devise]
    * Advanced oAuth (connect multiple social accounts for one user)
    * User Account setting/profile update
    * Authorization (role-based access)

* Admin Panel 

    * Dashboard
    * User Management (invite, ban, unban, impersonate)
    * Settings - site settings, currencies, subscription plans, testimonials, countries, states, social media links 
    * Analytics

* Tenant Onboarding

    * New tenant registration
    * Admin Panel - Tenant Management (approve, decline)

* Tenant Admin Panel

    * Welcome page
    * My Organization - Locations, Memberhips, Products & Services
    * Settings - Subscription (add, change, cancel plan), [PayStack] payment & billing, Tenant Account settings  
    * Analytics

* Plan-based restrictions - limit access to different features

## Tech Stack


## Setup

    clone the repo
    edit secret credentials with postgresql database role username and password
    bundle

    setup and run dev server
    ```
    bin/setup
    bin/dev
    ```


* ...
