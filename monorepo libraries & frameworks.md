# monorepo libraries & frameworks

## 🏆 Best overall (most teams)

### 🥇 **Turborepo**

![https://turborepo.com/icon.png?icon.fb1a054d.png=&utm_source=chatgpt.com](https://turborepo.com/icon.png?icon.fb1a054d.png=&utm_source=chatgpt.com)

![https://www.maxpou.fr/_astro/turborepo-pipeline.Byba11M-_2oPoM.webp?utm_source=chatgpt.com](https://www.maxpou.fr/_astro/turborepo-pipeline.Byba11M-_2oPoM.webp?utm_source=chatgpt.com)

**Best for:** React, Next.js, Expo, full-stack SaaS

**Why it wins**

-   Extremely fast builds (smart caching)
    
-   Simple mental model
    
-   Excellent DX
    
-   First-class support for React, Next.js, Expo
    

**Used by:** Vercel, Linear, HashiCorp

✅ **Best choice for web + mobile monorepos**

----------

## 🥈 Best enterprise / large-scale

### 🥈 **Nx**

![https://miro.medium.com/v2/resize%3Afit%3A1048/0%2A8tu6dgB0zeyiz-vo.png?utm_source=chatgpt.com](https://miro.medium.com/v2/resize%3Afit%3A1048/0%2A8tu6dgB0zeyiz-vo.png?utm_source=chatgpt.com)

![https://dcv19h61vib2d.cloudfront.net/thumbs/egghead-use-the-nx-dependency-graph-to-visualize-your-monorepo-structure-sL5CBTjDv/egghead-use-the-nx-dependency-graph-to-visualize-your-monorepo-structure-sL5CBTjDv.jpg?utm_source=chatgpt.com](https://dcv19h61vib2d.cloudfront.net/thumbs/egghead-use-the-nx-dependency-graph-to-visualize-your-monorepo-structure-sL5CBTjDv/egghead-use-the-nx-dependency-graph-to-visualize-your-monorepo-structure-sL5CBTjDv.jpg?utm_source=chatgpt.com)

**Best for:** Large teams, enterprise apps

**Strengths**

-   Dependency graph visualization
    
-   Code generation
    
-   Strong Angular + React support
    
-   Fine-grained control
    

**Tradeoff**

-   More configuration
    
-   Steeper learning curve
    

----------

## 🥉 Best minimal & lightweight

### 🥉 **pnpm** (workspaces only)

![https://miro.medium.com/1%2A2uJWLlyD7tFR-e_jT-mpjg.png?utm_source=chatgpt.com](https://miro.medium.com/1%2A2uJWLlyD7tFR-e_jT-mpjg.png?utm_source=chatgpt.com)

![https://blog.logrocket.com/wp-content/uploads/2022/07/simple-structure-workspace.png?utm_source=chatgpt.com](https://blog.logrocket.com/wp-content/uploads/2022/07/simple-structure-workspace.png?utm_source=chatgpt.com)

**Best for:** Small teams, simple monorepos

**Pros**

-   Very fast installs
    
-   Minimal tooling
    
-   Easy to understand
    

**Cons**

-   No caching or task orchestration
    
-   You wire everything manually
    

----------

## 🧩 Frameworks that work great _inside_ monorepos

### Web

-   **Next.js** → SaaS, E-commerce, SEO
    
-   **Vite** → Dashboards, internal tools
    

### Mobile

-   **Expo** → Best React Native DX
    

### Backend (optional)

-   **NestJS**
    
-   **tRPC**
    

----------

## 🎨 UI & shared code libraries (monorepo-friendly)

### Cross-platform UI

-   **Tamagui**
    
-   **NativeWind**
    

### State & data

-   **TanStack Query**
    
-   **Zustand**
    

----------

## 🔐 Tooling essentials

-   **Linting**: **ESLint**
    
-   **Formatting**: **Prettier**
    
-   **Testing**: **Vitest**
    
-   **CI/CD**: **GitHub Actions**
    

----------

## 🧠 Decision table (quick pick)

| Your need             | Pick this           |
| --------------------- | ------------------- |
| Web + mobile SaaS     | **Turborepo**       |
| Enterprise / 50+ devs | **Nx**              |
| Simple repo           | **pnpm workspaces** |
| React Native          | **Expo**            |
| SEO / E-commerce      | **Next.js**         |
| Dashboards            | **Vite**            |

