# Elevator Algorithm Simulator Specification

## 1. System Overview

### 1.1 Core Features
- Interactive elevator system simulation
- Customizable building and elevator parameters
- Real-time visualization of elevator operations
- Custom algorithm creation and testing
- Performance analysis and comparison tools

### 1.2 System Requirements
- Web browser-based application
- Smooth animation support
- Minimum screen resolution: 1280x720
- Stable internet connection for online features

## 2. Simulation Parameters

### 2.1 Building Configuration
- Number of floors: 5-20
- Number of elevators: 1-4
- Floor height: Configurable
- Maximum passengers per floor: Configurable
- Building layout: Standard vertical arrangement

### 2.2 Elevator Properties
- Maximum weight capacity (kg)
- Maximum passenger count
- Movement speed (floors per second)
- Acceleration/deceleration rate
- Door operation timing
- Current status indicators
- Direction indicators

### 2.3 Passenger Properties
- Generation rate (passengers per minute)
- Weight range (minimum to maximum)
- Patience threshold
- Starting and destination floors
- Wait time tolerance
- Group size possibilities

## 3. Algorithm System

### 3.1 Algorithm Interface
- Event-based control system
- Real-time decision making
- Multiple algorithm support
- Custom algorithm creation
- Algorithm comparison capabilities

### 3.2 Built-in Algorithms
- First Come First Serve (FCFS)
- Nearest Car
- SCAN (Elevator Algorithm)
- LOOK Algorithm
- Custom algorithm support

### 3.3 Algorithm Components
Events:
- Passenger request received
- Elevator arrival at floor
- Passenger boarding/exit
- Emergency situations
- Capacity reached
- Door obstruction

Actions:
- Assign elevator to request
- Add floor to queue
- Queue request for later
- Load/unload passengers
- Change direction
- Emergency stop

Helper Functions:
- Find nearest elevator
- Check floor accessibility
- Calculate wait times
- Determine optimal routes
- Monitor load factors

## 4. User Interface

### 4.1 Main Display
- Building visualization
- Real-time elevator movement
- Passenger visualization
- Queue status indicators
- Floor status display
- Emergency indicators

### 4.2 Control System
- Simulation controls (start/pause/reset)
- Speed adjustment
- Parameter configuration
- Algorithm selection
- Emergency controls

### 4.3 Algorithm Development Interface
- Algorithm creation workspace
- Testing environment
- Performance monitoring
- Debug information
- Error detection

## 5. Performance Metrics

### 5.1 Real-time Metrics
- Average wait time
- Maximum wait time
- Total passengers served
- Energy consumption
- Elevator utilization rates
- Queue lengths per floor
- System efficiency score

### 5.2 Scoring System
Base Metrics:
- Passengers successfully served
- Average service time
- Energy efficiency

Penalties:
- Excessive wait times
- High energy usage
- Unbalanced elevator usage
- Passenger complaints

Bonuses:
- Efficient routing
- Quick response times
- Balanced load distribution
- Energy conservation

## 6. Data Management

### 6.1 Saved Information
- Building configurations
- Elevator settings
- Passenger parameters
- Custom algorithms
- Performance records
- High scores

### 6.2 Export Options
- Configuration profiles
- Algorithm scripts
- Performance reports
- Statistical analysis
- Comparative studies

## 7. Future Capabilities

### 7.1 Planned Features
- Multiple building layouts
- Special event scenarios
- Advanced passenger behaviors
- Multi-building systems
- Emergency protocols
- Weather impact simulation

### 7.2 Community Features
- Algorithm sharing
- Performance leaderboards
- Community challenges
- Collaborative development
- Educational resources 