---
layout: post
title: "Building a Real-Time Market Ticker"
date: 2024-12-24
categories: [components]
tags: [react, real-time, market-data]
---

# Real-Time Market Ticker Implementation

The market ticker displays live market data using React and Tailwind CSS.

## Component Structure
```jsx
const MarketTicker = () => {
  const [marketData, setMarketData] = useState([
    { symbol: 'NASDAQ', price: '14,897.24', change: '+1.2%', trending: true },
    { symbol: 'S&P 500', price: '4,754.63', change: '+0.8%', trending: true }
  ]);

  useEffect(() => {
    // Update logic
  }, []);

  return (
    // Rendering logic
  );
};
```

## Styling
```scss
.animate-ticker {
  animation: ticker 30s linear infinite;
}
```

## Next Steps
- WebSocket integration
- Real market data API
- Performance optimization
