# Pathly-Landing-Page
This is my first ever landing page project, and I'm really proud of how it turned out! After developing the Pathly app, I realized I needed a professional website to showcase it to potential users. I decided to build a modern, responsive landing page that would highlight all the app's features and benefits.

I built the site using React and Vite, which gave me a fast development experience and excellent performance. The landing page includes multiple sections: a hero area with a clear value proposition, feature highlights with animations, benefits of using the app, and call-to-action buttons to download Pathly.

One of the challenges I faced was making sure the site looked great on all device sizes. I implemented a fully responsive design that adapts to everything from small mobile screens to large desktop displays. I also added smooth animations using the AOS (Animate On Scroll) library to make the page feel more dynamic and engaging.

Beyond the main landing page, I created several additional pages including a detailed Privacy Policy, Terms of Service, a Support page with app information, and a Contact page with a form for users to reach out. There's even a dedicated page for downloading various Pathly logo variants.

This project taught me a lot about web design principles, user experience, and how to effectively market an app. I'm especially happy with how the visual style matches the Pathly app itself, creating a consistent brand experience. The clean aesthetics and intuitive navigation make it easy for visitors to understand what Pathly offers and why they should download it.

Features:
// Responsive design for all device sizes
// Animated sections with AOS (Animate On Scroll)
// Multiple pages including Home, Privacy, Terms, Support
// Contact form with validation
// Modern UI with clean aesthetics![Uploading thumbnail.svg…]()
<?xml version="1.0" encoding="UTF-8"?>
<svg width="800" height="450" viewBox="0 0 800 450" fill="none" xmlns="http://www.w3.org/2000/svg">
  <!-- Dark Background -->
  <rect width="800" height="450" fill="#1A1A1A"/>
  
  <!-- Pathly Logo and Header -->
  <g transform="translate(30, 40)">
    <text x="0" y="0" font-family="monospace" font-size="24" fill="#5FBDBD" font-weight="bold">{ Pathly</text>
  </g>
  
  <!-- Navigation Menu - Adjusted to prevent overlap -->
  <g transform="translate(400, 40)">
    <text x="0" y="0" font-family="sans-serif" font-size="14" fill="#FFFFFF">Features</text>
    <text x="80" y="0" font-family="sans-serif" font-size="14" fill="#FFFFFF">Benefits</text>
    <text x="160" y="0" font-family="sans-serif" font-size="14" fill="#FFFFFF">FAQ</text>
    <text x="210" y="0" font-family="sans-serif" font-size="14" fill="#FFFFFF">Support</text>
    <text x="280" y="0" font-family="sans-serif" font-size="14" fill="#FFFFFF">Contact Us</text>
  </g>
  
  <!-- Hero Text -->
  <g transform="translate(40, 200)">
    <text x="0" y="0" font-family="sans-serif" font-size="48" fill="#FFFFFF" font-weight="bold">Forge your path to</text>
    <text x="0" y="60" font-family="sans-serif" font-size="48" fill="#FFFFFF" font-weight="bold">better habits</text>
    
    <text x="0" y="100" font-family="sans-serif" font-size="16" fill="#CCCCCC" width="400">
      Track your habits, get AI coaching, and build a better you
    </text>
    <text x="0" y="125" font-family="sans-serif" font-size="16" fill="#CCCCCC" width="400">
      with Pathly's intuitive self-improvement app
    </text>
  </g>
  
  <!-- App Screenshot -->
  <g transform="translate(550, 180)">
    <rect x="0" y="0" width="200" height="400" rx="20" fill="#222222"/>
    
    <!-- App Header -->
    <text x="100" y="30" font-family="sans-serif" font-size="16" fill="#FFFFFF" text-anchor="middle">Pathly</text>
    
    <!-- Welcome Message -->
    <text x="20" y="60" font-family="sans-serif" font-size="14" fill="#FFFFFF">Welcome back, Alex!</text>
    <text x="180" y="60" font-family="sans-serif" font-size="18" fill="#5FBDBD" text-anchor="end">12</text>
    <text x="20" y="80" font-family="sans-serif" font-size="10" fill="#999999">Day Streak</text>
    
    <!-- Task Items -->
    <rect x="20" y="100" width="160" height="50" rx="10" fill="#333333"/>
    <circle cx="35" cy="125" r="10" fill="#5FBDBD"/>
    <text x="55" y="120" font-family="sans-serif" font-size="12" fill="#FFFFFF">Morning</text>
    <text x="55" y="135" font-family="sans-serif" font-size="12" fill="#FFFFFF">Meditation</text>
    <text x="160" y="125" font-family="sans-serif" font-size="12" fill="#CCCCCC" text-anchor="end">8:00 AM</text>
    
    <rect x="20" y="160" width="160" height="50" rx="10" fill="#333333"/>
    <circle cx="35" cy="185" r="10" fill="#444444" stroke="#666666"/>
    <text x="55" y="180" font-family="sans-serif" font-size="12" fill="#FFFFFF">Workout</text>
    <text x="160" y="185" font-family="sans-serif" font-size="12" fill="#CCCCCC" text-anchor="end">6:30 PM</text>
    
    <rect x="20" y="220" width="160" height="50" rx="10" fill="#333333"/>
    <circle cx="35" cy="245" r="10" fill="#444444" stroke="#666666"/>
    <text x="55" y="240" font-family="sans-serif" font-size="12" fill="#FFFFFF">Read 30</text>
    <text x="55" y="255" font-family="sans-serif" font-size="12" fill="#FFFFFF">minutes</text>
    <text x="160" y="245" font-family="sans-serif" font-size="12" fill="#CCCCCC" text-anchor="end">9:00 PM</text>
    
    <!-- Weekly Progress -->
    <text x="20" y="300" font-family="sans-serif" font-size="14" fill="#FFFFFF">Weekly Progress</text>
    
    <!-- Bottom Navigation -->
    <rect x="0" y="350" width="200" height="50" fill="#222222"/>
    <circle cx="30" cy="375" r="3" fill="#5FBDBD"/>
    <circle cx="70" cy="375" r="3" fill="#666666"/>
    <circle cx="110" cy="375" r="15" fill="#5FBDBD" opacity="0.8"/>
    <circle cx="150" cy="375" r="3" fill="#666666"/>
    <circle cx="190" cy="375" r="3" fill="#666666"/>
  </g>
  
  <!-- CTA Buttons -->
  <g transform="translate(40, 350)">
    <rect x="0" y="0" width="120" height="40" rx="20" fill="#5FBDBD"/>
    <text x="60" y="25" font-family="sans-serif" font-size="14" fill="#FFFFFF" text-anchor="middle">Get the App</text>
    
    <rect x="140" y="0" width="120" height="40" rx="20" fill="none" stroke="#5FBDBD" stroke-width="1"/>
    <text x="200" y="25" font-family="sans-serif" font-size="14" fill="#FFFFFF" text-anchor="middle">Learn More</text>
    
    <rect x="280" y="0" width="120" height="40" rx="20" fill="#5FBDBD" opacity="0.9"/>
    <text x="340" y="25" font-family="sans-serif" font-size="14" fill="#FFFFFF" text-anchor="middle">View Page</text>
  </g>
</svg> 
