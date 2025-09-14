# LaMart1.0

MarketSwift – Stock Management & Self-Service POS
MarketSwift is a case study and real-world development project focused on building a modern stock management and self-service point-of-sale (POS) system for a multi-branch Asian supermarket chain in the UK. The project addresses inefficiencies in manual invoice entry, limited cross-branch visibility, and the high costs of existing commercial POS solutions.

Project Background
The supermarket chain currently relies on a manual, line-by-line stock entry process managed solely by the owner. This method consumes several hours per delivery and creates bottlenecks, data errors, and scalability challenges. Commercial POS systems cost upwards of £13,000 per year per branch, which is unsustainable for smaller businesses.

MarketSwift aims to:
Short-term: Deliver a web-based stock management tool with a spreadsheet-style interface, CSV/XLSX import/export, validation, and dashboards for reporting.

Long-term: Develop a self-service kiosk POS system integrated with the central stock database, using low-cost hardware (~£600 setup) to provide an affordable alternative for small supermarkets.

Research & Requirements
The development process begins with requirements gathering through shadowing the supermarket owner during live stock updates. This includes documenting workflows, timing invoice entry, identifying pain points, and clarifying reporting needs. The insights form the foundation for database schema design, UI layout, and system architecture.

Technical Approach
Backend: FastAPI (Python) or Java Spring Boot
Frontend: React or Vanilla JavaScript with AG Grid (Excel-like UI)
Database: PostgreSQL or MySQL
Deployment: Low-cost VPS hosting (Hetzner/OVH)

Expected Impact
Reduce invoice entry time from ~60 minutes to <10 minutes.
Decrease stock entry errors to under 1%.
Enable real-time, cross-branch stock visibility.
Provide the first low-cost self-service POS solution for small supermarkets.

Vision
Beyond solving internal inefficiencies, MarketSwift has the potential to become a resellable, modular retail solution for independent supermarkets, bridging the gap between expensive enterprise systems and outdated manual processes. This repository tracks the full journey — from shadowing and requirements gathering to prototypes, implementation, and evaluation.
