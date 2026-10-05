
# Smart Fleet IoT Platform — Business Case

## 1. Business Context

The Smart Fleet IoT Platform was developed as part of a smart connectivity initiative to expand fleet operation management capabilities and provide connected vehicle services to customers.

The initiative was driven by the need to combine a newly developed **Vehicle Tracking System (ATS)** device with a digital fleet management platform. By collecting and validating vehicle data, the product aimed to provide customers with greater visibility into their vehicles while enabling more efficient fleet utilization, safer driving, and proactive vehicle maintenance.

The product was primarily designed to create additional value for fleet rental and corporate customers, while also supporting connected vehicle services for individual customers purchasing new vehicles.

The initiative was sponsored by the **Fleet Management department and R&D initiatives**.


## 2. Business Problem

Before the platform was introduced, important fleet information such as vehicle mileage and maintenance status was often collected through manual reporting.

Vehicle users or fleet customers would provide mileage information to fleet owners or administrative teams. Maintenance and service activities were then planned based on the reported mileage.

This created several business challenges:

- Limited real-time visibility into vehicle usage
- Reliance on manually reported mileage data
- Difficulty monitoring fleet utilization
- Limited visibility into driving behavior
- Reactive maintenance management
- Increased operational effort
- Limited ability to identify vehicle-related issues early

The business therefore needed a more reliable and scalable way to collect vehicle data and transform it into actionable fleet insights.


## 3. Product Opportunity

Connected vehicles create an opportunity to move fleet management from a primarily reactive and manually monitored process toward a **data-driven operating model**.

By installing an ATS device in vehicles, the platform can continuously collect telemetry and driving data and make relevant information available to fleet users.

The product opportunity was therefore to create a centralized platform that could:

1. Connect vehicles to a digital fleet ecosystem.
2. Provide real-time visibility into vehicle activity.
3. Improve fleet utilization through mileage and usage insights.
4. Support safer and more economical driving.
5. Enable more proactive maintenance management.
6. Reduce operational effort associated with manual vehicle monitoring.


## 4. Target Customers and Users

### Target Customers

**Fleet Rental & Corporate Customers**

Organizations managing multiple vehicles that require centralized visibility, utilization monitoring, maintenance planning, and operational reporting.

**Individual Vehicle Customers**

Customers purchasing new vehicles who can benefit from connected vehicle services and vehicle monitoring capabilities.

### Key Product Users

| User | Primary Need |
|---|---|
| Fleet Manager | Monitor and optimize fleet operations |
| Fleet Operations Specialist | Track vehicle activity and operational alerts |
| Technician | Install, activate, and validate ATS devices |
| Customer / Fleet Owner | Monitor vehicle usage and receive actionable information |


## 5. Product Vision

> **Transform connected vehicle data into actionable insights that enable safer, more efficient, and proactive fleet operations.**

The product moves beyond traditional vehicle tracking by combining connectivity, telemetry validation, driving analytics, vehicle information, and operational alerts in a centralized platform.


## 6. Proposed Product

The Smart Fleet IoT Platform connects vehicles equipped with ATS devices to a centralized cloud-based fleet management platform.

### High-Level Data Flow

```text
Vehicle
   ↓
ATS Device
   ↓
IoT Gateway
   ↓
Cloud
   ↓
Smart Fleet IoT Platform
   ↓
Fleet Users
```

Vehicle data is updated on the platform approximately every **15 seconds**, providing near real-time visibility into connected vehicles.

The platform also validates incoming data during the device installation process to ensure that GPS, mileage, sensor information, and other relevant telemetry are correctly received.


## 7. Key Product Capabilities

### Real-Time Fleet Monitoring

Fleet users can monitor connected vehicles and access their latest available location and vehicle information.

### Vehicle Utilization

Mileage and driving history provide visibility into how vehicles are being used across the fleet.

This supports more balanced fleet utilization and helps identify vehicles with significantly different usage levels.

### Driving Analytics

The platform provides driving behavior insights through indicators such as:

- Sudden braking
- Sudden acceleration
- Speed limit violations
- Sudden steering manuevers

These inputs contribute to the **Driver Score** and support safer and more economical driving.

### Vehicle Health & Maintenance

The platform can receive vehicle fault signals and display relevant alerts.

Mileage information can also support maintenance planning by providing visibility into current mileage and upcoming maintenance requirements.

### Alerts

When vehicle data is no longer received, an alert is generated and made available through the platform. Relevant Fleet Management specialists and technicians can also receive an email notification.

### Reporting

The platform provides fleet-related reporting capabilities to support operational decision-making.

---

## 8. Product Differentiation

The product was designed to provide value beyond basic GPS tracking.

Its differentiation comes from combining:

- Real-time vehicle visibility
- IoT telemetry validation
- Driver Score
- Eco-driving insights
- Vehicle health signals
- Maintenance alerts
- Fleet utilization insights

This creates a broader **connected fleet management experience** rather than a standalone vehicle tracking solution.


## 9. MVP Scope

The initial product focused on the core capabilities required to connect vehicles and provide meaningful fleet visibility.

### MVP Capabilities

- Vehicle registration
- ATS device installation
- Device validation
- GPS tracking
- Vehicle location history
- Mileage monitoring
- Vehicle health signals
- Alerts
- Reporting
- Maintenance information

The MVP established the foundation for expanding the product toward more advanced fleet intelligence capabilities.


## 10. Product Success Criteria

Product success was evaluated primarily through operational and data quality outcomes.

### Connectivity & Data

- Faster and more reliable device installation
- Correct data flow from vehicles to the platform
- Successful telemetry validation during installation

### Fleet Operations

- Improved visibility into vehicle usage
- Better fleet utilization
- More reliable mileage information
- Improved maintenance monitoring

### Customer Experience

- Earlier visibility of vehicle-related issues
- Automated maintenance and fault alerts
- Reduced dependence on manual reporting


## 11. Key Product Challenges

Several challenges required product and cross-functional decision-making during the project:

### IoT–Platform Integration

Ensuring reliable communication between the ATS device, IoT infrastructure, cloud environment, and platform.

### Data Quality

Vehicle data had to be validated to ensure that information displayed to users was reliable and actionable.

### MVP Definition

The product needed to balance the potential of connected vehicle technology with the capabilities required to deliver immediate customer value.

### Installation Operations

The device installation process required coordination between vehicle availability, parking locations, technical teams, device activation, and validation.

### Data Privacy

Vehicle and driving analytics were subject to KVKK requirements. Data flow therefore depended on completion of the relevant customer contract and privacy approvals.


## 12. Future Product Opportunities

The platform provides a foundation for extending fleet management toward more intelligent and predictive capabilities.

Potential future opportunities include:

- **AI-powered predictive maintenance**
- **AI-driven driving recommendations**
- **Fleet optimization recommendations**
- **EV charging optimization**
- **Predictive driver risk analysis**
- **Automated fleet reporting**

These capabilities could evolve the platform from a monitoring solution into a more proactive **fleet intelligence platform**.


## 13. My Product Management Contribution

As **Business Analyst & Product Owner**, my contribution covered the product lifecycle from understanding business needs to supporting delivery.

Key activities included:

- Requirement gathering
- Stakeholder workshops
- Business and process analysis
- Product backlog management
- User story definition
- Feature prioritization
- Sprint planning
- BPMN process modeling
- Collaboration with technical teams
- User Acceptance Testing (UAT)

**The role focused on translating business and customer needs into actionable product requirements while maintaining alignment between business stakeholders and the development team.**


