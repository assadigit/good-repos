---
source: https://github.com/amilich/isometric-city
aliases:
  - isometric-city
  - amilich/isometric-city
tags: [typescript, nextjs, typescript, canvas, simulation, game, css, javascript, shell, url]
category: Web-Frameworks
stars: 2183
org: amilich
primary_language: TypeScript
languages: [TypeScript, CSS, JavaScript, Shell, url]
credibility_score: 47.0/100
date_processed: 2026-07-10



---

# isometric-city

> **TL;DR:** Self-hosted isometric city and theme park simulation game built with NextJS, TypeScript, and HTML5 Canvas.

**`amilich/isometric-city`** · ⭐ 2,183 · 🔧 TypeScript

## What is it?
IsoCity is an open-source city-building simulation that runs entirely in the browser using NextJS, TypeScript, and HTML5 Canvas. The project includes two main applications: IsoCity, which simulates autonomous traffic (cars, trains, planes, buses, seaplanes) and pedestrian movement across a dynamically growing urban environment with economy and resource management; and IsoCoaster, a theme park variant featuring roller coasters, rides, and guest simulation. Both apps are built from scratch with a tile-based placement system for roads, buildings, parks, utilities, and more.

The core of the project is an isometric rendering engine implemented on top of HTML5 Canvas, providing depth sorting, layer management, and support for both image and canvas sprites. This allows for complex visual effects while maintaining good performance. The simulation logic runs client-side with real-time updates, leveraging NextJS's React ecosystem for state management and TypeScript for type safety.

## How does it work?
IsoCity uses a NextJS application as its frontend framework, combining React components with custom Canvas rendering layers for the isometric grid. The HTML5 Canvas (`CanvasIsometricGrid`) handles all drawing operations, including depth sorting to correctly render buildings, roads, and vehicles. Traffic agents are autonomous JavaScript objects that follow predefined routes, obey traffic lights, and interact with the map. Pedestrian agents use pathfinding algorithms to navigate the city while avoiding collisions. The economy system tracks resources, manages zoning (residential, commercial, industrial), and drives city growth through a state machine updated each tick.

## Why is it important? (Core Value)
For a developer curating self-hostable alternatives to SaaS products, IsoCity offers a polished, open-source city simulation that can be deployed on any server or local machine without relying on paid services. It demonstrates advanced Canvas-based rendering and real-time simulation logic, making it an excellent learning resource for performance optimization, pathfinding, and state management in web applications. While not an AI agent, it aligns with your interest in open-source projects from major tech companies (NextJS is maintained by Vercel) and could be added to your Obsidian vault under 'Tools' or 'Infrastructure' notes as a self-hostable web app. The project also showcases modern development practices—TypeScript for type safety, NextJS for server-side rendering, and Cursor AI editor—making it relevant for developer productivity.

## Key Features & Technologies
- Isometric Rendering Engine (HTML5 Canvas)
- Traffic System (cars, trains, planes, buses, seaplanes)
- Pedestrian System (pathfinding and crowd simulation)
- Economy & Resources (zoning, city growth logic)
- Interactive Grid (tile-based placement)
- Built with NextJS and TypeScript
- Made with Cursor AI editor

## Difference from Others
Unlike commercial city builders such as Cities: Skylines or SimCity, IsoCity is completely open-source and free to host anywhere. Compared to older 2D city simulators, it features a polished isometric perspective with depth sorting and layer management that many open-source alternatives lack. Other web-based city projects often use simple grid rendering without the sophisticated Canvas engine here, and they typically lack real-time autonomous vehicle simulation. IsoCity also includes a theme park variant (IsoCoaster) which is rare among open-source city builders, setting it apart from most similar projects.

## 🏢 Organization & Credibility
- **Developer:** amilich
- **Reputation:** Unknown
- **Stars:** 2,183
- **Forks:** 239
- **Recent Activity:** 17 commits in 3 months
- **Credibility Score:** 47.0/100 (Low)
- **Languages:** TypeScript, CSS, JavaScript, Shell, url
- **Last Release:** No releases
- **Quality:** ✅ good

## 💡 My Ideas & Notes
[Add your personal thoughts here]

## 📱 Social Signal (Manual)
- **Source:** [Dropdown: Reddit/X/Instagram/GitHub Search/Other]
- **Link:** [URL]
- **Notes:** [Context]

## 📔 Journal
[Date] - [Your experiences]

---
*Source: [GitHub](https://github.com/amilich/isometric-city)*
