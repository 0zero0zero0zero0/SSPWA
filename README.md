# SSPWA
> Mission: "Create a progressive web app that feels like interacting with a movie."
## Single Screen Progressive Web App
## Table of Contents

I. [Core Philosophy](#core-philosophy)

A. [Single Screen Experience](#single-screen-experience)

B. [Quantum Development Principles](#quantum-development-principles)

II. [Brand Identity](#brand-identity)

A. [Visual Language](#visual-language)

B. [Key Messaging](#key-messaging)

III. [Technical Foundation](#technical-foundation)

A. [Technology Stack](#technology-stack)

B. [Development Approach](#development-approach)

IV. [Design System](#design-systems)

A. [Layout Principles](#layout-principles)

B. [Component Architecture](#component-architecture)

V. [Development Standards](#development-standards)

A. [Core Guidelines](#core-guidelines)

B. [Performance Focus](#performance-focus)

VI. [Community Strategy](#community-strategy)

A. [Engagement Channels](#engagement-channels)

B. [Contribution Model](#contribution-model)

VII. [Innovation Roadmap](#innovation-roadmap)

A. [Near Term Goals](#near-term-goals)

B. [Long Term Visions](#long-term-visions)

VIII. [About](#about)

IX. [Code](#code)

X. [Formatting](#formatting)

XI. [Guidelines](#guidelines)

### Core Philosophy
#### Single Screen Experience
SSPWA transforms web applications into cinematic experiences:
- End Endless Scrolling
- Every Pixel is an Actor
- Consistent Experience With All Devices
#### Quantum Development Principles
- **00**: Semantic Structure
- **01**: Fluid Interactions
- **10**: Meaningful Engagement
- **11**: Holistic Integration
### Brand Identity
#### Visual Language
- **Primary**: `rgba(0,0,0,1)` — Depth of Possibility
- **Secondary**: `rgba(255,255,255,1)` — Clarity of Purpose
- **Interaction**: `rgba(0,0,0,.9)` — Subtle Movement
#### Key Messaging
- Consistent Experience On All Devices
- No Scrolling Pure Interaction
- Ultimate Movie Game App Experience
### Technical Foundation
#### Technology Stack
- **Framework**: Vue.js V3 + Vite
- **Environment**: UNIX
- **Package Management**: Yarn
- **E2E Testing**: Playwright
- **Local Testing**: Vitest
#### Development Approach
- Quantum Development Model
- Semantic HTML
- Fluid Transitions
- Meaningful User Engagement
### Design Systems
#### Layout Principles
- Pure Flexbox
- Perfect Element Balancing
- Single Screen
- Code Formatting Standards
- RGBA or HSLAT Color Only
#### Component Architecture
```html
<north>Navigation</north>
<west>Navigation</west>  
<main>Content Stage</main>
<east>Navigation</east>
<south>Navigation</south>
```
### Development Standards
#### Core Guidelines
- Open Source IDE Only
- No Partial Files
- No Code Comments
- No Code Imports
- No Spread Operators
- Clean, Semantic Formatting
- One Space = One Tab
#### Performance Focus
- Instant view transitions
- Perfect element centering 
- IndexDB efficiency
- NoSQL when necessary
### Community Strategy
#### Engagement Channels
- GitHub Discussions
- Vue.js Forum
- PWA Developer Group
- Open Sourced Platforms
#### Contribution Model
- UNLiCENSE Open Source
- Clear Contribution Guidelines
- Community Recognition Programs
### Innovation Roadmap
#### Near Term Goals
- Three.js Integration
- Matter.js Physics
- Advanced State Management
- Cross Device Sync
#### Long Term Visions
- Web5 Integration
- AI Enhanced Interactions
- Innovative Display Technologies
- Revolutionary User Experiences
### About
#### SSPWA (Single Screen Progressive Web App) is an UNLiCENSE LiCENSE open source project that started in early 2019. A good movie experience feels the same on an old, square TV as it does on a new, widescreen TV that has the same screen size. The modern screen may provide an enhanced experience, but with an old screen you do not loose the quality of the movie in terms of the storyline and performance of the actors. SSPWA will provide a similar experience where the actors in a movie can be compared to the elements on the screen of the app. The app will feel the same regardless of what device you use the app on.
#### To add to the movie experience SSPWA will allow you to interact with the elements on the screen. When you watch a movie you do not interact with the actors. That would make the experience dynamic and more like a video game. SSPWA aims to give you a foundation to build highly interactive app experiences that your users can load and use on any of their devices in a moments notice.
#### Unlike a traditional PWA (Progressive Web App) or web application in general, the elements on the screen will never exist outside of the screen view. End the endless scrolling of apps and websites today and build the ultimate movie/game/app experience of the future!
### Code
`favicon.svg`
```
<svg xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="quantumBg"><animate attributeName="gradientTransform" type="rotate" values="0 125 250;360 250 125" dur="86400s" repeatCount="indefinite"/><stop offset="0%"><animate attributeName="stop-color" values="hsla(215,50%,45%,1);hsla(215,100%,45%,1);hsla(215,50%,45%,1)" dur="86400s" repeatCount="indefinite"/></stop><stop offset="100%"><animate attributeName="stop-color" values="hsla(215,100%,45%,1);hsla(215,50%,45%,1);hsla(215,100%,45%,1)" dur="86400s" repeatCount="indefinite"/></stop></linearGradient><filter id="quantumGlow"><feGaussianBlur stdDeviation="5" result="coloredBlur"/><feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect width="100%" height="100%" fill="url(#quantumBg)"/></svg>
```
`index.html`
```
<!DOCTYPE html>
<html lang="en">
 <head>
  <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <meta name="description" content="Single Screen Progressive Web App">
  <link rel="icon" href="favicon.svg">
  <title>SSPWA</title>
  <style>
   html,body,#A{display:flex;flex-wrap:wrap;width:100%;height:100%;overflow:hidden;box-sizing:border-box;margin:0;padding:0;background:hsla(0,0%,0%,1);color:hsla(0,0%,100%,1);font-size:25px;line-height:25px;cursor:default;}
   north{display:flex;justify-content:center;align-items:center;width:100%;height:50px;}
   west{display:flex;justify-content:center;align-items:center;width:50px;height:calc(100% - 100px);}
   main{display:flex;width:calc(100% - 100px);height:calc(100% - 100px);overflow:hidden;box-sizing:border-box;margin:0;padding:0;border:2px solid hsla(0,0%,100%,.1);}
   east{display:flex;justify-content:center;align-items:center;width:50px;height:calc(100% - 100px);}
   south{display:flex;justify-content:center;align-items:center;width:100%;height:50px;}
   north:hover,west:hover,east:hover,south:hover{background:hsla(0,0%,100%,.1);}
   h1,h2,h3,p,ol,ul,li{display:flex;width:100%;overflow:hidden;box-sizing:border-box;margin:5px 0;padding:0;}
   h1{font-size:32px;line-height:35px;}
   h2{font-size:27px;line-height:30px;}
   h3{font-size:25px;line-height:28px;}
   ol,ul{flex-direction:column;}
   p,li{font-size:20px;line-height:22px;}
   button{display:flex;justify-content:center;align-items:center;height:45px;overflow:hidden;box-sizing:border-box;margin:0;padding:10px;background:none;border:2px solid hsla(0,0%,100%,1);border-radius:5px;color:hsla(0,0%,100%,1);font-size:25px;line-height:25px;}
   button:hover{background:hsla(0,0%,100%,.9);color:hsla(0,0%,0%,1);}
   button:disabled{background:none;border:none;color:hsla(0,0%,0%,1);}
   @media(max-width:750px){
    h1{font-size:25px;line-height:28px;}
    h2{font-size:23px;line-height:25px;}
    h3{font-size:20px;line-height:22px;}
    p,li{font-size:16px;line-height:17px;}
    button{height:35px;font-size:16px;line-height:17px;}
   }
   h1{display:flex;justify-content:center;align-items:center;width:100%;height:100%;overflow:hidden;box-sizing:border-box;margin:0;padding:10px;background:hsla(215,100%,45%,1);color:hsla(0,0%,100%,1);}
  </style>
 </head>
 <body>
  <div id="A">
   <north role="navigation">η</north>
   <west role="navigation">ψ</west>
   <main role="main"><h1>Single Screen Progressive Web App</h1></main>
   <east role="navigation">φ</east>
   <south role="navigation">∫</south>
  </div>
 </body>
</html>
```
### Formatting
- 1 space = 1 tab
- semantic
- balanced
- optimized
- efficient
### Guidelines
- NEVER MAKE A FILE WITH PARTIALS INCLUDING COMMENT PARTIALS, NOR USE SPREAD/IMPORT OPERATORS!
- STICK WITH THE FLEX TEMPLATE, NEVER FORCE/TRICK STYLES!
- NEVER ADD COMMENTS, BREAK THE FORMATTING, OR MODIFY/CHANGE THE CORE CODE!
- FIVE DIMENSIONAL CODE APPEALS TO ALL FIVE SENSES/DIMENSIONS!
- 5D = 3D + 2D && Web2 + Web3 = Web5 && 00 01 10 11 = Quantum
