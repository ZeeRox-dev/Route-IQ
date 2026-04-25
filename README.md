## 🚛 RouteIQ – Multi-Vehicle Fleet Optimizer

RouteIQ is an interactive fleet management and route optimization web application designed to intelligently assign delivery stops across multiple vehicles while balancing fuel efficiency, traffic conditions, and delivery priorities.

Built as a single-page HTML application, it combines mapping, clustering, and optimization logic into a visually rich dashboard.

# 🌟 Features: 
# 🚗 Multi-Vehicle Fleet Management
    - Add/remove delivery vehicles dynamically
    - Assign starting locations via map clicks
    - Track fuel levels, mileage, and performance
    
# 🗺️ Interactive Map System
    - Click anywhere to set vehicle depot locations
    - Visualize routes and delivery clusters
    - Embedded map interface using iframe
# 📦 Delivery Clustering
    - Predefined clusters:
        - Sion
        - Vile Parle
        - Mira Road
        - Other Stops
    - Intelligent grouping of delivery points using GeoJSON
# 🧠 Smart Route Optimization
    - Cluster-based route assignment
    - Priority-based delivery sequencing
    - Pareto optimization (time vs fuel efficiency)
# ⛽ Fuel Optimization System
    - Tracks fuel consumption per vehicle
    - Automatic cross-vehicle compensation:
    - If fuel < 30%, nearby vehicles take over deliveries
# 🚦 Traffic Simulation & Integration
    - Traffic modes:
        - Simulated Traffic
        - OSM Baseline
        - HERE Live Traffic (API-based)
    - Adjustable traffic intensity
# 📊 Dashboard Analytics
    - Total stops
    - Active vehicles
    - Estimated fuel usage
    - Fleet efficiency metrics
# 🛠 Debug Panel
    - Real-time system monitoring:
        - API calls
        - Vehicle count
        - Fuel usage
        - Traffic factors
# 🧱 Tech Stack
    - Frontend: HTML, CSS, JavaScript
    - Mapping: Embedded map (iframe-based)
    - Data: GeoJSON for delivery points
    - APIs (optional):
        - HERE Maps API (for live traffic)
