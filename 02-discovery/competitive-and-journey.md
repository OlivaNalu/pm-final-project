# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Two key personas are identified. 
1. Frontline Driver: A delivery driver responsible for completing daily delivery routes, recording delivery outcomes, and capturing proof of delivery.

2. Fleet Dispatcher: A fleet dispatcher responsible for coordinating drivers, managing route assignments, and monitoring delivery progress throughout the day.
- **Goal, what is this user ultimately trying to achieve?:** The two personas have different goals.

1. Frontline Driver: Complete deliveries as quickly and efficiently as possible, with minimal administrative effort and without interruptions to their route.

2. Fleet Dispatcher: Keep drivers on the correct routes and maintain accurate, real-time visibility of delivery operations.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** Across the two personas we have the following friction:

1. Frontline Driver: Marking a delivery requires navigating three screens and multiple taps, even when working in difficult conditions such as rain with a package in one hand. Combined with unreliable offline access and app crashes that can erase remaining stops, drivers increasingly rely on WhatsApp, screenshots, and paper manifests instead.

2. Fleet Dispatcher: Route reassignment changes take 8–15 minutes to reach drivers, while delivery status updates can lag by 20–60 minutes. Dispatchers therefore cannot trust the dashboard to reflect what is happening in the field and resort to WhatsApp to coordinate operations.
- **External tools, the outside platforms or tools the user is forced to use:** WhatsApp groups, direct messaging, and manual coordination.
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Frontline Driver steps taken:
1. Bypass complex delivery completion: Instead of navigating three screens to mark a delivery as completed, drivers message or call their dispatcher to communicate the delivery outcome.
2. Create an offline backup: Before starting a route, drivers take screenshots of their stop lists so they can continue working when connectivity is lost.
3. Maintain a paper backup: Drivers keep printed manifests available in case the application crashes or their remaining stops become inaccessible.
4. Manually compensate for missing information: When the app crashes mid-route, drivers contact the office and ask dispatchers to read out their remaining stops.

Fleet Dispatcher steps taken:
1. Communicate route changes outside RouteLogic: When reassigning a route, dispatchers use WhatsApp to notify drivers because application updates can take 8–15 minutes to propagate.
2. Manually verify delivery progress: Rather than trusting the dashboard, dispatchers contact drivers directly to confirm whether deliveries have been completed.
3. Use external communication to resolve discrepancies: When dashboard statuses lag behind actual delivery activity, dispatchers rely on driver messages to establish what is happening in the field.
4. Maintain parallel operational communication: WhatsApp becomes the practical coordination channel because it provides a more immediate way to communicate than RouteLogic.
- **Core frustration, the exact moment the process feels most “broken”:** Frontline Driver breaking point: When a driver needs to mark a delivery as completed but must navigate three screens and multiple taps, potentially in the rain with a package in one hand. The experience becomes even more frustrating when connectivity fails or the app crashes and the remaining route disappears. At that point, the driver abandons RouteLogic and resorts to WhatsApp, screenshots, or paper manifests just to keep working.

Fleet Dispatcher breaking point: When a dispatcher reassigns a route but the driver continues following the old route because the update takes 8–15 minutes to reach their app. The dispatcher cannot trust that instructions have reached the driver or that the dashboard reflects actual delivery progress. They resort to WhatsApp to communicate changes and manually verify what is happening in the field.
- **The evidence, a specific quote or behavior from the research that proves this:** Frontline Driver
Evidence: UXR-01, UXR-03, UXR-06, UXR-12
Specific quote – UXR-01 (Diego, delivery driver):
"To mark a stop delivered I tap through three screens. In the rain, at a doorstep, with a package in one hand. I've started just texting my dispatcher instead."
Supporting behaviours:
- Five of seven drivers keep a paper manifest as a backup in case the app fails (UXR-12).
- Drivers take screenshots of their routes because stop lists are unavailable without connectivity (UXR-06).
- One driver lost 20 minutes after the app crashed mid-route and had to call the office to recover the remaining stops (UXR-03).

Fleet Dispatcher
Evidence: UXR-02, UXR-09
Specific quote – UXR-02 (Fleet dispatcher, mid-size 3PL):
"I reassign a route and the driver doesn't see it for ten, fifteen minutes. By then they've driven the wrong way. We keep a WhatsApp group as the real system."
Supporting behaviours:
- Driver status updates lag behind actual delivery progress, leaving completed stops displayed as in progress (UXR-09).
- Dispatchers rely on WhatsApp to communicate route changes because they cannot depend on RouteLogic to deliver updates quickly enough (UXR-02).
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** file:///C:/Users/zakemoli/Downloads/routelogic_future_state_journey.html
