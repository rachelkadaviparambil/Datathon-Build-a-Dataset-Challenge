Bethancourt Ballroom Outlet Availability | TAMU Datathon

This is a website that tracks outlet availability across tables in the Memorial Student Center (MSC) Bethancourt Ballroom at the 2026 TAMU Datahon.

Key Features

Ballroom Floor Map Overview: This is a map layout showing the entire room grid. Clicking row range labels or individual table pairs  scrolls you directly down to their detailed controls.

Detailed Table Outlet Controls: Grid section organized into the Left Side and Right Side of the ballroom, broken down by row number groupings.

Real-Time WebRTC Sync: This was built with PeerJS so multiple users can see live updates and active user counts simultaneously without a traditional backend database.

Scroll back to Top: This is a quick-scroll button next to the active users icon in the sticky header that automatically fades in whenever you scroll down to the Detailed Controls section.

Admin Modal & Security: This is a security feature that requires Admin login access allowing administrators to set specific outlets as "Unpluggable" (They are the Power Supply to the other outlets) to prevent attendees from altering the power infrastructure.

Ballroom Section Structure

The application maps out the ballroom into Left Side and Right Side sections:

Left Side of Ballroom:

Row 109–92

Row 91–70

Row 48–67

Row 46–25

Right Side of Ballroom:

Row 127–110

Row 149–128

Row 171–150

Row 24–1

Admin Credentials

Name: Mr. Rev

Password: Datathon

ID Number: 2026

Outlet Statuses

Available (Green): This means an open plug is available for regular users to use. Click on it to set it as unavailable.

Unavailable (Red): This means the plug currently taken. Click on it to set it as available.

Unpluggable (Black / Red Outline ⚡): This means this is a power supply outlet. This can only be edited by an authorized user/Admin.

Project Setup & Deployment

No build tools or installation steps are required.

Clone or download the repository.

Open index.html directly in any web browser, or push the repository to GitHub Pages.
