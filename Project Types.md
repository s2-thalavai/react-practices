
## 1. SaaS (subscription-based product)

**Examples:** CRM, project management, analytics tools

### What matters

-   Auth, roles, billing
    
-   Long-lived UI
    
-   Fast iteration & SEO (for marketing pages)
    

### Recommended setup

-   **React**: 18
    
-   **Framework**: Next.js (App Router)
    
-   **Rendering**: Server Components + Client Components
    
-   **State**: React Query + lightweight global store
    
-   **Why**: Scalability, SEO, clean separation of server/client
    
> **Best overall React use case**

----------

## 2. Dashboard (internal tools, admin panels)

**Examples:** Admin panel, analytics dashboard, internal ops tools

### What matters

-   Heavy data tables & charts
    
-   Little or no SEO
    
-   Fast client-side interactions
    

### Recommended setup

-   **React**: 18
    
-   **Framework**: Vite + React
    
-   **Rendering**: Client-side rendering (CSR)
    
-   **State**: React Query + Zustand
    
-   **Why**: Simple, fast, fewer abstractions
    

> **Skip SSR unless needed**

----------

## 3. E-commerce (storefronts)

**Examples:** D2C stores, marketplaces

### What matters

-   SEO & performance
    
-   Fast page loads
    
-   Caching & scalability
    
-   Checkout stability
    

### Recommended setup

-   **React**: 18
    
-   **Framework**: Next.js
    
-   **Rendering**:
    
    -   Server-side rendering (SSR)
        
    -   Static generation (SSG)
        
-   **State**: Minimal global state
    
-   **Why**: SEO, performance, conversion rates
    

> **Avoid heavy client-only apps**

----------

## 4. Mobile (apps, not websites)

**Examples:** Android & iOS apps

### What matters

-   Native performance
    
-   Offline support
    
-   Device APIs
    

### Recommended setup

-   **React Native** (still React 18 concepts)
    
-   **Framework**: Expo (recommended)
    
-   **State**: React Query / Zustand
    
-   **Why**: Same React mental model, native UI
    

> **Do NOT use React DOM for mobile apps**

----------

## Quick comparison table

| Project type | React version | Framework    | Rendering |
| ------------ | ------------- | ------------ | --------- |
| SaaS         | 18            | Next.js      | SSR + RSC |
| Dashboard    | 18            | Vite         | CSR       |
| E-commerce   | 18            | Next.js      | SSR + SSG |
| Mobile       | 18            | React Native | Native    |

----------

## Final recommendation

-   **SaaS** → React 18 + Next.js
    
-   **Dashboard** → React 18 + Vite
    
-   **E-commerce** → React 18 + Next.js (SSR-heavy)
    
-   **Mobile** → React Native (Expo)

----------

