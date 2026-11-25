# Feature Roadmap, Module 4 · RouteLogic Velocity

**Team:** 2 engineers + 1 designer + 1 CS lead

## Strategic anchors
- **Persona:** Two key personas that I am solving for: 1. Frontline Driver: A delivery driver responsible for completing daily delivery routes, recording delivery outcomes, and capturing proof of delivery.  2. Fleet Dispatcher: A fleet dispatcher responsible for coordinating drivers, managing route assignments, and monitoring delivery progress throughout the day.
- **Primary metric:** Average daily time lost to manual workarounds. Reduce the current 31-minute baseline by at least 30%, to approximately 22 minutes. Break down the measurement by persona during the pilot to establish where the improvements are coming from.
- **Moment of misery:** Across the two personas we have the following friction:  1. Frontline Driver: Marking a delivery requires navigating three screens and multiple taps, even when working in difficult conditions such as rain with a package in one hand. Combined with unreliable offline access and app crashes that can erase remaining stops, drivers increasingly rely on WhatsApp, screenshots, and paper manifests instead.  2. Fleet Dispatcher: Route reassignment changes take 8–15 minutes to reach drivers, while delivery status updates can lag by 20–60 minutes. Dispatchers therefore cannot trust the dashboard to reflect what is happening in the field and resort to WhatsApp to coordinate operations.
- **Guardrail:** Protect existing core product satisfaction. Driver Core Dispatch CSAT must remain at or above 4.3/5.0 and Coordinator Core Dispatch CSAT at or above 4.1/5.0. Also protect Manager Reporting CSAT at 4.5/5.0 where changes affect enterprise reporting or data flows.

## Scoring
| Feature | Value | Effort | Quadrant | Decision | Rationale |
|---|---|---|---|---|---|
| B1 One-Click Compliance Checklist | 4 | 3 | Major Project | Next | Tackles a significant 14.6-minute workflow bottleneck and reduces administrative effort, particularly for Dispatchers, but compliance is not the clearest expression of either persona’s primary moment of misery. |
| B2 Smart Daily Report Auto-Fill | 2 | 5 | Time Sinker | Cut | Automates a downstream reporting task rather than fixing frontline execution or coordination; AI and data-quality dependencies make it difficult to deliver safely in four weeks. |
| B3 Shift Handoff Wizard | 4 | 2 | Quick Win | Now | Could save around 6.8 minutes per day and simplify Dispatcher handoffs, but has limited direct impact on the Driver experience. |
| B4 Mobile-First Coordinator Dashboard | 3 | 5 | Time Sinker | Cut | Could improve Dispatcher access to core workflows, but is a broad redesign, risks becoming a large scope of work, and does not directly resolve Driver-side friction or unreliable updates. |
| B5 Step Progress Indicator | 2 | 1 | Fill-In | Later | Easy to implement, but showing workflow progress does little to remove the underlying steps, delays or manual workarounds. |
| B6 Driver Alert Notifications | 5 | 3 | Major Project | Next | Directly addresses the 8–15-minute route-change communication delay and connects Dispatcher decisions with Driver execution; integration and offline reliability need validation. This is key to address core requirement that we need to fix |
| B7 Contextual AI ETA Display | 2 | 3 | Time Sinker | Cut | Low adoption of predictive ETAs (11% among Drivers) suggests this is not a priority; it does not address the core route-change or delivery-update friction. |
| B8 Fleet Analytics Manager View | 1 | 5 | Time Sinker | Cut | Primarily serves management visibility, not the two frontline personas; risks diverting scarce capacity from the operational experience and could put reporting value at risk. |
| B9 Compliance Audit Trail Export | 2 | 2 | Fill-In | Later | Useful for audit and compliance needs, but it is a downstream administrative benefit rather than a meaningful reduction in daily Driver or Dispatcher workarounds. |
| B10 In-App Coordinator Training | 2 | 2 | Fill-In | Later | May help new Dispatchers learn the product, but training does not fix a workflow that is inherently slow, complex or unreliable. |

## Roadmap
### NOW, Pilot (4 weeks, 3 accounts)
- **B3 Shift Handoff Wizard**, Could save around 6.8 minutes per day and simplify Dispatcher handoffs, but has limited direct impact on the Driver experience.

### NEXT, GA Release (weeks 5-8)
- **B1 One-Click Compliance Checklist**, Tackles a significant 14.6-minute workflow bottleneck and reduces administrative effort, particularly for Dispatchers, but compliance is not the clearest expression of either persona’s primary moment of misery.
- **B6 Driver Alert Notifications**, Directly addresses the 8–15-minute route-change communication delay and connects Dispatcher decisions with Driver execution; integration and offline reliability need validation. This is key to address core requirement that we need to fix

### LATER, backlog
- **B5 Step Progress Indicator**, Easy to implement, but showing workflow progress does little to remove the underlying steps, delays or manual workarounds.
- **B9 Compliance Audit Trail Export**, Useful for audit and compliance needs, but it is a downstream administrative benefit rather than a meaningful reduction in daily Driver or Dispatcher workarounds.
- **B10 In-App Coordinator Training**, May help new Dispatchers learn the product, but training does not fix a workflow that is inherently slow, complex or unreliable.

### ✂ Cut List
- **B2 Smart Daily Report Auto-Fill**, Automates a downstream reporting task rather than fixing frontline execution or coordination; AI and data-quality dependencies make it difficult to deliver safely in four weeks.
- **B4 Mobile-First Coordinator Dashboard**, Could improve Dispatcher access to core workflows, but is a broad redesign, risks becoming a large scope of work, and does not directly resolve Driver-side friction or unreliable updates.
- **B7 Contextual AI ETA Display**, Low adoption of predictive ETAs (11% among Drivers) suggests this is not a priority; it does not address the core route-change or delivery-update friction.
- **B8 Fleet Analytics Manager View**, Primarily serves management visibility, not the two frontline personas; risks diverting scarce capacity from the operational experience and could put reporting value at risk.
