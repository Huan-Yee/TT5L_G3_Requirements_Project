> ![D:\\Google
> Drive\\\_desktop\\Saya\\MMU-New-logow.fw\_.png](media/image1.png){width="4.31849956255468in"
> height="1.241307961504812in"}
>
> CSE 6334 Software Requirements Engineering
>
> Project Part 1: SRS
>
> Group :7

+-----------------------------------+-----------------------------------+
| Name                              | > Student ID                      |
+===================================+:=================================:+
| > Akid Syazwan bin Nor Azman Shah | > 1211111238                      |
+-----------------------------------+-----------------------------------+
| > Teng Chay Xuan                  | > 1231300802                      |
+-----------------------------------+-----------------------------------+
| > Kishen Kumar A/L Kumaran        | > 1211111528                      |
+-----------------------------------+-----------------------------------+
| > Shannon Fernandez               | > 1211106748                      |
+-----------------------------------+-----------------------------------+

[1. Introduction [2](#introduction)](#introduction)

[1.1. Purpose [2](#purpose)](#purpose)

[1.2. Scope [2](#scope)](#scope)

[1.3. Product overview [2](#product-overview)](#product-overview)

[1.3.1. Product perspective
[2](#product-perspective)](#product-perspective)

[1.3.2. System Interfaces [3](#system-interfaces)](#system-interfaces)

[1.3.2.1. User Interfaces [4](#user-interfaces)](#user-interfaces)

[1.3.2.2. Hardware Interfaces
[4](#hardware-interfaces)](#hardware-interfaces)

[1.3.2.3. Software Interfaces
[5](#software-interfaces)](#software-interfaces)

[1.3.2.4. Communications Interfaces
[5](#communications-interfaces)](#communications-interfaces)

[1.3.2.5. Memory Constraints
[6](#memory-constraints)](#memory-constraints)

[1.3.2.6. Operations [6](#operations)](#operations)

[1.3.2.7. Site Adaptation Requirements
[7](#site-adaptation-requirements)](#site-adaptation-requirements)

[1.3.3. Product function [8](#product-function)](#product-function)

[1.3.4. User characteristics
[9](#user-characteristics)](#user-characteristics)

[1.3.5. Limitations [10](#limitations)](#limitations)

[1.3.5.1. Definitions [11](#definitions)](#definitions)

[2. References [11](#references)](#references)

[3. Requirements [12](#requirements)](#requirements)

[3.1. Functions [12](#functions)](#functions)

[3.1.1. Functions Activity/Sequence Diagrams
[14](#functions-activitysequence-diagrams)](#functions-activitysequence-diagrams)

[3.1.1.1. Login Activity Diagram
[14](#login-activity-diagram)](#login-activity-diagram)

[3.1.1.2. Register to System Activity Diagram
[14](#register-to-system-activity-diagram)](#register-to-system-activity-diagram)

[3.1.1.3. Join Cub Activity Diagram
[15](#join-cub-activity-diagram)](#join-cub-activity-diagram)

[3.1.1.4. View Upcoming Events Activity Diagram
[15](#view-upcoming-events-activity-diagram)](#view-upcoming-events-activity-diagram)

[3.1.1.5. RSVP for Events Activity Diagram
[16](#rsvp-for-events-activity-diagram)](#rsvp-for-events-activity-diagram)

[3.1.1.6. Manage Club Members Activity Diagram
[16](#manage-club-members-activity-diagram)](#manage-club-members-activity-diagram)

[3.1.1.7. Create Event Proposal Sequence Diagram
[17](#create-event-proposal-sequence-diagram)](#create-event-proposal-sequence-diagram)

[3.1.1.8. Submit Budget Proposal Activity Diagram
[17](#submit-budget-proposal-activity-diagram)](#submit-budget-proposal-activity-diagram)

[3.1.1.9. Submit Venue Booking Proposal Activity Diagram
[18](#submit-venue-booking-proposal-activity-diagram)](#submit-venue-booking-proposal-activity-diagram)

[3.1.1.10. Cancel Event Sequence Diagram
[18](#cancel-event-sequence-diagram)](#cancel-event-sequence-diagram)

[3.1.1.11. View RSVP for Event Activity Diagram
[19](#view-rsvp-for-event-activity-diagram)](#view-rsvp-for-event-activity-diagram)

[3.1.1.12. Submit Event Report Activity Diagram
[19](#submit-event-report-activity-diagram)](#submit-event-report-activity-diagram)

[3.1.1.13. Monitor Club and Event Activity Activity Diagram
[20](#monitor-club-and-event-activity-activity-diagram)](#monitor-club-and-event-activity-activity-diagram)

[3.1.1.14. Generate Report Activity Diagram
[21](#generate-report-activity-diagram)](#generate-report-activity-diagram)

[3.2. Performance requirements
[22](#performance-requirements)](#performance-requirements)

[3.3. Usability requirements
[22](#usability-requirements)](#usability-requirements)

[3.4. Interface requirements
[23](#interface-requirements)](#interface-requirements)

[3.4.1. System interface [23](#system-interface)](#system-interface)

[3.4.2. User interface [23](#user-interface)](#user-interface)

[3.4.3. Hardware interface
[24](#hardware-interface)](#hardware-interface)

[3.4.4. Software interface
[24](#software-interface)](#software-interface)

[3.4.5. Communication interface
[25](#communication-interface)](#communication-interface)

[3.5. Logical database requirements
[25](#logical-database-requirements)](#logical-database-requirements)

[3.6. Design constraint [26](#design-constraint)](#design-constraint)

[3.7. Software system attributes
[27](#software-system-attributes)](#software-system-attributes)

[3.7.1. Reliability [28](#reliability)](#reliability)

[3.7.2. Availability [28](#availability)](#availability)

[3.7.3. Security [28](#security)](#security)

[3.7.4. Maintainability [29](#maintainability)](#maintainability)

[3.7.5. Portability [29](#portability)](#portability)

[3.8. Supporting information
[29](#supporting-information)](#supporting-information)

[3.8.1. Sample Input/Output Formats
[29](#sample-inputoutput-formats)](#sample-inputoutput-formats)

[3.8.2. Supporting or Background Information
[30](#supporting-or-background-information)](#supporting-or-background-information)

[3.8.3. Problem Statement (What the Software Solves)
[30](#problem-statement-what-the-software-solves)](#problem-statement-what-the-software-solves)

[4. Verification [31](#verification)](#verification)

[4.1. Verification approach.
[31](#verification-approach.)](#verification-approach.)

[4.2. Verification criteria
[32](#verification-criteria)](#verification-criteria)

[4.2.1. Unit Testing Verification Criteria
[32](#unit-testing-verification-criteria)](#unit-testing-verification-criteria)

[4.2.2. Integration testing verification criteria
[33](#integration-testing-verification-criteria)](#integration-testing-verification-criteria)

[4.2.3. Functional testing verification criteria
[34](#functional-testing-verification-criteria)](#functional-testing-verification-criteria)

[4.2.4. User acceptance testing verification criteria
[35](#user-acceptance-testing-verification-criteria)](#user-acceptance-testing-verification-criteria)

[4.2.5. Performance verification criteria
[36](#performance-verification-criteria)](#performance-verification-criteria)

[4.2.6. Usability verification criteria
[37](#usability-verification-criteria)](#usability-verification-criteria)

[5. Appendices [37](#appendices)](#appendices)

[5.1. Assumptions and Dependencies
[37](#assumptions-and-dependencies)](#assumptions-and-dependencies)

#  Introduction

## Purpose

The purpose of this document is to define the software requirements for
the Student Club Management System. This document outlines the intended
functionality, user interfaces, constraints, and system interactions for
developers, testers, and stakeholders.

## Scope

The Student Club Management System will serve as a centralized digital
platform that facilitates the administration of student clubs, allowing
for effective member management, event coordination, financial tracking,
and venue booking. It aims to increase efficiency, transparency, and
accessibility for students and university administrators.

## Product overview

> The Student Club Management System (CMS) with Budget and Venue
> integration is designed to serve as a centralized platform for
> managing the various activities of student club within the university.
> The aim of this system is to make necessary task like club membership
> registration, event planning, budget submission and approval and venue
> booking more efficient. The platform will also integrate with the
> university space reservation and finance management system to
> facilitate easier departmental cooperation

### Product perspective

The Club Management System (CMS) is a web-based solution that function
as a centralized platform for overseeing student club activities at the
university. It aims to facilitate smooth communication among different
parties including student, club committee, external system like
financial and venue system. This system is a part of the university
ecosystem and connect with the institutional platform to enhance
administrative workflows and enrich user experience. Figure 1.3.1 below
show the context diagram of the system.

> ![](media/image2.png){width="5.406248906386701in"
> height="3.0854297900262466in"}
>
> *Figure 1.3.1 CMS context diagram*

### System Interfaces

> External Systems and Interactions:

  -----------------------------------------------------------------------
  **System**                        **Functionality**
  --------------------------------- -------------------------------------
  University Financial System       Submit and retrieve status of budget
                                    proposals.

  Venue Booking System              Submit venue booking requests and get
                                    confirmation or denial.

  University Authentication         Authenticate users and assign roles
                                    (e.g., student, committee, admin).
  -----------------------------------------------------------------------

### 

#### User Interfaces

> The Student Club Management System will include intuitive user
> interfaces customized by role:

+--------------------+-------------------------------------------------+
| > **User Role**    | > **Interface Description**                     |
+:===================+:================================================+
| > Club Member      | > Dashboard to register for clubs, view events, |
|                    | > and RSVP.                                     |
+--------------------+-------------------------------------------------+
| > Club Committee   | > Panel for managing members, submitting        |
|                    | > proposals, and tracking events.               |
+--------------------+-------------------------------------------------+
| > Administrator    | > Admin portal for monitoring activity,         |
|                    | > generating reports, and approving requests.   |
+--------------------+-------------------------------------------------+

> **UI Characteristics:**

- Mobile-responsive design making it easy for students to access on the
  go.

- Compliant with the university's digital accessibility and branding
  standards.

- Easy navigation with a top menu, dashboard tiles, and modal forms for
  quick interactions.

#### Hardware Interfaces

> The Student Club Management System will run on cloud infrastructure
> and does **not** directly interface with hardware devices. However, it
> must be compatible with:

+--------------------+-------------------------------------------------+
| > **Hardware       | > **Requirement**                               |
| > Type**           |                                                 |
+====================+=================================================+
| > Desktop / Laptop | > Browsers: Chrome, Firefox, Safari, Edge       |
|                    | > (latest 2 versions).                          |
+--------------------+-------------------------------------------------+
| > Mobile Devices   | > Responsive UI must work on all screen sizes   |
| > (iOS/Android)    |                                                 |
+--------------------+-------------------------------------------------+

#### Software Interfaces

> The Student Club Management System requires integration with the
> following external and internal software systems:

+-------------------+----------------------------------+---------------+
| > **Software      | > **Purpose**                    | > **Source**  |
| > Product**       |                                  |               |
+===================+==================================+===============+
| > University      | > Budget request processing and  | > Finance     |
| > Financial       | > approval workflows             | > Department  |
| > System          |                                  |               |
+-------------------+----------------------------------+---------------+
| > Venue Booking   | > Room reservation and calendar  | > Campus      |
| > System          | > sync                           | > Facilities  |
|                   |                                  | > Unit        |
+-------------------+----------------------------------+---------------+
| > University      | > Secure login and session       | > IT          |
| > Login System    | > management                     | > Department  |
+-------------------+----------------------------------+---------------+
| > PostgreSQL      | > Backend data persistence       | > Open Source |
| > Database        |                                  |               |
+-------------------+----------------------------------+---------------+
| > Node.js         | > Server-side logic              | > Open Source |
| > (Backend        |                                  |               |
| > Runtime)        |                                  |               |
+-------------------+----------------------------------+---------------+

#### Communications Interfaces

> The Student Club Management System will utilize the following
> communication interfaces:

- **Protocol**: HTTPS over TLS 1.3

- **Internal Communication**: REST APIs between frontend and backend
  components

- **External Communication**:

  - **University Authentication Service** via OAuth2 SSO

  - **Financial System API** via secure REST API endpoints

  - **Venue Reservation System** via authenticated REST API

- **Email Notifications**: SMTP protocol with university mail server
  (student.mmu.edu.my) for alerts and confirmations (event approval,
  RSVP status)

> **Security Notes**:

- All communications are encrypted end-to-end.

- APIs require token-based authentication using OAuth2 bearer tokens.

#### Memory Constraints

> The Student Club Management System will adhere to the following memory
> constraints:

- **Primary Memory (RAM)**:

  - Minimum server RAM: 4 GB

  - Recommended: 8 GB for production environment with caching enabled

- **Secondary Memory (Storage)**:

  - Minimum disk space: 50 GB for application, logs, and file uploads

  - Backup: minimum of 30 days

- **Database**:

  - PostgreSQL data volume expected to grow with number of clubs and
    members. This will require periodic archiving to be implemented in
    the system.

#### Operations

> The Student Club Management System is designed to support both
> **interactive** and **automated** operations, including:
>
> **a) Modes of Operation:**

- **User-Initiated**:

  - Club committee submits event and budget proposals.

  - Admin approves or rejects requests.

  - Students RSVP to events.

- **Scheduled/Automated**:

  - Daily sync with venue and finance systems.

  - Email Notification (daily or real-time).

> **b) Operation Timing:**

- **Interactive Use**: 24/7 user access from web interface.

- **Unattended Use**:

  - Nightly backups

  - Log cleanup

  - API-based data sync during off-peak hours

> **c) Support Functions:**

- Data validation

- Duplicate checks for event names, venues, and schedules

- Conflict detection for venue booking

> **d) Backup & Recovery:**

- Full database backup every 24 hours.

- Recovery procedures documented and tested quarterly.

- Incremental backups every 6 hours.

- Logs retained for 30 days minimum.

#### Site Adaptation Requirements

> The Student Club Management includes some site-specific customization
> requirements:
>
> **a) Initialization Sequences:**

- Institution-specific data:

  - Club categories

  - Venue types

  - Approval workflows

- Safety constraints for budget caps and event duration rules are
  configurable per institution.

> **b) Configurable Features:**

- Branding (logo, colour scheme, footer text)

- Notification rules (e.g., when to send reminders)

- Admin roles and permissions can be adapted based on the university's
  organizational hierarchy

### Product function 

+------------------------+---------------------------------------------+
| **Stakeholder**        | **Function**                                |
+========================+:===========================================:+
| **Club Member**        | Register to system                          |
|                        +---------------------------------------------+
|                        | Login to system                             |
|                        +---------------------------------------------+
|                        | Join the club                               |
|                        +---------------------------------------------+
|                        | View upcoming events                        |
+------------------------+---------------------------------------------+
|                        | RSVP for events                             |
+------------------------+---------------------------------------------+
| **Club Committee**     | Login to system                             |
|                        +---------------------------------------------+
|                        | Manage club members                         |
|                        +---------------------------------------------+
|                        | Create event proposal                       |
|                        +---------------------------------------------+
|                        | Submit budget proposal                      |
|                        +---------------------------------------------+
|                        | Submit venue booking proposal               |
|                        +---------------------------------------------+
|                        | Cancel event                                |
|                        +---------------------------------------------+
|                        | Submit event report                         |
+------------------------+---------------------------------------------+
| **Admin**              | Login to system                             |
|                        +---------------------------------------------+
|                        | Monitor club and event activity             |
|                        +---------------------------------------------+
|                        | Generate reports                            |
+------------------------+---------------------------------------------+
| **Financial Department | View, approve or decline budget proposal    |
| Staff**                |                                             |
+------------------------+---------------------------------------------+
| **Venue Booking        | View, approve or decline venue booking      |
| Staff**                | proposals                                   |
+------------------------+---------------------------------------------+

### User characteristics 

There are several key user roles in Club Management System (CMS),
including club member, club committee, admin, finance and venue officer.
The following table shows the expected level of knowledge for each user.

System internal user:

  ------------------------------------------------------------------------
  Role        Description                 Required knowledge
  ----------- --------------------------- --------------------------------
  Club member A student who participates  Basic knowledge of using the CMS
              in the university club      to register, view events and
                                          RSVP in the events.

  Club        A leader in the club who    Knowledge on how to manage club
  committee   will manage the club        information, submit the event
              activities and submission   proposal include venue and
                                          finance request, and submit
                                          event report.

  Admin       University staff that       Knowledge in user management,
              responsible for managing    activity monitoring, generating
              and oversee the overall     report in the system
              club activities in the      
              university.                 
  ------------------------------------------------------------------------

System external user:

  ------------------------------------------------------------------------
  Role           Description               Knowledge
  -------------- ------------------------- -------------------------------
  Finance staff  University staff who      Ability to track budget, review
                 handle the financial      and approve/reject club
                 matters                   application, and update
                                           financial status within the
                                           CMS.

  Venue staff    University staff who      Knowledge in venue booking and
                 manage venue booking and  scheduling and maintaining
                 scheduling.               venue usage record in CMS.
  ------------------------------------------------------------------------

### Limitations

Club Management System (CMS) provide an efficient platform for managing
student club activities, there are several limitations as well that may
affect its functionality and performance, these limitations are outlined
in the table below:

  -----------------------------------------------------------------------
  Limitations          Description
  -------------------- --------------------------------------------------
  Limited to           The system developed specifically for university
  university club only club only, external organization cannot use the
                       platform.

  Venue booking        The venue viewing/booking depend on the
  constraints          integration with the university venue system, if
                       the university system is offline, the information
                       will be inaccurate.

  No mobile            The CMS is a web-based application and may not be
  application          fully optimized for mobile device. A dedicated
                       mobile application is not available at this
                       moment.

  Cannot use without   The CMS is a web-based application which needed
  internet             internet connection to use. Location with weak or
                       no internet connection difficult to use it.
  -----------------------------------------------------------------------

#### Definitions 

  -----------------------------------------------------------------------
  Definition      Description
  --------------- -------------------------------------------------------
  CMS             Club Management System (CMS) is a software application
                  design to manage and support university club
                  activities. It allows user to register, submit
                  proposal, manage membership, and track event
                  participation.

  Club member     A registered university student who joined the club
                  through the official enrolment process.

  Club Committee  A member elected or appointed to a leadership position
                  in the club.

  Event           An organized activity planned by a club that requires
                  submission of proposal including the financial
                  resource, venue booking and university approval.

  Admin           University staff that responsible for managing and
                  oversee the overall club in the university.

  Finance Module  An integrated part of the CMS that handle financial
                  processes.

  Venue Module    An integrated part of the CMS that handle venue booking
                  processes.
  -----------------------------------------------------------------------

# References

This document is prepared in reference to the following documents:

1.  IEEE. (2018). ISO/IEC/IEEE 29148:2018 Systems and software
    engineering--- Life cycle processes--- Requirements engineering.

> <https://www.iso.org/standard/72089.html>

2.  M. Hariprasad, N. N, N. Dey, P. D and R. Kumar P, \"College Club
    Activity Management System,\" 2023 7th International Conference on
    Computation

> System and Information Technology for Sustainable Solutions (CSITSS),
>
> Bangalore, India, 2023, pp. 1-5, doi:
> 10.1109/CSITSS60515.2023.10334208.

3.  Wiegers, K., & Beatty, J. (2013). Software requirements (3rd ed.).
    Microsoft Press.

# Requirements

## Functions

In this section, the key function of the Club Management System (CMS) is
outlined. This function will represent the core activities that user can
perform in the system. The diagram 3.1 below is the use case diagram
which show overview of how different user can interact with the system
and table 3.1 show the detailed of each function.

![A diagram of a student club management system AI-generated content may
be incorrect.](/media/image13.png){width="5.792832458442694in"
height="4.64583552055993in"}*Figure 3.1 Use case diagram*

  ---------------------------------------------------------------------------
  **Function   **Function Name**   **Description**
  Code**                           
  ------------ ------------------- ------------------------------------------
  F001         Login to system     Allows club members, committee and system
                                   admin to access the system using their
                                   credentials.

  F002         Register to system  Enables students to register in the
                                   system.

  F003         Join club           Enable student to join the available club
                                   in university

  F004         View Upcoming       Member can request to displays a list of
               Events              upcoming events organized by clubs.

  F005         RSVP for Events     Allows members to RSVP for events they are
                                   interested in attending.

  F006         Manage Club Members Enables committee members to manage member
                                   lists.

  F007         Create Event        Committee can draft a proposal for a new
               Proposal            event.

  F008         Submit Budget       Committee submits budget requests to the
               Proposal            finance system for approval.

  F009         Submit Venue        Committee sends a booking request to
               Booking Proposal    reserve a venue through the venue system.

  F010         Cancel Event        Committee can cancel planned events due to
                                   various reasons.

  F011         View RSVP for event Committee can view the RSVP result in the
                                   system for the event

  F012         Submit Event Report After an event, committee submits a report
                                   with results and feedback.

  F013         Monitor Club and    Admin can track all club and event
               Event Activity      activities through the system.

  F014         Generate Reports    Admin generates event and activity reports
                                   for recordkeeping or analysis.
  ---------------------------------------------------------------------------

*Table 3.1 List of function*

### Functions Activity/Sequence Diagrams

#### Login Activity Diagram

![](/media/image14.png){width="2.762419072615923in"
height="3.284825021872266in"}

*Figure 3.1.1.1 Login Activity Diagram*

#### Register to System Activity Diagram

![](/media/image15.png){width="2.788575021872266in"
height="3.062713254593176in"}

*Figure 3.1.1.2 Register to System Activity Diagram*

#### Join Cub Activity Diagram

![](/media/image16.png){width="3.4714763779527558in"
height="4.076110017497813in"}

*Figure 3.1.1.3 Join Club to System Activity Diagram*

#### View Upcoming Events Activity Diagram

![](media/image7.png){width="3.29375in" height="3.097916666666667in"}

*Figure 3.1.1.4 View Upcoming Events Activity Diagram*

#### RSVP for Events Activity Diagram

![](media/image8.png){width="1.8479166666666667in"
height="3.652083333333333in"}

*Figure 3.1.1.5 RSVP for Events Activity Diagram*

#### Manage Club Members Activity Diagram

![](/media/image17.png){width="1.7357217847769029in"
height="3.507833552055993in"}

*Figure 3.1.1.6 Manage Club Members Activity Diagram*

#### Create Event Proposal Sequence Diagram

![](/media/image18.png){width="5.193525809273841in"
height="3.6877712160979876in"}

*Figure 3.1.1.7 Create Event Proposal Sequence Diagram*

#### Submit Budget Proposal Activity Diagram

![](media/image11.png){width="2.38043416447944in"
height="3.230640857392826in"}

*Figure 3.1.1.8 Submit Budget Proposal Activity Diagram*

#### Submit Venue Booking Proposal Activity Diagram

![](/media/image19.png){width="2.684712379702537in"
height="3.643596894138233in"}

*Figure 3.1.1.9 Submit Venue Booking Proposal Activity Diagram*

#### Cancel Event Sequence Diagram 

![](/media/image1a.png){width="5.667344706911636in"
height="3.618649387576553in"}

*Figure 3.1.1.10 Cancel Event Sequence Diagram*

#### View RSVP for Event Activity Diagram

![](/media/image1b.png){width="1.9144925634295713in"
height="3.3152176290463693in"}

*Figure 3.1.1.11 View RSVP for Event Activity Diagram*

#### Submit Event Report Activity Diagram

![](/media/image1c.png){width="1.9183584864391952in"
height="3.683333333333333in"}

*Figure 3.1.1.12 Submit Event Report Activity Diagram*

#### Monitor Club and Event Activity Activity Diagram

![](/media/image1d.png){width="1.7412106299212597in"
height="3.589583333333333in"}

*Figure 3.1.1.13 Monitor Club and Event Activity* *Activity Diagram*

#### Generate Report Activity Diagram

![](/media/image1e.png){width="2.759514435695538in"
height="4.729558180227472in"}

*Figure 3.1.1.14 Generate Report Activity Diagram*

## Performance requirements

  ------------------------------------------------------------------------
  Requirement ID   Description                                Priority
  ---------------- ------------------------------------------ ------------
  REQ_P001         The system should load all dashboard       High
                   components in 3 seconds for 90% of users   

  REQ_P002         Event RSVP submission shall process within High
                   2 seconds during peak usage.               

  REQ_P003         Budget proposal submission to finance      Medium
                   system should receive response within 5    
                   seconds                                    

  REQ_P004         Venue booking function shall synchronize   Medium
                   with external venue system within 5        
                   second.                                    

  REQ_P005         Report for up to 1000 record shall         Low
                   generate within 10 second.                 
  ------------------------------------------------------------------------

## Usability requirements

  -------------------------------------------------------------------------
  Requirement ID  Description                       Metric       Priority
  --------------- --------------------------------- ------------ ----------
  REQ_U001        User should complete              ≤ 3 clicks   High
                  registration/login within 3                    
                  clicks from the homepage                       

  REQ_U002        Club committee shall submit event ≤ 3 minutes  High
                  proposal within 3 minutes                      
                  (average)                                      

  REQ_U003        Member should complete RSVP to    ≤ 3 clicks   Medium
                  the event within 5 clicks                      

  REQ_U004        90% of users shall rate the       Survey score High
                  system's ease of use as ≥4/5 on a              
                  post-training survey.                          
  -------------------------------------------------------------------------

## Interface requirements 

### System interface

  ---------------------------------------------------------------------------
  **System**       **Interface   **Benefits**
                   Type**        
  ---------------- ------------- --------------------------------------------
  **University     OAuth2 / SAML Ensures secure access with Single Sign-On
  Authentication                 (SSO), reducing login friction and improving
  System**                       user trust.

  **Financial      REST API      Enables automated submission and real-time
  Management                     tracking of budget proposals, reducing
  System**                       manual paperwork.

  **Venue          REST API      Facilitates efficient venue booking by
  Reservation                    checking availability and automating
  System**                       approvals.
  ---------------------------------------------------------------------------

### User interface

> Key UI Features:

- Top Navigation Bar: Provide access to the Dashboard, Club, Upcoming
  Events and Profile.

- **Role-based Dashboards**:

  - **Members**: See available clubs, RSVP to events.

  - **Committee**: Submit event proposals, manage members, track
    budgets.

  - **Admins**: Approve proposals, monitor reports.

- **Forms**:

  - Event proposal form (fields for title, date, description, budget,
    venue)

  - Member registration form

- **Interactive Components**:

  - Event calendar

  - RSVP buttons

  - Notifications panel

The interface will follow modern UI/UX principles and be accessible on
desktop and mobile devices.

### Hardware interface

> The system should support the following hardware-related
> considerations:

- **Client Devices**:

  - Laptops and desktops (Windows, macOS, Linux)

  - Mobile devices (iOS, Android) with modern browsers

- **Server Infrastructure**:

  - Deployed on cloud or university-hosted virtual machines

  - Supports standard networking, monitoring, and backup operations

### Software interface

  -----------------------------------------------------------------------------
  **Software    **Version/Spec**   **Benefits**
  Product**                        
  ------------- ------------------ --------------------------------------------
  University    v3.2+ (API)        Enables efficient, automated processing of
  Financial                        budget requests with real-time status
  System                           tracking.

  Venue Booking v2.5 (API)         Reduces scheduling conflicts and manual
  System                           coordination by providing up-to-date room
                                   availability and booking integration.

  University    OAuth2, SAML       Enhances security and user convenience
  Login System                     through centralized authentication and
                                   role-based access control.

  PostgreSQL    13+                Provides reliable, scalable, and performant
  Database                         storage of system data including users,
                                   events, and proposals.

  Node.js       18.x               Offers efficient handling of asynchronous
  (Backend                         tasks and API requests, contributing to fast
  Runtime)                         and responsive system performance.
  -----------------------------------------------------------------------------

### Communication interface

  -------------------------------------------------------------------------
  **Interface**   **Protocol**     **Use**
  --------------- ---------------- ----------------------------------------
  Web             HTTPS (TLS 1.3)  For secure API communication and
  communication                    frontend/backend interaction

  API endpoints   REST (JSON)      For financial system, venue system, and
                                   internal APIs

  Notifications   SMTP (TLS)       For sending email alerts on budget/venue
                                   decisions
  -------------------------------------------------------------------------

## Logical database requirements

> ![](/media/image1f.png){width="6.64383530183727in"
> height="4.041666666666667in"}

Relationships:

- A **User** can be a member of many **Clubs**; a **Club** has many
  **Users** → *many-to-many* via **Membership**.

- A **Club** can organize multiple **Events**; each **Event** belongs to
  one **Club** → *one-to-many*.

- Each **Event** can have multiple **RSVPs** by **Users** →
  *one-to-many*.

- Each **Budget Proposal** is linked to one **Club** and optionally to
  one **Event**.

- An **Event** is held at one **Venue**; a **Venue** may host multiple
  **Events** over time.

Constraints:

- **Unique Constraints** on email (User), club name (Club), and event
  name per date (Event).

- **Foreign Keys** between related entities to ensure referential
  integrity.

- **Check Constraints** for status fields (get_status (\'pending\',
  \'approved\', \'rejected\')).

## Design constraint 

> The design of the Student Club Management System is subject to several
> constraints arising from institutional policies, technical
> environments, and regulatory compliance.

Technical Constraints:

- **Authentication** must use the university's existing **OAuth2 based
  SSO system**.

- The system must be developed using **open-source technologies** (e.g.,
  Node.js, PostgreSQL).

- **RESTful API architecture** must be followed for external
  integrations (Financial and Venue systems).

- The web interface must be **responsive** and usable on standard
  browsers (Chrome, Firefox, Safari, Edge).

Institutional Constraints:

- The system must comply with **university IT governance policies**,
  including data privacy and audit requirements.

- Only **authorized personnel** (admins, committee members) may access
  approval or modification features.

Regulatory/Standards Constraints:

- Must comply with **data protection regulations** (e.g., FERPA or GDPR
  equivalents in your jurisdiction).

- All student records and event data must be **encrypted in transit (TLS
  1.3)** and at rest.

- 

> UI/UX Constraints:

- Interface design must follow the **university branding guidelines**
  including logo, colours, and font standards.

- Navigation must be simple and consistent across all modules.

## Software system attributes 

> This section specifies the key quality attributes expected from the
> **Student Club Management System (SCMS)** and their
> implementation-related requirements.

### Reliability

  ------------------------------------------------------------------------------------
  **Requirement   **Description**                          **Priority**   **Author**
  ID**                                                                    
  --------------- ---------------------------------------- -------------- ------------
  REQ_SCMS_001    SCMS shall recover from unexpected       High           Project Team
                  crashes within 60 seconds without data                  
                  loss.                                                   

  ------------------------------------------------------------------------------------

### Availability

  ------------------------------------------------------------------------------------
  **Requirement   **Description**                          **Priority**   **Author**
  ID**                                                                    
  --------------- ---------------------------------------- -------------- ------------
  REQ_SCMS_002    SCMS shall maintain at least 99.9%       High           Project Team
                  uptime during weekdays from 8 AM to 6                   
                  PM.                                                     

  ------------------------------------------------------------------------------------

### Security

  ------------------------------------------------------------------------------------
  **Requirement   **Description**                          **Priority**   **Author**
  ID**                                                                    
  --------------- ---------------------------------------- -------------- ------------
  REQ_SCMS_003    SCMS shall implement role-based access   High           Project Team
                  control for all user operations.                        

  REQ_SCMS_004    SCMS shall encrypt all sensitive data    High           Project Team
                  using TLS 1.3 during transmission and                   
                  AES-256 at rest.                                        
  ------------------------------------------------------------------------------------

### Maintainability

  ----------------------------------------------------------------------------------
  **Requirement   **Description**                        **Priority**   **Author**
  ID**                                                                  
  --------------- -------------------------------------- -------------- ------------
  REQ_SCMS_005    SCMS code shall follow standard coding Medium         Project Team
                  guidelines and include inline                         
                  documentation.                                        

  REQ_SCMS_006    SCMS shall achieve at least 80%-unit   Medium         Project Team
                  test coverage for critical modules.                   
  ----------------------------------------------------------------------------------

### Portability

  --------------------------------------------------------------------------------
  **Requirement   **Description**                      **Priority**   **Author**
  ID**                                                                
  --------------- ------------------------------------ -------------- ------------
  REQ_SCMS_007    SCMS shall run on both Linux and     High           Project Team
                  Windows environments using Docker                   
                  containers.                                         

  REQ_SCMS_008    SCMS shall not include any           Medium         Project Team
                  OS-specific file paths or                           
                  dependencies.                                       
  --------------------------------------------------------------------------------

## Supporting information

### Sample Input/Output Formats

+--------------+-----------------------------+----------------------------+
| **Function** | **Sample Input**            | **Expected Output**        |
+==============+=============================+============================+
| Club         | Name: Robotics Club         | Club created successfully. |
| Registration |                             | Status: "Pending\"         |
|              | Advisor: Prof. A. Kumar     |                            |
+--------------+-----------------------------+----------------------------+
| Event        | Title: Hackathon 2025       | Event created. Budget      |
| Proposal     |                             | submission link generated. |
|              | Date: 2025-11-10            | Status: Draft              |
|              |                             |                            |
|              | Venue: Auditorium           |                            |
+--------------+-----------------------------+----------------------------+
| RSVP         | Event ID: 121112526         | \"RSVP confirmed. Check    |
| Submission   |                             | your university email for  |
|              | User ID: 801                | the event invite.\"        |
+--------------+-----------------------------+----------------------------+
| Budget       | Club: AI Society            | \"Budget proposal          |
| Request      |                             | submitted. Awaiting        |
|              | Amount: \$450               | finance approval.\"        |
|              |                             |                            |
|              | Justification: Workshop     |                            |
|              | equipment                   |                            |
+--------------+-----------------------------+----------------------------+

### Supporting or Background Information

- The university currently manages student clubs using a combination of
  email, Google Forms, and paper-based budget forms.

- There is no existing unified system for event, budget, and member
  tracking --- causing delays, miscommunication, and duplication.

- The SCMS will serve as the first centralized platform for these tasks,
  integrating with the university\'s finance and venue APIs.

- Reference Materials:

  - Student Affairs Handbook

  - University Financial Workflow Documentation

  - Venue Booking Policy Manual

### Problem Statement (What the Software Solves)

> The current method of managing student club activities is fragmented
> and inefficient:

- Event proposals are submitted manually via forms and emails, leading
  to inconsistent approvals and lost requests.

- Budget submissions are often delayed due to missing paperwork or
  manual routing.

- Club membership rosters are not centralized, making it hard to
  validate participation or assign privileges.

- Venue booking conflicts occur due to lack of real-time visibility.

> The SCMS addresses these issues by:

- Automating workflows for proposals, approvals, and bookings.

- Maintaining a real-time dashboard for all stakeholders.

- Centralizing membership and role management per club.

- Reducing administrative load through streamlined integrations and
  audit trails.

# Verification

This section will describe the approach and criteria used to verify the
University Club Management System (CMS) meets its functional and
non-functional requirements. Verification ensures that the developed
system will meet the stakeholder\'s expectation, complete and perform
according to the specification

##  Verification approach.

The verification of CMS will be conducted using various software testing
technique throughout the development lifecycle. The table below outlines
the verification method, responsible parties, timeline and location for
each of the technique. Table 4.1 below show the approach will be used.

Table 4.1 Verification approach list

  --------------------------------------------------------------------------------------
  **Verification   **Description**         **Responsible   **Timeline**   **Location**
  technique**                              parties**                      
  ---------------- ----------------------- --------------- -------------- --------------
  **Unit Testing** Verifies individual     Developer       Week 4 -- Week Developer
                   modules function as                     7              environment
                   intended.                                              

  **Integration    Ensures interaction     Developers, QA  Week 7 -- Week Staging/test
  Testing**        between modules works   Tester          9              environment
                   as expected.                                           

  **Functional     Validate that each      QA team,        Week 9 -- Week University
  Testing**        function (F001--F013)   project         10             test lab
                   meets the requirements. supervisor                     

  **System         Assesses the entire     QA team         Week 10 --     Controlled
  Testing**        system behaviour,                       Week 11        lab/test
                   including performance                                  server
                   and security.                                          

  **User           Real users will test    End-users, QA   Week 11 --     Campus lab or
  Acceptance       the system to confirm   team            Week 12        virtual
  Testing (UAT)**  it meets real-world                                    environment
                   need.                                                  
  --------------------------------------------------------------------------------------

## Verification criteria

### Unit Testing Verification Criteria

  ------------------------------------------------------------------------
  **Module**     **Test Case**                     **Expected Output**
  -------------- --------------------------------- -----------------------
  Login          Validate correct                  Return true, user
                 username/password                 logged in

                 Validate incorrect password       Return false, login
                                                   fails

  Registration   Register new user with valid      Return success, user
                 inputs                            stored in DB

                 Register with missing student ID  Throw validation error

  Event module   Create event with valid data      Event object created
                                                   and stored

  RSVP module    Submit RSVP with valid member ID  RSVP saved;
                 and event ID                      confirmation returned

  Report module  Generate report for 1000 records  Returns report object,
                                                   size ≤ 10s
  ------------------------------------------------------------------------

### Integration testing verification criteria

  ------------------------------------------------------------------------
  **Integrated     **Test Case**                **Expected Outcome**
  Modules**                                     
  ---------------- ---------------------------- --------------------------
  Registration +   New user registers and logs  Login succeeds
  login            in immediately               post-registration

  Event creation + User RSVP to an event        RSVP linked to correct
  RSVP             created minutes earlier      event

  Budget           Submit budget, receive       Response = \"Proposal
  proposal +       acknowledgment from external Received\" in external
  finance system   API                          finance system

  Venue booking +  Book venue via UCMS, view    Booking marked "Reserved"
  venue system     confirmation in external     externally within 5 second
                   system                       

  Event report +   Submit report and generate   System summarizes and
  report generator monthly summary              includes the latest event
                                                reports
  ------------------------------------------------------------------------

### Functional testing verification criteria

  ---------------------------------------------------------------------------
  **Function   **Feature**    **Test Case**            **Expected Outcome**
  Code**                                               
  ------------ -------------- ------------------------ ----------------------
  F001         Login          Log in as a member with  Redirected to member
                              valid credentials        dashboard

  F002         Registration   Register with valid      Account created
                              student ID and MMU email successfully

  F003         Join Club      Join a club for student  Successfully join the
                              role                     available club

  F004         View Upcoming  Member views upcoming    List shows all
               Events         events                   upcoming events

  F005         RSVP for       RSVP to an event as a    RSVP recorded and
               Events         logged-in user           confirmation shown

  F006         Manage Club    Committee removes a      Member removed from
               Members        member from the club     list
                              list                     

  F007         Create Event   Committee submits event  Event proposal stored
               Proposal       title, date, objective   in system

  F008         Submit Budget  Submit budget request of Status shown as
               Proposal       RM500 for approval       \"Pending Approval\"

  F009         Submit Venue   Send venue request for   Venue status =
               Booking        May 30 in Lecture Hall A "Requested"
               Proposal                                

  F010         Cancel Event   Committee cancels an     Event marked as
                              event scheduled for next cancelled;
                              week                     participants notified

  F011         View RSVP for  Committee checks RSVP    List of attendees
               event          for an upcoming event    displayed

  F012         Submit Event   Submit post-event report Report stored and
               Report         including feedback       status = \"Submitted\"

  F013         Monitor Club   Admin views current      Dashboard shows
               and Event      event and activity logs  updated info
               Activity                                

  F014         Generate       Admin generates yearly   Downloaded PDF
               Reports        club activity report     includes summary for
                                                       the year
  ---------------------------------------------------------------------------

### User acceptance testing verification criteria

  -------------------------------------------------------------------------
  **User      **UAT Scenario**             **Acceptance Criteria**
  Role**                                   
  ----------- ---------------------------- --------------------------------
  Club Member Login, RSVP for event, view  All actions complete without
              upcoming events              errors, easy to navigate

  Club        Register, create event,      Workflow can be completed in
  Committee   submit budget and venue      under 10 minutes; responses
              request, submit report       within SLA

  Admin       Monitor club activity,       Data accurate, reports correctly
              generate reports, cancel an  generated
              event                        

  All Users   Use system for 30 minutes    ≥90% users rate usability ≥4/5
              and rate usability           
  -------------------------------------------------------------------------

### Performance verification criteria

  -----------------------------------------------------------------------------------
  **Requirement   **Description**          **Verification Criteria**   **Priority**
  ID**                                                                 
  --------------- ------------------------ --------------------------- --------------
  REQ_P001        Load dashboard within 3  90% of test users must      High
                  seconds for 90% of users experience ≤3s dashboard    
                                           loading time.               

  REQ_P002        Process RSVP submissions RSVP action must be         High
                  within 2 seconds during  confirmed in ≤2s with 100   
                  peak usage               concurrent users.           

  REQ_P003        Submit budget proposal   Budget system responds to   Medium
                  and receive response in  proposal submission within  
                  ≤5 seconds               5 seconds.                  

  REQ_P004        Venue booking            Venue booking request is    Medium
                  synchronizes with        acknowledged by external    
                  external system in ≤5    system within 5 seconds.    
                  seconds                                              

  REQ_P005        Generate reports for up  Report generation for 1000  Low
                  to 1000 records in ≤10   records must not exceed 10  
                  seconds                  seconds.                    
  -----------------------------------------------------------------------------------

### Usability verification criteria

  ---------------------------------------------------------------------------------
  **Requirement   **Description**          **Verification Criteria** **Priority**
  ID**                                                               
  --------------- ------------------------ ------------------------- --------------
  REQ_U001        Complete                 Test users must           High
                  registration/login in ≤3 register/login with ≤3    
                  clicks from homepage     clicks from homepage.     

  REQ_U002        Submit event proposal in Committee users should    High
                  ≤3 minutes (average)     complete event proposal   
                                           form within 3 minutes.    

  REQ_U003        RSVP submission requires Test members must         Medium
                  ≤5 clicks                complete RSVP in ≤5       
                                           clicks.                   

  REQ_U004        90% of users rate ease   Survey results show 90%   High
                  of use ≥4/5 in           of users give ≥4/5 for    
                  post-training survey     usability.                
  ---------------------------------------------------------------------------------

# Appendices

##  Assumptions and Dependencies

> This section outlines all necessary conditions assumed to be true
> during the design and development of the Student Club Management
> System (CMS), as well as the technical, organizational, and
> environmental dependencies the system relies on. These factors are
> critical to ensure the CMS functions as intended and meets user
> expectations.\
> \
> A.1 Assumptions

1.  **User Authentication and Access**

<!-- -->

A)  All end-users (students, committee members, admins, staff) possess
    valid and active university-issued credentials for access via the
    university\'s Single Sign-On (SSO) system.

B)  Role-based access rights (student, committee, admin, finance staff,
    venue staff) are properly pre-assigned by the university\'s identity
    management system.

C)  University staff are responsible for managing and updating user
    roles and permissions within the authentication system.

<!-- -->

2.  **Network and Accessibility**

<!-- -->

A)  All users have regular access to the internet and modern web
    browsers (latest 2 versions of Chrome, Firefox, Safari, or Edge).

B)  The system will be hosted on a cloud-based infrastructure or a
    university-provided virtual machine with guaranteed uptime of at
    least 99.5%.

C)  Users will interact with the system via web-based interfaces; mobile
    responsiveness is expected but no native mobile app will be provided
    during the initial release.

<!-- -->

3.  **System Environment and Compatibility**

<!-- -->

A)  All external APIs (financial system, venue booking system,
    authentication system) are compatible with RESTful communication and
    return predictable, validated JSON responses.

B)  External systems (finance, venue, university SSO) remain stable,
    maintained, and accessible throughout the lifecycle of CMS.

C)  External system outages are rare and will be handled through
    fallback mechanisms or error messages.

<!-- -->

4.  **Operational and Policy Assumptions**

<!-- -->

A)  University regulations on event proposal approval, budget limits,
    venue usage, and report submissions are clearly documented and will
    be provided to the development team.

B)  Each club has a designated advisor and at least one active committee
    member responsible for administrative actions (e.g., proposals,
    reports).

C)  All clubs are formally recognized by the university and must follow
    standardized procedures for funding and venue requests.

<!-- -->

5.  **Communication and Notification**

<!-- -->

A)  The university provides access to an SMTP-compatible email server
    for outbound communications (e.g., RSVP confirmations, budget/venue
    decisions, password recovery).

B)  Notifications and alerts are enabled for all major workflows: event
    creation, approval, budget response, venue response, RSVP
    confirmations, and report submissions.

<!-- -->

6.  **Data and Security Assumptions**

<!-- -->

A)  The university has an acceptable use policy and privacy guidelines
    governing the storage and access of student information.

B)  All data transmitted between CMS and external/internal systems will
    use TLS 1.3 encryption.

C)  User data at rest (within the database) will be encrypted using
    industry standards (e.g., AES-256).

<!-- -->

7.  **Development and Testing Environment**

<!-- -->

A)  The development team will have sandbox access to test instances of
    the financial and venue systems.

B)  Testing teams (QA, committee volunteers) are available for User
    Acceptance Testing (UAT) before system deployment.

C)  The university will provide or approve test accounts representing
    all user roles for end-to-end testing.

<!-- -->

8.  **Backup and Recovery**

<!-- -->

A)  Scheduled backups (full and incremental) are implemented and managed
    by the hosting provider or university IT.

B)  System recovery plans are validated at least quarterly and include
    procedures for data restoration in under 2 hours.

<!-- -->

9.  **Localization and Branding**

<!-- -->

A)  All interface text will be delivered in English (default) unless
    requested otherwise.

B)  University branding (logos, colours, font styles) will be provided
    to maintain consistent UI design.

> A. **[Dependencies]{.underline}**

1.  **University Authentication System**

- Type: OAuth2-based Single Sign-On (SSO)

- Role: Secure user login and access control

- Dependency: CMS depends on this system to validate users and assign
  permissions; any downtime in SSO affects all user access.

2.  **Financial Management System**

- Type: REST API-based budget processing tool

- Role: Receive and respond to club budget proposals

- Dependency: Budget submission workflow in CMS relies on this system
  for real-time approval/rejection and tracking.

3.  **Venue Booking System**

- Type: REST API integration

- Role: Submit venue reservation requests, receive confirmation or
  rejection

- Dependency: CMS depends on this system to process and reflect accurate
  venue availability; outdated or unavailable venue data can result in
  double bookings or failed reservations.

4.  **University Email Server (SMTP)**

- Type: SMTP server (e.g., smtp.student.mmu.edu.my)

- Role: Send all automated emails (event updates, proposal status,
  confirmation)

- Dependency: Without this, users will not receive system-generated
  notifications, alerts, or confirmation emails.

5.  **PostgreSQL Database**

- Type: Relational Database

- Role: Store all persistent data (users, clubs, events, proposals,
  reports)

- Dependency: All system modules depend on this database; failure or
  misconfiguration will halt CMS operations.

6.  **Node.js Runtime**

- Type: Server-side JavaScript execution engine

- Role: Executes backend logic and API endpoints

- Dependency: CMS relies on Node.js to process data, communicate with
  other systems, and execute business logic.

7.  **University Governance Policies**

- Type: Organizational/Regulatory

- Role: Define data handling, user access, event regulations

- Dependency: CMS workflows (e.g., proposal approvals, event limits)
  must align with university rules; policy changes can affect functional
  logic.

8.  Deployment Infrastructure

- Type: Cloud platform or university VM hosting

- Role: Host and run CMS with required resources (CPU, RAM, storage)

- Dependency: Hosting platform must support TLS, scheduled tasks (cron
  jobs), API gateway routing, and sufficient performance.

9.  Browser Standards

- Type: Client-Side Software

- Role: Interface through which users access CMS

- Dependency: CMS assumes compliance with ECMAScript and HTML5
  standards; unsupported browsers may cause UI/UX issues.

10. Stakeholder Availability

- Type: Organizational

- Role: Provide input, feedback, UAT participation

- Dependency: Without active participation from students, committees,
  and staff, requirements validation and usability testing are at risk.

> **[B. Acronyms and Abbreviations (Exhaustive List)]{.underline}**

+------------------+---------------------------------------------------+
| > Acronym /      | > Full Form / Description                         |
| > Abbreviation   |                                                   |
+==================+===================================================+
| > CMS            | > Club Management System                          |
+------------------+---------------------------------------------------+
| > UI             | > User Interface                                  |
+------------------+---------------------------------------------------+
| > UX             | > User Experience                                 |
+------------------+---------------------------------------------------+
| > SSO            | > Single Sign-On                                  |
+------------------+---------------------------------------------------+
| > API            | > Application Programming Interface               |
+------------------+---------------------------------------------------+
| > HTTPS          | > Hypertext Transfer Protocol Secure              |
+------------------+---------------------------------------------------+
| > TLS            | > Transport Layer Security                        |
+------------------+---------------------------------------------------+
| > OAuth2         | > Open Authorization 2.0 (authentication          |
|                  | > protocol)                                       |
+------------------+---------------------------------------------------+
| > SMTP           | > Simple Mail Transfer Protocol                   |
+------------------+---------------------------------------------------+
| > REST           | > Representational State Transfer (web service    |
|                  | > style)                                          |
+------------------+---------------------------------------------------+
| > JSON           | > JavaScript Object Notation                      |
+------------------+---------------------------------------------------+
| > SQL            | > Structured Query Language                       |
+------------------+---------------------------------------------------+
| > DB             | > Database                                        |
+------------------+---------------------------------------------------+
| > RAM            | > Random Access Memory                            |
+------------------+---------------------------------------------------+
| > VM             | > Virtual Machine                                 |
+------------------+---------------------------------------------------+
| > QA             | > Quality Assurance                               |
+------------------+---------------------------------------------------+
| > UAT            | > User Acceptance Testing                         |
+------------------+---------------------------------------------------+
| > FERPA          | > Family Educational Rights and Privacy Act (or   |
|                  | > equivalent local privacy legislation)           |
+------------------+---------------------------------------------------+
| > GDPR           | > General Data Protection Regulation              |
+------------------+---------------------------------------------------+
| > REQ            | > Requirement (prefix used in ID numbers, e.g.,   |
|                  | > REQ_U001)                                       |
+------------------+---------------------------------------------------+
| > Fxxx           | > Function Code (e.g., F001: Login, F002:         |
|                  | > Register)                                       |
+------------------+---------------------------------------------------+
| > MMU            | > Multimedia University                           |
+------------------+---------------------------------------------------+
| > CRUD           | > Create, Read, Update, Delete (common database   |
|                  | > operations)                                     |
+------------------+---------------------------------------------------+
| > SRS            | > Software Requirements Specification             |
+------------------+---------------------------------------------------+
| > SRS ID         | > Unique identifier used to track requirement in  |
|                  | > SRS (e.g., REQ_P001)                            |
+------------------+---------------------------------------------------+
| > HTTPS          | > Hypertext Transfer Protocol Secure              |
+------------------+---------------------------------------------------+
| > AES-256        | > Advanced Encryption Standard -- 256-bit         |
|                  | > encryption                                      |
+------------------+---------------------------------------------------+
| > UX Survey      | > Usability Experience Survey                     |
+------------------+---------------------------------------------------+
| > UI/UX          | > Combined term for user interface and user       |
|                  | > experience                                      |
+------------------+---------------------------------------------------+
| > DevOps         | > Development and Operations (software delivery   |
|                  | > practice)                                       |
+------------------+---------------------------------------------------+
| > ESLint         | > JavaScript code quality tool (used in           |
|                  | > development, if applicable)                     |
+------------------+---------------------------------------------------+
| > SMTP           | > Simple Mail Transfer Protocol                   |
+------------------+---------------------------------------------------+
| > CRUD           | > Create, Read, Update, Delete (standard          |
|                  | > operations on data)                             |
+------------------+---------------------------------------------------+
| > OAuth          | > Open Authorization protocol used for secure     |
|                  | > token-based user authentication                 |
+------------------+---------------------------------------------------+
| > JWT            | > JSON Web Token (used for session management, if |
|                  | > applicable)                                     |
+------------------+---------------------------------------------------+
| > CI/CD          | > Continuous Integration / Continuous Deployment  |
+------------------+---------------------------------------------------+
| > MVC            | > Model-View-Controller (software design pattern) |
+------------------+---------------------------------------------------+
