# **DeepVizor** - 

*A user-friendly Python tool for capturing and analyzing network packets with real-time visualization and filtering.*  Designed to enable users to capture network packets, examine detailed information, and visualize network traffic trends

## **Overview**

**DeepVizor** is a network packet analysis tool developed in Python 3, utilizing Scapy for packet capture and Tkinter for the graphical interface. This application supports network analysts in monitoring and analyzing packet information with features such as protocol filtering, detailed packet views, and traffic trend visualization.

## **Installation**

This application is compatible with major platforms. **Python 3.7.9** is recommended for best compatibility. Install all required libraries using `requirements.txt` or follow manual installation steps.

1. **Install Python**  
   Download the appropriate version of Python from the official Python website.

2. **Install Required Packages**  
   Use pip to install all dependencies listed in `requirements.txt`.

3. **Manual Installation (Optional)**  
   Install individual packages such as Scapy, Matplotlib, and Tkinter if needed.

## **How to Use DeepVizor**

1. **Launch the Application:**  
   Open DeepVizor to display available network interfaces.

2. **Select Network Interface:**  
   Choose an active network interface for packet capture.

3. **Set Packet Capture Count:**  
   After selecting an interface, enter the number of packets to capture. For large capture counts, there may be a slight delay as the data loads.

## **Features**

- **Filter Network Packets:** Filter packets by protocol, source, or destination for precise analysis.
- **Detailed Packet Information:** Double-click any packet to view in-depth details.
- **IPv6 Support:** Compatible with IPv6 packets.
- **Generate I/O Graphs:** Visualize traffic trends with I/O graphs.
- **Open PCAP/PCAPNG Files:** Analyze existing packet capture files.
- **Save Packet Data:** Save captured packets for future reference.
- **DNS Hostname Resolution:** Resolve DNS response packets to hostnames.
- **Protocol Support:** Supports protocols such as HTTP, TLSv1.2, SSDP, TCP, UDP, ARP, and more.

## **Feature Guide**

### Filtering Packets  
Select the **Filter** button, then choose a filtering option from Protocol, Source, or Destination. Enter the desired value, such as the protocol type (e.g., HTTP) or a specific IP address, to apply filtering.

### Detailed Packet Information  
Double-click any packet in the list to display its details in the top section of the window.

### Generating I/O Graphs  
Select **Statistics** from the menu, then choose **Generate I/O Graph** to visualize packet flow with options to zoom, pan, and save the graph.

### Opening PCAP Files  
Navigate to **File > Open** and choose a PCAP or PCAPNG file to analyze existing packet capture data.

### Saving Packets  
Use **File > Save As** to save the current session’s packet data to the default directory.

### DNS Hostname Resolution  
In the **View** menu, select **Resolve DNS Hostnames** to convert DNS responses to hostnames.

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## **Acknowledgements**

Built using:
- Scapy for packet capture
- Matplotlib for data visualization
- Tkinter for GUI
