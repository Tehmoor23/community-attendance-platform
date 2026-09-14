```markdown
# Community Attendance & Analytics Platform

> **Project showcase:** The source code is maintained privately because the application supports real community operations and processes attendance-related information. This repository contains project documentation and anonymized screenshots only.

A role-based web and Android platform for managing attendance across prayers, community programs, and events at multiple locations.

The application was designed and developed as an independent volunteer software project using React Native, Expo, JavaScript, Firebase, and Firestore.

## Project Overview

The platform replaces fragmented manual attendance processes with a unified digital system. It supports different operational environments, including individual registration, tablet-based data entry, QR-assisted attendance, terminal operation, program administration, and unattended kiosk use.

Locations, organizational groups, permissions, event types, and application modes can be configured independently. Each interface provides only the functionality required for its specific workflow while using the same underlying cloud-based data structure.

## Key Features

| Area | Capabilities |
|---|---|
| Attendance management | Records attendance for prayers, community programs, and other events |
| Multiple capture modes | Manual registration, QR workflows, tablet operation, terminals, and cloud-synchronized entry |
| Role-based access | Separate permissions and interfaces for administrators, local operators, and restricted users |
| Multi-location support | Independent configuration and evaluation of multiple community locations |
| Program management | Creation, selection, administration, and evaluation of individual programs and events |
| Analytics | Weekly totals, group distributions, location comparisons, charts, and summary metrics |
| Filtering | Evaluation by time period, location, program, organizational group, and attendance type |
| Data export | Structured exports for further processing and reporting |
| Responsive interfaces | Optimized layouts for desktop, tablet, Android, and kiosk environments |
| Cloud integration | Centralized data storage and synchronization using Firebase and Firestore |

## Selected Screenshots

The following screenshots provide a selected glimpse into the platform rather than a complete product tour.

The full application contains additional administrative, configuration, filtering, user-management, master-data, export, and role-specific operational workflows that are intentionally not shown publicly. This protects internal processes while keeping the showcase focused on the most relevant functionality.

All displayed locations, identifiers, and statistics have been anonymized or replaced with synthetic demonstration data. The QR code shown was temporary and is no longer active.

### Attendance Entry

The attendance interface is designed for fast operation on tablets, terminals, and larger displays. It presents the currently active prayer and allows users to continue through a group-specific registration workflow.

![Manual attendance entry](assets/01-attendance-entry.png)

### QR-Based Attendance

The platform can generate temporary QR codes for attendance registration. A manual ID search remains available as an alternative workflow when QR registration is not suitable.

![QR-based attendance](assets/02-qr-attendance.png)

### Attendance Analytics Overview

Administrators can review aggregated attendance figures for a selected calendar week and location. The overview provides a concise breakdown by organizational group while keeping the underlying records centralized.

![Attendance analytics overview](assets/03-attendance-analytics-overview.png)

### Attendance Distribution and Summary Metrics

Detailed analytics visualize attendance across individual prayers. Additional metrics identify averages, highest and lowest attendance values, and changes within the selected evaluation period.

![Attendance analytics chart](assets/04-attendance-analytics-chart.png)

### Program Analytics

Programs and community events can be evaluated independently from regular prayer attendance. Administrators can select an event, review its total attendance, apply filters, and export the corresponding records.

![Program analytics overview](assets/05-program-analytics-overview.png)

### Group and Location Breakdown

The detailed program view compares attendance across organizational groups and participating locations. It combines absolute values, reference totals, percentages, and visual progress indicators in one interface.

![Program location breakdown](assets/06-program-location-breakdown.png)

## Technical Overview

| Category | Technologies and Concepts |
|---|---|
| Application | React Native, Expo, JavaScript |
| Platforms | Web and Android |
| Backend | Firebase and Firestore |
| Data model | Shared cloud-based data structure for locations, users, attendance records, prayers, and programs |
| Access control | Role-based permissions and application modes |
| Interfaces | Responsive desktop, tablet, mobile, terminal, and kiosk layouts |
| Development | Requirements analysis, implementation, testing, debugging, refactoring, and deployment |
| Workflow | Git and GitHub for version control and iterative development |

## Architecture and Design Considerations

The application was designed around a shared data model that supports several operational contexts without requiring separate systems for each location or workflow.

Key engineering considerations included:

- Reducing unnecessary Firestore reads while maintaining current information
- Keeping role-specific interfaces simple and focused
- Supporting multiple locations and organizational structures
- Maintaining consistent behavior across web, Android, tablet, and kiosk layouts
- Separating prayer attendance from independent program and event workflows
- Providing meaningful analytics without exposing individual personal information
- Handling configuration, filtering, statistics, and exports through a unified system

## My Contribution

I independently designed and developed the platform as a volunteer software project.

My responsibilities included:

- Translating real operational requirements into technical workflows
- Designing the application structure and user interfaces
- Implementing the web and Android application
- Creating the Firestore data model and cloud integration
- Developing role-based access and administrative functionality
- Implementing QR, tablet, terminal, and manual attendance workflows
- Building statistics, filters, dashboards, and export functionality
- Testing, debugging, refactoring, and deploying the application
- Iteratively improving the system based on practical use and feedback

## Privacy and Source Availability

The production source code is intentionally not included in this public repository.

The application supports real organizational processes and may interact with confidential attendance and configuration data. Publishing the complete source could expose internal workflows, data structures, deployment details, or security-relevant implementation information.

This showcase therefore contains:

- An overview of the project and its functionality
- Anonymized screenshots
- Synthetic demonstration values
- A summary of the technologies and engineering decisions

It does not contain:

- Production source code
- Personal attendance records
- Active QR credentials
- API keys or environment variables
- Firebase configuration
- Internal access information

Further technical details can be discussed upon request without disclosing confidential data or production credentials.

## Project Status

The platform is under active development and supports practical community attendance and program-management workflows. Features are continuously tested, refined, and extended based on operational requirements.


## Contact

For questions about the project or working student opportunities, feel free to contact me:

[LinkedIn](https://www.linkedin.com/in/tehmoor-bhatti) · [Email](mailto:tehmoor.bhatti@stud.fra-uas.de)
```
