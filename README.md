NAME: REONSLY K C 
COMPANY: CODTECH IT SOLUTIONS 
ID: CT08CS99 
DOMAIN: CYBER SECURITY & ETHICAL HACKING 
DURATION: 10TH MAY 2024 TO 10TH JUNE 2024 
MENTOR: SRAVANI GOUNI 

OVERVIEW OF PROJECT 

At its core, the script utilizes Python's built-in socket library, renowned for its networking capabilities. This library enables the script to establish connections with ports on a target system and ascertain their accessibility. The script employs a modular structure, encapsulating the scanning functionality within the scan_ports function. This function iterates through a range of ports provided by the user, attempting to connect to each port in turn.

Upon connection attempt, the script evaluates the resulting status code, interpreting a 0 as indicative of an open port, while non-zero codes signify closed ports. Subsequently, the script communicates the status of each port to the user, displaying whether it's open or closed. The main function orchestrates the entire process, soliciting user input for the target IP address or domain name, as well as the port range to be scanned.

By design, this script furnishes a fundamental yet valuable utility in the realm of network security. It empowers users with the capability to swiftly identify potentially vulnerable access points within their network infrastructure. Moreover, its simplicity and accessibility render it an excellent learning tool for individuals seeking to comprehend the underlying principles of network scanning and socket programming.

However, it's important to acknowledge the script's limitations. As it focuses solely on port scanning, it overlooks other critical aspects of vulnerability assessment, such as identifying outdated software versions or misconfigurations. To evolve into a comprehensive vulnerability scanning tool, it would necessitate integration with additional libraries and functionalities tailored to address a broader spectrum of security concerns. Nonetheless, as a foundational building block, this script lays a robust groundwork for further expansion and refinement in pursuit of enhanced security posture.
