
Networking ProjectNetworking Project
Oct 2024 - Oct 2024Oct 2024 - Oct 2024

        **Project Overview**:
        The goal was to establish a robust network architecture divided into three VLANs: Employees, Finance, and Guests, ensuring secure communication between them.

        **Network Design**:

        Components:

        - Switch 0 (Main Switch): The central switch connecting to the router and other switches via trunk ports.
        - Switch 1 (VLAN 10 - Employees): Houses four PCs, enabling internal communication within the employee VLAN.
        - Switch 2 (VLAN 20 - Finance): Contains one PC for finance operations, isolated for security.
         Wireless Access Point (WAP): Provides guest access through VLAN 30, ensuring separation from internal VLANs.
        - Router: Facilitates inter-VLAN communication via subinterfaces, allowing different VLANs to connect while maintaining security.

        VLAN Assignments:

         VLAN 10: Employees (4 PCs on Switch 1)
         VLAN 20: Finance (1 PC on Switch 2)
         VLAN 30: Guests (Wireless access via WAP)

        Trunking:
        Trunk ports are configured between switches and the router, using 802.1Q encapsulation to carry multiple VLANs over the same link.

        **Key Configurations**:
        - VLANs created for Employees (VLAN 10), Finance (VLAN 20), and Guests (VLAN 30).
        - Inter-VLAN routing configured on a Cisco router for seamless communication.

  
        **Challenges**:
        Faced issues with inter-VLAN communication initially, resolved by adjusting trunk configurations and ensuring correct VLAN assignments.

        **Results**:
        Successfully achieved inter-VLAN communication with testing conducted, ensuring a secure and efficient network.

        **Tools Used**: Cisco Packet Tracer **Project Overview**: The goal was to establish a robust network architecture divided into three VLANs: Employees, Finance, and Guests, ensuring secure communication between them.  **Network Design**: Components: - Switch 0 (Main Switch): The central switch connecting to the router and other switches via trunk ports. - Switch 1 (VLAN 10 - Employees): Houses four PCs, enabling internal communication within the employee VLAN. - Switch 2 (VLAN 20 - Finance): Contains one PC for finance operations, isolated for security. Wireless Access Point (WAP): Provides guest access through VLAN 30, ensuring separation from internal VLANs. - Router: Facilitates inter-VLAN communication via subinterfaces, allowing different VLANs to connect while maintaining security. VLAN Assignments: VLAN 10: Employees (4 PCs on Switch 1) VLAN 20: Finance (1 PC on Switch 2) VLAN 30: Guests (Wireless access via WAP) Trunking: Trunk ports are configured between switches and the router, using 802.1Q encapsulation to carry multiple VLANs over the same link.  **Key Configurations**: - VLANs created for Employees (VLAN 10), Finance (VLAN 20), and Guests (VLAN 30). - Inter-VLAN routing configured on a Cisco router for seamless communication.  **Challenges**: Faced issues with inter-VLAN communication initially, resolved by adjusting trunk configurations and ensuring correct VLAN assignments.  **Results**: Successfully achieved inter-VLAN communication with testing conducted, ensuring a secure and efficient network. **Tools Used**: Cisco Packet Tracer
        Skills: VLAN · networking · Network Design · LAN Switching · Cisco Networking
