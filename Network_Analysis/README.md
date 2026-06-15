# Network Analysis for Emergency Response Using ArcGIS Pro

## Project Overview

This project demonstrates the use of ArcGIS Pro Network Analyst to support emergency response planning and routing analysis.

The project focuses on:

- Building a network dataset
- Determining the shortest route between locations
- Evaluating route changes caused by barriers
- Identifying the closest emergency facility to an incident
- Identifying multiple closest facilities for emergency response planning

These analyses are commonly used in emergency management, public safety, transportation planning, utility operations, and logistics.

---

## Objectives

The objectives of this project were to:

1. Build and configure a transportation network dataset.
2. Perform shortest path routing analysis.
3. Evaluate the impact of barriers on route selection.
4. Identify the closest emergency facility to an incident location.
5. Determine multiple closest facilities for improved emergency response planning.

---

## Software Used

- ArcGIS Pro
- ArcGIS Network Analyst Extension

---

## Data Used

- Road Network
- Emergency Facility Locations
- Incident Locations
- Network Dataset

---

## Methodology

### 1. Network Dataset Creation

A transportation network dataset was created using the road network.

The network dataset was configured with impedance attributes representing:

- Distance (Miles)
- Travel Time (Minutes)

The impedance attribute allows the network solver to identify the most efficient routes.

### Network Dataset

![Network Dataset](images/01_network_dataset_setup.png)

---

### 2. Shortest Route Analysis

A route analysis layer was created to identify the shortest path between selected locations.

The analysis used the route solver to determine the optimal path based on the selected impedance attribute.

![Shortest Route](images/02_shortest_route_analysis.png)

#### Results

- Successfully identified the optimal route.
- Demonstrated how impedance values influence route selection.
- Route optimization can be based on distance or travel time.

---

### 3. Route Analysis with Barrier

A barrier was introduced into the network to simulate a road closure or obstruction.

The route was recalculated to identify an alternative path around the barrier.

![Barrier Analysis](images/03_route_with_barrier.png)

#### Results

- Network solver successfully avoided blocked segments.
- Alternative routes were generated automatically.
- Demonstrated real-world emergency response and transportation planning scenarios.

---

### 4. Single Closest Facility Analysis

A Closest Facility analysis was performed to identify the nearest emergency facility to a fire incident.

![Single Closest Facility](images/04_single_closest_facility.png)

#### Results

- Identified the nearest available facility.
- Calculated optimal travel routes.
- Demonstrated emergency dispatch applications.

---

### 5. Multiple Closest Facilities Analysis

A Closest Facility analysis was expanded to evaluate multiple facilities serving multiple incidents.

![Multiple Closest Facilities](images/05_multiple_closest_facilities.png)

#### Results

- Determined the most efficient facility assignments.
- Improved emergency response coverage.
- Demonstrated network-based resource allocation.

---

## Applications

This workflow can be applied to:

- Fire station dispatch
- Emergency medical response
- Police response planning
- Utility service routing
- Transportation planning
- Logistics and delivery optimization

---

## Skills Demonstrated

- ArcGIS Pro
- ArcGIS Network Analyst
- Network Dataset Creation
- Route Analysis
- Closest Facility Analysis
- Barrier Analysis
- Spatial Decision Support
- Emergency Response Planning
- GIS Cartography

---

## Key Takeaways

This project demonstrates how GIS network analysis can be used to support emergency response planning by identifying efficient routes, evaluating network disruptions, and assigning the most appropriate facilities to incidents. Network Analyst provides powerful tools for improving operational efficiency and supporting data-driven decision making.
