# Home Automation Dashboard

A web-based home automation interface designed to monitor and manage various smart devices across different rooms. This project utilizes a PHP backend paired with a mobile-friendly frontend.

## Key Features
*   **Room Controls:** Dedicated interfaces for the Bedroom, Drawing Room, Garage, and Kitchen[cite: 2].
*   **Device Management:** Visual status indicators and controls for lights, ceiling fans, pedestal fans, and a central hub[cite: 2].
*   **Security & Access:** Modules for front door and porch light monitoring[cite: 2].
*   **User Tracking:** Backend PHP services for managing user/employee access and generating reports (`getemployee.php`, `getreports.php`)[cite: 2].

## Tech Stack
*   **Frontend:** HTML, CSS[cite: 2].
*   **UI Frameworks:** Bootstrap and jQuery Mobile (v1.0rc1) for responsive, touch-friendly navigation[cite: 2].
*   **Backend:** PHP[cite: 2].
*   **Database:** SQL (setup schema included via `directory.sql`)[cite: 2].

## Repository Structure
*   `www/`: Contains all frontend assets, including HTML views (`bedroom.html`, `garage.html`), CSS stylesheets, fonts, and UI images[cite: 2].
*   `services/`: Houses the backend logic, database configuration (`config.php`), and endpoints for data retrieval[cite: 2].

## Setup Instructions
1. Clone the repository to your local machine.
2. Move the project files to a local PHP web server environment (e.g., XAMPP, WAMP, or LAMP stack).
3. Import the `services/directory.sql` file into your MySQL database[cite: 2].
4. Update the database credentials inside `services/config.php` to match your local environment[cite: 2].
5. Navigate to the `www/` directory in your web browser to access the dashboard[cite: 2].
