# JanPro Dispatch Optimization & Staffing System

Google Maps API-integrated workforce allocation and dispatch optimization system built using Excel and Power Query for multi-site commercial cleaning operations.

---

## Overview

This project was designed to improve operational staffing coordination across multiple janitorial contracts by automating:

- distance-based worker ranking
- dispatch sequencing
- backup staffing allocation
- staffing visibility
- duplicate assignment prevention
- operational dispatch workflow management

The system combines operational planning logic with Google Maps Distance Matrix API integration to support more efficient workforce allocation and reduced travel inefficiencies.

---

## Key Features

### Workforce Allocation
- Automatically ranks workers by proximity to contract locations
- Assigns primary and backup staffing order
- Supports multi-site staffing coordination

### Dispatch Optimization
- Generates operational call lists by client and day
- Prioritizes closest available workers
- Reduces manual dispatch decision-making

### Duplicate Assignment Prevention
- Prevents primary workers from being assigned multiple contracts on the same day
- Flags conflicts for manager review

### Google Maps API Integration
- Uses Google Maps Distance Matrix API to calculate worker-to-site commute distances
- Supports dynamic distance-based ranking logic

### Operational Dashboard
- Tracks staffing coverage
- Identifies open staffing gaps
- Improves dispatch visibility for managers

---

## System Workflow

```text
Employees + Availability
            ↓
Contract Requirements
            ↓
Google Maps API Distance Calculation
            ↓
DistanceMap Ranking Engine
            ↓
Optimized Dispatch Logic
            ↓
Manager Dashboard + Call Lists
```

---

## Tools Used

- Microsoft Excel
- Power Query
- Google Maps Distance Matrix API
- Operational Dispatch Logic
- Workforce Allocation Modeling

---

## Example Operational Use Case

1. Manager filters dispatch list by current day
2. System displays primary staffing assignments
3. Backup workers remain visible if callouts occur
4. Distance ranking prioritizes operational efficiency
5. Dashboard highlights staffing shortages or conflicts

---

## Project Structure

| Sheet | Purpose |
|---|---|
| Employees | Worker availability, pay, and location data |
| Contracts | Client staffing requirements and service schedules |
| DistanceMap | API-generated worker-to-site distance rankings |
| OptimizedCallList | Final dispatch order and backup assignments |
| Dashboard | Staffing visibility and operational summaries |

---

## Future Improvements

- Live automatic API refresh scheduling
- Route optimization logic
- Labor hour balancing
- Supply chain integration
- Mobile dispatch interface
- Power BI dashboard integration

---

## Resume Description

Built a Google Maps API-integrated dispatch and workforce allocation system using Excel and Power Query to improve staffing coordination, backup coverage, and scheduling efficiency across commercial cleaning contracts.

---

## Notes

This project was developed as an operational workflow and process improvement system modeled after real-world dispatch and workforce coordination practices used in service operations environments.
