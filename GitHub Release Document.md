# Electrician App — Unified SQL Express & SQL Server Edition
## Initial GitHub Release — Version 1.0.0

This release introduces the fully unified version of the Electrician App, combining all features and license tiers into a single Windows `.exe` application. The app supports both SQL Express and SQL Server, selected during installation, eliminating the need for separate builds or database versions.

All license tiers (Basic, Pro, Enterprise) are included in one unified application, with access determined by the user’s Gumroad license key.

---

## ADMIN ROLES

• GLOBAL ADMIN (Corporate Level)
  - Full system access.
  - Manages subscription plans and license upgrades.
  - Creates companies, divisions, and regions.
  - Manages all admins (global + local).
  - Controls payroll schedules and exports.
  - Oversees inventory, suppliers, and purchase orders.
  - Integrates the Payroll App with CRM modules.

• LOCAL ADMIN (Division / Region Level)
  - Limited access based on assigned role + permissions.
  - Enters employee job tickets, production data, and material usage.
  - Reviews work tickets before payroll is processed.
  - Can manage inventory and POs if permissions allow.
  - Cannot modify subscription plans or corporate settings.

---

## Included in This Release
- Basic Plan  
- Pro Plan  
- Enterprise Plan  
- Admin Add‑on  
- Employee Add‑on  
- Unified SQL Express + SQL Server architecture  
- One installer, one app, one onboarding flow  

---

## Plan Descriptions

### Basic Plan
Provides essential management features for individuals or small teams in the electrical industry.  
Includes core workflow tools, job entry, payroll calculation, and standard reporting.  
Ideal for users who need a reliable, cost‑effective foundation without advanced automation.

---

### Pro Plan
Expands on the Basic plan with enhanced productivity tools and deeper reporting.  
Designed for growing teams that manage multiple projects and need more flexibility.  
Includes prepopulated database fields for electrical materials, employees, and builders to speed up data entry.

---

### Enterprise Plan
Unlocks the full capabilities of the system, including everything in Pro plus advanced features and enterprise‑grade controls.  
Required for organizations with multiple administrators or complex operational needs.  
Serves as the base license for all administrative and employee‑level functionality.

Enterprise includes:
- Custom reporting templates  
- Priority support  
- Employee login functionality  
- Daily production input by field employees  
- Separate login pages for admins and employees  

---

## License Activation
A valid Stripe subscription is required to use this application.

• On first launch, the app checks your subscription status securely through Stripe.
• If your subscription is active, the app unlocks full access.
• If your subscription is canceled, expired, or unpaid, access is restricted.
• Internet is required only during subscription verification and plan changes.
• All billing and upgrades are handled through Stripe’s secure checkout.

---

## Database
The Electrician App supports two database modes, selected during installation:

### SQL Express (Local Database — Recommended for 1–5 users)
- Automatically installed and configured by the installer  
- Ideal for individuals, small teams, and single‑machine setups  
- Fully offline and self‑contained  

### SQL Server (Remote or On‑Prem Server)
- Connect to an existing SQL Server instance  
- Supports multi‑user environments and IT‑managed deployments  
- Ideal for medium‑to‑large teams or companies with dedicated servers  

Both modes use the same unified application and feature set.

---

## Stability
This version is the current stable build distributed through the updater and serves as the foundation for all future updates.