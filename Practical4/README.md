# Netflix Streaming Platform - Domain Model

## Overview

This domain model shows the important components and how they are connected to provide a smooth streaming experience. The system is divided into five main areas: 

## Domain Structure

The Netflix platform consists of five interconnected domains:

### 1. Subscription
This domain handles all subscription-related processes:
- **Subscription Plan**: Different levels of service offerings
- **Payment Gateway**: Processes subscription payments
- **Account Renewal**: Handles subscription renewals
- **Payment Cancellation**: Manages subscription cancellation and refunds

### 2. User Management & Personalization
This domain focuses on user identity and personalized experiences:
- **User**: Central entity representing the customer
- **User Registration**: Onboarding of new users
- **Email Authentication**: Verification and security
- **Multi-Account Management**: Handles multiple profiles under one subscription
- **Search for Content**: Enables users to find specific content
- **Recommendation System**: Offers customized content suggestions
- **View History and Preference**: Tracks user view history and preferences

### 3. Streaming Technology & Infrastructure
This domain manages the technical delivery of content:
- **Multi-screen Viewing**: Enables viewing across different devices
- **Adaptive Streaming**: Adjusts streaming quality based on network conditions

### 4. Customer Support and Feedback
This domain handles user assistance and community engagement:
- **Help Center and FAQs**: Provides self-service support resources
- **Content Rating and Reviews**: Collects and displays user feedback on content

### 5. Content Management
This domain oversees the content library:
- **Content Licensing**: Manages rights for streaming third-party content
- **Netflix Original Production**: Oversees Netflix-produced content
- **Content Delivery Network Optimization**: Ensures efficient global content delivery

## Key Relationships

The domain model illustrates several important relationships:

- **User → Subscription**: Users have subscription plans that determine their service level
- **User → Multiple Features**: Users can access search, recommendations, and multi-account management
- **Recommendation System ← View History**: Recommendations are influenced by viewing habits
- **Content Rating → Recommendation System**: User ratings influence recommendations
- **Streaming Technology ← Content Management**: Content delivery is optimized through the network
- **User → Customer Support**: Users can access help and provide content ratings

## Link 

[Netflix Domain Model](https://online.visual-paradigm.com/share.jsp?id=333936313330352d31&email=02230302.cst@rub.edu.bt#diagram:workspace=bbjvhilc&proj=0&id=1)