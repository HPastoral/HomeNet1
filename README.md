# Home Network Topology 
Introduction:

In today's interconnected world, home networks play a crucial role in our daily lives. However, many home networks are vulnerable to various security risks due to their default configurations and lack of robust security measures. This introduction will outline the topology of a typical unsecure home network, comprising only a modem from the Internet Service Provider (ISP) and a wireless router. Furthermore, it will introduce a project aimed at enhancing the network's security by implementing a suite of free open-sourced tools and technologies, including pfSense firewall, Suricata, OpenVPN, Zeek, and a Wazuh SIEM server.

# Unsecure Home Network Topology:

![Snag_b6c33b](https://github.com/HPastoral/HomeNet1/assets/135756003/64041d66-13f3-4000-91ef-a0337aa6e8fd)

A common home network setup typically involves an ISP-provided modem that connects to the internet and a wireless router that enables multiple devices to connect wirelessly. In this basic configuration, the modem acts as a gateway, establishing the connection between the home network and the ISP's network, while the wireless router handles internal network traffic and provides Wi-Fi access to devices.

However, this simple network topology leaves the home network vulnerable to various security threats. Without additional security measures, unauthorized access, malicious activities, and potential data breaches become significant concerns. Therefore, it becomes essential to fortify the network's defenses and establish robust security protocols.

# Securing the Home Network with Open-source Security (Meaning Free):


![Snag_b77b21](https://github.com/HPastoral/HomeNet1/assets/135756003/b9466720-82b5-4b03-abc3-3047f28bc185)


To address the security challenges of the home network, a comprehensive project is proposed. The project involves implementing several key security tools and technologies to enhance network protection and monitoring capabilities.

pfSense Firewall: A robust and feature-rich firewall solution, pfSense, will be deployed to create a secure perimeter around the home network. pfSense provides advanced firewall rules, network address translation (NAT), and port forwarding capabilities, allowing fine-grained control over inbound and outbound network traffic.

Suricata: An open-source network intrusion detection and prevention system (IDS/IPS), Suricata will be integrated into the network. Suricata will monitor network traffic in real-time, detecting and alerting on suspicious or malicious activities, such as malware infections, exploits, and intrusion attempts.

OpenVPN: To establish secure remote access to the home network, OpenVPN, an open-source virtual private network (VPN) solution, will be implemented. OpenVPN ensures encrypted communication between remote devices and the home network, protecting sensitive data and preventing eavesdropping.

Zeek: Formerly known as Bro, Zeek is an open-source network security monitoring tool. Zeek will be utilized to passively monitor network traffic, capturing packets, and generating high-level logs for network analysis, threat detection, and incident response.

Wazuh Server: A Wazuh server will be deployed to provide centralized security monitoring and log management. Wazuh offers real-time threat detection, log analysis, and response capabilities, enabling the network administrator to monitor the overall security posture of the home network effectively.

By implementing this comprehensive suite of security tools and technologies, the home network will be fortified against a wide range of security threats. The project aims to create a secure and robust network environment, ensuring the privacy, integrity, and confidentiality of the network's data and devices.

