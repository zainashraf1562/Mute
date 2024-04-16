# Mute

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

Mute is a mobile app designed to introduce users to new music tailored to their listening preferences and moods. Using AI algorithms, it offers personalized music recommendations, curated playlists, and mood-based song suggestions to enhance the user's Mute experience.

### App Evaluation

- **Category:** Music Discovery & Recommendation
- **Mobile:** Mobile-first approach ensures accessibility and real-time music recommendations. Users can instantly explore new tracks and playlists tailored to their mood.
  
- **Story:** Connects users with their favorite music genres and moods. Enables users to find new music that resonates with their personal preferences, creating a personalized music journey.
  
- **Market:** Targeted at music enthusiasts, casual listeners, and anyone interested in exploring diverse music genres. Potential for partnerships with music streaming services for monetization.
  
- **Habit:** Encourages users to explore and listen to new music daily. With personalized recommendations, users are motivated to engage frequently to discover new tracks and playlists.
  
- **Scope:** 
  - **V1**: Focuses on personalized music recommendations and mood-based playlists. Users can create profiles to manage preferences and playlists.
  - **V2**: Introduces social sharing features allowing users to share favorite tracks or playlists with friends.
  - **V3**: Adds a collaborative playlist feature where users can create and share playlists with others.
  - **V4**: Incorporates a community aspect with user reviews and ratings for tracks and playlists.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Personalized Music Recommendations
* Tending Music Recommendations

**Optional Nice-to-have Stories**

* Social Sharing of Favorite Tracks/Playlists
* User Profile Management

### 2. Screen Archetypes

- **Home Screen**
  * Display personalized music recommendations
  * Navigate to Search Screen
  * Navigate to Trending Screen

- **Search Screen**
  * Enables users to search for artists, albums, or tracks
  * Navigate to Home Screen (to view recommendations based on search)

- **Trending Screen**
  * Display trending music
  * Navigate to Search Screen
  * Navigate to Home Screen
 
-**Music Detail Screen**
  * Song Details
  * Song lyrics

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home -> Home Screen
* Search -> Search Screen        ->Song Detail Screen
* Trending -> Trending Screen

**Flow Navigation** (Screen to Screen)

- [ ] Home Screen
  * Navigate to Search Screen
  * Navigate to Trending Screen
  * Navigate to Song Detail Screen
  
- [ ] Search Screen
  * Navigate to Home Screen
  * Navigate to Trending Screen
  * Navigate to Song Detail Screen
  
- [ ] Trending Screen
  * Navigate to Home Screen
  * Navigate to Trending Screen
  * Navigate to Song Detail Screen

## Wireframes

<img width="528" alt="Screenshot 2024-04-16 at 12 53 17 AM" src="https://github.com/zainashraf1562/Mute/assets/155921778/f11552b7-e5ae-416d-9797-1741acdd9b72">



## Schema 

[This section will be completed in Unit 9]

### Models

[Add table of models]

### Networking

- [Add list of network requests by screen]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Spotify]
