# AXO Implementation Standard Operating Procedures (SOPs)

---

## Phase 1: Foundation (Weeks 1-2)

| SOP # | Task | Owner | Procedure | Verification |
|---|---|---|---|---|
| **1.1** | **Conduct Content Audit** | Content Team Lead | 1. Crawl the entire website to get a list of all URLs.<br>2. For each URL, assess content against the CLEAR framework.<br>3. Score each page on a scale of 1-5 for each CLEAR principle.<br>4. Prioritize pages for optimization based on traffic and strategic importance. | Content audit spreadsheet is complete and reviewed by the AXO team. |
| **1.2** | **Establish AXO Team & Roles** | Project Sponsor | 1. Formally nominate members for the AXO team from Technical, Content, Marketing, and Governance.<br>2. Draft a team charter outlining the mission, goals, and responsibilities.<br>3. Hold a kickoff meeting to align on the 8-week roadmap. | Team charter is signed off by all members and leadership. |
| **1.3** | **Set Up Measurement Framework** | Marketing/Analytics Lead | 1. Configure analytics to track agent-specific user-agent strings.<br>2. Implement custom event tracking for schema-related interactions.<br>3. Create a baseline report for current agent traffic and citation rate (if possible).<br>4. Set up a dashboard to monitor primary and secondary AXO KPIs. | AXO dashboard is live and populated with baseline data. |
| **1.4** | **Configure Initial Crawling Controls** | Technical Lead | 1. Review the existing `robots.txt` file.<br>2. Add directives to disallow known malicious bots.<br>3. Create an initial `llms.txt` file pointing to the homepage and top 5-10 key pages. | `robots.txt` and `llms.txt` files are live on the production server. |

---

## Phase 2: Structure (Weeks 3-4)

| SOP # | Task | Owner | Procedure | Verification |
|---|---|---|---|---|
| **2.1** | **Implement CLEAR Framework on Priority Pages** | Content Team | 1. Based on the content audit, rewrite the top 20 priority pages.<br>2. Ensure each page has a clear heading hierarchy (H1, H2, H3).<br>3. Verify that each factual claim is supported by a citation.<br>4. Move key facts and summaries to the top of the page. | All 20 priority pages are updated and live. |
| **2.2** | **Add Basic Schema Markup** | Technical Team | 1. Implement `Organization` schema on the homepage.<br>2. Implement `Product` schema on all product pages.<br>3. Implement `Article` schema on all blog posts and articles.<br>4. Use Google's Rich Results Test to validate the markup. | Schema validation passes for all targeted pages. |
| **2.3** | **Optimize Page Loading Speeds** | Technical Team | 1. Run performance tests using Google PageSpeed Insights.<br>2. Optimize images by compressing them and using next-gen formats.<br>3. Minify CSS and JavaScript files.<br>4. Enable browser caching and server-side compression. | PageSpeed Insights score improves by at least 20 points for key pages. |

---

## Phase 3: Enhancement (Weeks 5-6)

| SOP # | Task | Owner | Procedure | Verification |
|---|---|---|---|---|
| **3.1** | **Add Comprehensive Trust Signals** | Content Team | 1. Create detailed author bio pages for all content creators.<br>2. Add author schema to all articles.<br>3. Create a dedicated page for editorial policies and fact-checking standards.<br>4. Update the "About Us" page with detailed company history and leadership bios. | New trust signal pages are live and linked from relevant content. |
| **3.2** | **Implement Advanced Schema** | Technical Team | 1. Implement `FAQPage` schema on all FAQ pages.<br>2. Implement `BreadcrumbList` schema across the site.<br>3. Implement `Review` schema for products with customer reviews.<br>4. Explore and implement other relevant industry-specific schema. | Advanced schema is validated and live on the site. |
| **3.3** | **Develop Content APIs** | Technical Team | 1. Define the scope and requirements for a content API.<br>2. Develop API endpoints for key content types (e.g., products, articles).<br>3. Implement API key authentication and rate limiting.<br>4. Create documentation for the API. | API is deployed and documentation is available. |

---

## Phase 4: Scale & Monitor (Weeks 7-8)

| SOP # | Task | Owner | Procedure | Verification |
|---|---|---|---|---|
| **4.1** | **Expand Optimization to All Content** | Content Team | 1. Continue rewriting all remaining content to align with the CLEAR framework.<br>2. Ensure all new content follows AXO best practices from creation.<br>3. Establish a regular content review and update cycle. | 80% of all site content is updated to meet AXO standards. |
| **4.2** | **Implement Advanced Monitoring** | Marketing/Analytics Lead | 1. Implement a signal-based agent detection system.<br>2. Refine the AXO dashboard with more granular data.<br>3. Set up automated alerts for significant changes in agent traffic or citation rates. | Advanced agent detection is live and the dashboard is updated. |
| **4.3** | **Train Content Teams** | Content Team Lead | 1. Hold a formal training session on AXO principles and the CLEAR framework.<br>2. Provide writers with a checklist for creating agent-ready content.<br>3. Incorporate AXO into the official content style guide. | Training is complete and the style guide is updated. |
| **4.4** | **Establish Maintenance Workflows** | AXO Team | 1. Schedule monthly reviews of AXO performance.<br>2. Establish a process for regularly updating `llms.txt` and schema markup.<br>3. Create a feedback loop for incorporating new learnings into the AXO strategy. | A formal AXO maintenance plan is documented and approved. |
