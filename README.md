# desi-etsy-webApplication
Desi Crafts - Handmade Products Marketplace
Project Summary
Desi Crafts is a niche e-commerce platform similar to Etsy but specialized for handmade products from Indian artisans. The platform connects skilled artisans with customers looking for authentic handcrafted items across various categories.

Key Features
Multi-Role User System

Customers: Browse, purchase products, leave reviews
Artisans: Manage profile, add/edit products, track orders
Administrators: Approve artisans, products, manage platform
Product Management

Detailed product listings with images, descriptions, pricing
Categories and regions filtering
Stock management and sale pricing options
Product approval workflow for quality control
Artisan Profiles

Custom storefront for each artisan
Bio and story section to highlight craftsmanship
Featured artisan spotlight
Product showcase by artisan
Shopping Experience

Advanced search and filtering
Shopping cart functionality
Checkout process
Integrated payment preparation (Razorpay)
Order Management

Order tracking for customers
Order fulfillment for artisans
Status updates and history
Technical Implementation
Frontend: React with Vite, using a component library based on shadcn/ui components
Backend: Express.js server with RESTful API endpoints
Database: Schema designed using Drizzle ORM (currently using in-memory storage, can be connected to PostgreSQL)
Authentication: JWT-based authentication system with secure password handling
State Management: React Context for auth and cart state
Routing: Wouter for client-side routing
API Integration: React Query for data fetching and mutations
Styling: Tailwind CSS with custom theming
Application Structure
Client: React frontend with modular components

Pages: Home, Products, Product Details, Cart, Checkout, Artisan Profiles, Dashboards
Components: Reusable UI elements, layout components, feature-specific components
Hooks: Custom hooks for auth, cart, and other functionality
Server: Express backend with RESTful API

Routes: Authentication, Products, Categories, Orders, Artisan Profiles, Admin
Storage: In-memory data storage with CRUD operations
Middleware: Authentication, authorization, validation
Shared: Common code between client and server

Schema: Database models and validation using Drizzle and Zod
Key Workflows
Artisan Journey:

Register account → Complete profile → Add products → Receive orders → Fulfill orders
Customer Journey:

Browse products → View details → Add to cart → Checkout → Track order
Admin Journey:

Approve artisans → Review products → Manage orders → Monitor platform
This marketplace is built with scalability in mind and follows modern web development practices, making it suitable for further extensions such as advanced analytics, loyalty programs, or additional payment gateways.
