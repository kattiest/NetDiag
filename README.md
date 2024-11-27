# NetDiag
The Network Diagnostic Script is a comprehensive tool designed to diagnose and report common and advanced network issues. By combining basic connectivity tests with detailed analysis of network adapters, configurations, and performance, the script provides IT professionals and users with actionable insights into potential network problems.

Functionality:

    Network Adapter Status:
        Checks the status of all network adapters to ensure they are enabled and functioning.

    Ping Tests:
        Verifies connectivity to local (localhost), external (Google DNS), and internet (google.com) endpoints.

    DNS Resolution:
        Ensures domain names can be resolved to IP addresses using DNS.

    Traceroute:
        Analyzes the route and hops to an external server (Google DNS) to detect bottlenecks or unreachable nodes.

    Firewall Status:
        Displays the current status of the Windows Firewall for all profiles.

    Active Network Connections:
        Lists all active TCP/UDP connections and open ports to detect suspicious or unnecessary connections.

    IP Configuration:
        Displays detailed network configuration, including IP addresses, DNS servers, and gateway information.

    Wi-Fi Signal Strength:
        Retrieves detailed information about Wi-Fi signal quality and strength for systems connected to wireless networks.

    Event Log Analysis:
        Extracts network-related events from the Windows Event Log to highlight connection issues or errors.

    Speed Test (Optional):
        Uses PowerShell to test download and upload speeds (requires the Speedtest PowerShell module).

Key Sections:

    Adapter Status Check: Identifies disabled or malfunctioning network adapters.
    Connectivity Tests: Ensures the system can communicate with both local and internet hosts.
    DNS and Routing Analysis: Diagnoses potential DNS resolution or routing issues.
    Firewall Configuration: Verifies firewall rules and settings.
    Connection Inventory: Provides an overview of active network connections.
    Wi-Fi Diagnostics: Measures signal strength and connection quality for wireless adapters.
    Event Log Review: Extracts and analyzes logs for network-related warnings or errors.
    Speed Performance (Optional): Reports download and upload speed metrics.


    Suitable for diagnosing connectivity issues, network slowdowns, or Wi-Fi problems.
Helps determine if the issue lies with the system, network hardware, or external infrastructure.
