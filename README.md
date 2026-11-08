Bethancourt Ballroom Outlet Availability | TAMU Datathon

A real-time web application built for TAMU Datathon to track outlet availability across tables in the Memorial Student Center (MSC) Bethancourt Ballroom.

Key Features

Ballroom Floor Map Overview: Top-level visual layout showing the entire room grid. Clicking row range labels or individual table pairs smoothly scrolls directly down to their detailed controls.

Detailed Table Outlet Controls: Grid section organized into the Left Side and Right Side of the ballroom, broken down by row number groupings.

Real-Time WebRTC Sync: Built with PeerJS so multiple users can see live updates and active user counts simultaneously without a traditional backend database.

Scroll back to Top: A quick-scroll button next to the active users icon in the sticky header that automatically fades in whenever you scroll down to the Detailed Controls section.

Admin Modal & Security: Admin login access allowing administrators to set specific outlets as "Unpluggable" (Power Supply) to prevent attendees from altering essential power infrastructure.

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

Available (Green): Open plug available for hackers to use. Click to set as unavailable.

Unavailable (Red): Plug currently taken. Click to set as available.

Unpluggable (Black / Red Outline ⚡): Designated power supply outlet. Can only be edited by an authenticated Admin.

Project Setup & Deployment

No build tools or installation steps are required.

Clone or download the repository.

Open index.html directly in any web browser, or push the repository to GitHub Pages.
