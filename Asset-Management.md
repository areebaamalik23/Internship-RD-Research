1. Introduction
An Asset Management System is a software application designed to help organizations manage, monitor, and track their physical and digital assets throughout their lifecycle.

Organizations use different types of assets, such as computers, laptops, printers, furniture, machinery, vehicles, and software licenses. Managing these assets manually can be difficult, especially when an organization has a large number of employees and resources.

An Asset Management System provides a centralized platform where administrators can maintain asset records, assign assets to employees, monitor their condition, track maintenance activities, and manage asset availability.

Main Objectives:

- Maintain accurate records of company assets.
- Track the location and status of assets.
- Manage asset assignments and returns.
- Monitor asset maintenance and repairs.
- Reduce asset loss and unnecessary expenses.
- Improve resource utilization and accountability.

2. Main Users
2.1 Admin
The Admin manages the overall system and has access to administrative functions.
Responsibilities:

- Manage system users and their roles.
- Add, update, and delete asset records.
- Manage asset categories.
- Assign assets to employees.
- Monitor asset information.
- Generate asset reports.
2.2 Employee
Employees use the system to view and manage information about assets assigned to them.

Responsibilities:

- View assigned assets.
- Check asset details and status.
- Submit asset requests.
- Report damaged or faulty assets.
- Request maintenance or replacement.
- Confirm asset receipt and return.
2.3 Asset Manager
The Asset Manager is responsible for monitoring and maintaining organizational assets.

Responsibilities:

- Monitor asset availability.
- Manage asset assignments and returns.
- Track asset locations.
- Schedule maintenance and repairs.
- Update asset conditions.
- Monitor asset usage and generate reports.

3. Key Features of Asset Management System
3.1 Asset Registration

Asset Registration allows administrators to add new assets to the system and maintain their records.

Information Includes:

- Asset name
- Asset ID or unique identification number
- Serial number
- Asset category
- Purchase date
- Purchase cost
- Asset location
- Asset condition
- Current status

Purpose:

- Maintains centralized asset records.
- Makes assets easier to identify.
- Prevents duplicate asset entries.
- Helps administrators track company resources.

Example: When a company purchases ten new laptops, the administrator registers each laptop with its unique asset ID and serial number.

3.2 Asset Categorization

This feature allows administrators to organize assets into different categories.

Examples:

- Computers and Laptops
- Printers and Scanners
- Office Furniture
- Networking Equipment
- Vehicles
- Software Licenses
- Machinery

Purpose:

- Organizes assets systematically.
- Makes searching and filtering easier.
- Helps administrators manage different asset types.
- Improves asset reporting.

3.3 Asset Assignment
Asset Assignment allows administrators or asset managers to assign available assets to employees or departments.

Information Includes:

- Employee name or ID
- Asset ID
- Assignment date
- Department
- Assigned location
- Expected return date, if applicable

Purpose:

- Tracks which employee is using each asset.
- Maintains assignment records.
- Improves accountability.
- Prevents unauthorized asset distribution.

Example: An administrator assigns a company laptop to a newly hired employee and records the assignment date.

3.4 Asset Tracking

Asset Tracking allows organizations to monitor the location and current status of their assets.

Tracking Information:

- Current location
- Assigned employee
- Asset status
- Asset condition
- Movement history

Purpose:

- Helps locate company assets.
- Reduces asset loss.
- Tracks asset movement between departments.
- Provides updated asset information.

3.5 Asset Return Management

This feature manages the process of returning assets when employees leave the organization, change departments, or no longer need assigned equipment.

Main Functions:

- Record asset return dates.
- Check the returned asset's condition.
- Update asset availability.
- Maintain return history.
- Record missing or damaged items.

Purpose:

- Ensures assets are returned properly.
- Maintains accurate asset records.
- Makes returned assets available for reassignment.

3.6 Maintenance and Repair Management

This feature helps organizations manage asset maintenance and repair activities.

Main Functions:

- Schedule regular maintenance.
- Record repair requests.
- Track maintenance history.
- Store repair costs.
- Update asset conditions.
- Monitor maintenance status.

Purpose:

- Keeps assets in good working condition.
- Reduces unexpected equipment failures.
- Extends asset lifespan.
- Helps control maintenance expenses.

