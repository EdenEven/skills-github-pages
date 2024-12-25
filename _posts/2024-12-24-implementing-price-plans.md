---
layout: post
title: "Implementing Pricing Plans"
date: 2024-12-24
categories: [components]
tags: [react, pricing, ui]
---

# Creating Dynamic Pricing Components

## Plan Structure
- Monthly: $119/month
- Annual: $1,299/year
- Enterprise: $17,000/year

## Component Implementation
```jsx
const PricingCard = ({ plan, price, features }) => (
  <div className="p-6 bg-gray-800 rounded-lg space-y-4">
    <h3>{plan}</h3>
    <p>{price}</p>
    <ul>{features.map(f => <li key={f}>{f}</li>)}</ul>
  </div>
);
```

## Payment Integration
- Stripe setup
- Subscription management
- Invoicing system
