# Software Requirements Specification (SRS) for Online Food Ordering System

## Purpose
The purpose of this Software Requirements Specification (SRS) is to define the requirements for developing an Online Food Ordering System. This system aims to enable customers to browse restaurant menus and place orders efficiently, allow restaurant owners to receive real-time order notifications, and provide admins with tools to manage menus and system configurations. The SRS serves as a foundation for the system’s design, development, and testing phases within a 2-week timeline.

## Scope
The scope of the Online Food Ordering System includes core features such as menu browsing, order placement with confirmation, real-time order notifications for restaurant owners, and admin tools for menu management. It excludes advanced features like payment integration, delivery tracking beyond basic notifications, and multi-language support due to the 2-week timeline constraint.

## Product Features
- Menu Browsing: Customers can view categorized menus (e.g., appetizers, mains) with a loading time of under 3 seconds.
- Order Placement: Customers can place orders online with confirmation displayed within 2 seconds.
- Real-Time Notifications: Restaurant owners receive order notifications within 5 seconds.
- Menu Management: Admins can update menu items with changes saved within 2 seconds.

## User Roles
- Customer: The end user who browses menus, places orders, and views order status.
- Restaurant Owner: The service provider who receives orders, updates statuses, and manages the menu.
- Admin: The system manager who updates menus, manages user accounts, and configures system settings.

## Constraints
- Timeline: The project must be completed within 2 weeks (April 26 – May 10, 2025).
- Resources: Limited to free tools (e.g., JIRA, Draw.io, Google Docs).
- Technical: No payment gateway integration due to complexity; basic UI and backend only.

## Functional Requirements
| Code   | Description                                      | Type           |  
|--------|--------------------------------------------------|----------------|  
| FR-01  | Browse restaurant menus with categories         | Functional     |  
| FR-02  | Place orders online with confirmation           | Functional     |  
| FR-03  | Receive real-time order notifications           | Functional     |  
| FR-04  | Manage menus and update items                   | Functional     |

## Non-Functional Requirements
| Code   | Description                                      | Type           |  
|--------|--------------------------------------------------|----------------|  
| NFR-01 | Menu loads within 3 seconds                     | Non-Functional |  
| NFR-02 | System supports 100 concurrent users            | Non-Functional |  
| NFR-03 | Notification sent within 5 seconds              | Non-Functional |  
| NFR-04 | Order confirmation shown within 2 seconds       | Non-Functional |  
| NFR-05 | Menu updates saved within 2 seconds             | Non-Functional |

## UI, Hardware, Software Interfaces
- UI: A simple HTML/CSS frontend for menu browsing and order placement.
- Hardware: Standard laptop/server (e.g., 8GB RAM, 2.5GHz processor) to support development and testing.
- Software: Node.js for backend logic, MySQL for database management (to be finalized in design phase).

## Communication Protocols
The system will use REST APIs to enable real-time notifications from the backend to restaurant owners. Detailed implementation (e.g., endpoints, authentication) will be defined in the design phase.

## Version
Version 1.0, Drafted on April 29, 2025