3.7 Asset Status Management

This feature allows administrators to monitor the current status of each asset.

Common Asset Statuses:

- Available
- Assigned
- Under Maintenance
- Damaged
- Lost
- Retired

Purpose:

- Provides clear information about asset availability.
- Helps administrators identify usable and unusable assets.
- Prevents assigning unavailable assets.

3.8 Asset Request Management

This feature allows employees or departments to request new assets or additional equipment.

Request Information:

- Requested asset type
- Request date
- Reason for request
- Employee or department details
- Request status

Request Statuses:

- Pending
- Approved
- Rejected

Purpose:

- Organizes employee asset requests.
- Provides an approval process.
- Helps administrators manage resource distribution.
- Maintains request history.

3.9 Notifications and Alerts

This feature sends notifications about important asset-related activities.

Examples:

- A new asset request has been submitted.
- An asset has been assigned to an employee.
- An asset return date is approaching.
- Maintenance is required.
- An asset request has been approved or rejected.

Purpose:

- Keeps employees and administrators informed.
- Improves communication.
- Helps prevent missed return dates.
- Supports timely maintenance.

3.10 Asset History and Audit Logs

This feature maintains a historical record of asset-related activities and changes.

Information Includes:

- Asset registration details.
- Assignment and return records.
- Location changes.
- Maintenance history.
- Status updates.
- User activity records.

Purpose:

- Maintains transparency.
- Tracks asset ownership and usage history.
- Helps identify unauthorized changes.
- Supports accountability and auditing.

3.11 Depreciation Management

Depreciation Management helps organizations track the reduction in the financial value of assets over time.

Main Functions:

- Record the original purchase cost.
- Set the asset's useful life.
- Calculate depreciation.
- Estimate the current book value.
- Maintain depreciation records.

Purpose:

- Helps calculate the current financial value of assets.
- Supports financial planning.
- Helps organizations understand asset value over time.

3.12 Reports and Analytics

This feature allows administrators and management to generate reports about organizational assets.

Examples:

- Total registered assets.
- Available and assigned assets.
- Assets under maintenance.
- Damaged or retired assets.
- Department-wise asset reports.
- Asset purchase and maintenance costs.

Purpose:

- Provides an overview of company resources.
- Helps management make informed decisions.
- Supports budgeting and planning.
- Improves asset utilization.

4. Proposed Technology Stack
The following technologies are proposed for developing the Asset Management System.
4.1. Frontend Technologies

- HTML5: Used to create the structure of web pages.
- CSS3: Used for styling, layouts, and visual design.
- JavaScript (ES6+): Handles dynamic functionality and user interactions.
- React.js: Used to build reusable UI components and interactive interfaces.
- Bootstrap 5: Helps create responsive and mobile-friendly layouts.

4.2. Backend Technologies

- Node.js: Handles server-side operations and asynchronous processing.
- Express.js: Simplifies backend development, API creation, and routing.

4.3. Database

- PostgreSQL: Stores and manages asset records, employee information, assignments, maintenance records, and asset history.
- Provides relational data management and data consistency.

4.4. Authentication and Security

- JWT (JSON Web Token): Used for token-based user authentication.
- bcrypt: Used to securely hash user passwords.
- Role-Based Access Control (RBAC): Manages permissions according to user roles.

4.5. API Development

- REST API: Enables communication between the frontend and backend.
- Supports operations such as creating, updating, retrieving, and deleting asset records.

4.6. Containerization

- Docker: Packages the application and its dependencies into containers.
- Docker Compose: Helps manage multiple services, such as frontend, backend, and database.

4.7. Version Control

- Git: Tracks code changes and manages different versions.
- GitHub: Hosts source code and supports collaboration and CI/CD integration.

### Reasons for Selecting This Technology Stack

- Provides a modern and responsive user interface.
- Supports secure user authentication and role-based permissions.
- Makes asset tracking and management easier.
- Handles relationships between employees, assets, and departments.
- Provides reliable database management.
- Simplifies application deployment.
- Supports future system expansion and maintenance.
Note: This is a proposed stack, not a requirement. The final technologies can vary depending on project size and organizational needs.