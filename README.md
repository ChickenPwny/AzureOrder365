# AzureOrder365
A comprehensive web application for visualizing Azure security logs with real-time threat intelligence analysis and interactive mapping capabilities. Developed in collaboration with Polito Inc. - Full Service Cybersecurity Consulting Fi

## Azure Security Logs Map & Threat Intelligence Dashboard

A powerful web-based security visualization tool that transforms Azure security logs into an interactive geographic map with real-time threat intelligence analysis.

### 🚀 Features

**🗺️ Interactive Geographic Visualization**
- Real-time mapping of security events using MapLibre GL
- Color-coded risk markers (High/Medium/Low/Info/None)
- Dynamic connection lines showing relationships between security events
- Clickable IP address legend with filtering capabilities

**🛡️ Advanced Threat Intelligence**
- Multi-source threat intelligence integration (ThreatFox, AbuseIPDB, VirusTotal, MISP)
- Real-time reputation scoring and malware detection
- Automated risk assessment based on log patterns
- Threat intelligence dashboard with live statistics

**📊 Smart Data Processing**
- Supports JSON and CSV log file uploads
- Drag-and-drop file interface
- Automatic filtering for security-relevant events
- IP geolocation with fallback for private networks

**🔗 Connection Analysis**
- Visual relationship mapping between security events
- Multiple connection types (High-risk, Geographic, Event-type, Related)
- Interactive filtering by connection type
- Connection strength visualization through line thickness

**�� User Experience**
- Responsive design with modern UI
- Real-time status updates during processing
- Interactive popups with detailed event information
- Keyboard shortcuts (ESC to close modals)

### 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Mapping**: MapLibre GL (OpenStreetMap tiles)
- **Threat Intelligence**: Multiple REST APIs
- **File Processing**: Client-side JSON/CSV parsing
- **Styling**: Modern CSS with animations and transitions

### 🎯 Use Cases

- **Security Operations Centers (SOC)**: Visualize security incidents geographically
- **Threat Hunting**: Identify patterns and relationships in security logs
- **Incident Response**: Quickly assess the scope and impact of security events
- **Compliance Reporting**: Generate visual reports for security assessments
- **Security Training**: Interactive learning tool for security professionals

### 🚀 Quick Start

1. Open `test-simple.html` in a modern web browser
2. Upload your Azure security logs (JSON or CSV format)
3. Watch as the system automatically:
   - Extracts IP addresses from logs
   - Performs threat intelligence analysis
   - Generates an interactive map
   - Creates connection relationships
4. Use the interactive controls to filter and explore the data

### 📋 Supported Log Formats

- **Azure Audit Logs**: Sign-in failures, admin activities
- **Azure Firewall Logs**: Denied connections, application rules
- **Threat Intelligence Logs**: Security alerts and detections
- **Custom Logs**: Any JSON/CSV with IP address fields

### �� Configuration

The tool includes configurable threat intelligence APIs:
- ThreatFox (free, no API key required)
- AbuseIPDB (requires API key)
- VirusTotal (requires API key)
- MISP feeds (public instances)

### 📈 Key Metrics

- **Real-time Processing**: Handles large log files efficiently
- **Threat Intelligence**: Queries multiple sources simultaneously
- **Visualization**: Supports up to 100 connection lines for optimal performance
- **Accuracy**: Advanced IP geolocation with private network detection

### 🎨 Interactive Features

- **IP Legend**: Click any IP to focus on that node and its connections
- **Connection Filtering**: Filter by relationship type (high-risk, geographic, etc.)
- **Threat Dashboard**: Live statistics on malicious, suspicious, and clean IPs
- **Popup Details**: Comprehensive event information with threat intelligence

### 🔒 Security Features

- Client-side processing (no data sent to external servers)
- Local threat intelligence caching
- Private IP address detection and handling
- Secure API key management for threat intelligence services
