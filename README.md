# Wireshark-for-Security-Detect-Network-Anomalies
## Objective

Learn to capture and analyze network traffic using Wireshark.
Gain hands-on experience with real-world traffic patterns.

### Skills Learned

- Navigate Wireshark's interface and key features.
- Perform network traffic captures.
- Filter and analyze captured data for anomalies.

### Tools Used
- Wireshark
- Xfce Ubuntu


## Steps
### Task 1
Exploring Wireshark's Interface
Navigate Wireshark's interface, including:
- Capture options.
- Protocol list.
- Live packet view.
Select the correct network interface for capturing traffic.
![Screenshot 2025-02-18 104825](https://github.com/user-attachments/assets/95fe8249-be00-4231-bf35-c12f1d212842)
![Screenshot 2025-02-18 105006](https://github.com/user-attachments/assets/5e7771b9-07a3-4618-b574-45748ffcf1d3)
### Key Takeaways
- Understand Tool Layouts: Familiarity with the interface of analysis tools like Wireshark is crucial for effective and efficient workflows.
- Adaptability: While tool interfaces may evolve over time, understanding the foundational structure makes adapting to updates easier.
- Efficient Navigation: Learning to organize your workspace and use shortcuts enhances productivity when analyzing large datasets.
### Task 2
Capturing and Saving Traffic
- Generate traffic using apps or websites.
- Monitor traffic focusing on key protocols (e.g., HTTP, TCP).
- Save captures in pcapng format for future analysis.
![Screenshot 2025-02-18 110344](https://github.com/user-attachments/assets/ff858ea7-4427-46b9-a960-8b72d4d230fb)
![Screenshot 2025-02-18 110153](https://github.com/user-attachments/assets/7add66f6-8857-441c-992e-543f243b004a)
![Screenshot 2025-02-18 110251](https://github.com/user-attachments/assets/2383dfda-28d4-462e-addb-b5d406442e3c)
### Key Takeaways
- Thorough Documentation: Always label and save captured data in organized formats to ensure easy retrieval for future analysis or compliance needs.
- Reproducibility: The ability to recreate captures and conditionsensures consistency in troubleshooting and threat analysis..
- Attention to Baselines: Capturing normal traffic patterns provides a foundation for detecting anomalies in the future.
### Task 3
Filtering Captured Data
- Load captured file
- Apply filters
- Refine filters to identify IOCs
- Save filtered view
![Screenshot 2025-02-18 112028](https://github.com/user-attachments/assets/4952e8fb-6490-4a48-af29-fa49429fecd6)
![Screenshot 2025-02-18 112044](https://github.com/user-attachments/assets/1f81498c-13a7-4a0d-9db6-5d7e47ed962d)
![Screenshot 2025-02-18 112216](https://github.com/user-attachments/assets/63b2ac0c-9d94-45fb-afb9-9424dcbb3075)
![Screenshot 2025-02-18 112306](https://github.com/user-attachments/assets/b7989d0e-c226-45e0-becd-0e2499fdc552)
![Screenshot 2025-02-18 112445](https://github.com/user-attachments/assets/69756149-035d-4ad5-8751-010baeeb4409)
![Screenshot 2025-02-18 113123](https://github.com/user-attachments/assets/476a5149-57b1-4d6d-a2e6-936cb1c5b029)
![Screenshot 2025-02-18 113140](https://github.com/user-attachments/assets/c7465b28-32f6-4556-ba5d-cdc06f87cd27)
![Screenshot 2025-02-18 113203](https://github.com/user-attachments/assets/ccb59c8c-3554-4e79-b48d-c493fd7e8652)
![Screenshot 2025-02-18 113445](https://github.com/user-attachments/assets/06073f9e-cce1-4f00-b8a3-a1c8dc8f9ff3)
![Screenshot 2025-02-18 113647](https://github.com/user-attachments/assets/c1e73813-40e4-42d3-8eac-54b8a768eed4)
![Screenshot 2025-02-18 111917](https://github.com/user-attachments/assets/fd7986b9-1fb3-422b-a8ca-d680e954bfb6)
### Key Takeaways
- Precision is Key: Effective filtering helps narrow down data to relevant insights, saving time during analysis.
- Layered Approaches: Combine simple and advanced filters to focus on the most critical data without losing broader context.
- Reusable Techniques: The logic behind filtering (e.g., by protocol or IP) applies universally across various network analysis scenarios.
***
![Screenshot 2025-02-18 114329](https://github.com/user-attachments/assets/571998bc-a079-41ce-9dff-c74a0bc1761b)
![Screenshot 2025-02-18 115702](https://github.com/user-attachments/assets/9d664e49-704c-4943-8ae2-f3c733d36dc6)
![Screenshot 2025-02-18 115745](https://github.com/user-attachments/assets/3748fff9-74c6-46a8-968c-e4b7dfd077ee)
![Screenshot 2025-02-18 115811](https://github.com/user-attachments/assets/d5f74ee4-1ee8-45e9-a4bb-7cd9f43add7b)
![Screenshot 2025-02-18 115859](https://github.com/user-attachments/assets/ac29aca9-14ab-47b0-8bd6-4ac237d33422)
### Key Takeaways
- Start Simple, Build Gradually: Begin with broad filters to
understand overall patterns, then refine your approach to isolate
critical data.
- Consistency is Key: Standardize your filtering and analysis
methods to ensure repeatable and reliable results.
- Stay Organized: Always save filtered results and annotate key
findings to maintain clarity during extended investigations.
### Task 4
Analyzing Traffic for Threats
- Detect common threats
- Document findings and propose
mitigation measures.
![Screenshot 2025-02-18 120554](https://github.com/user-attachments/assets/e580305c-1d3a-47c3-915b-b58025374187)
![Screenshot 2025-02-18 120710](https://github.com/user-attachments/assets/2c6bb1ad-84f0-4c51-891b-a3b59885c75b)
![Screenshot 2025-02-18 120813](https://github.com/user-attachments/assets/8fc06444-2a10-4220-a827-9152af2503bc)
![Screenshot 2025-02-18 121117](https://github.com/user-attachments/assets/32eac7d2-9efc-471e-802f-bed917cf927a)
### Key Takeaways
- Recognize Patterns: Familiarity with normal traffic patterns
enables faster detection of potential threats or anomalies.
- Context Matters: Malicious activity often mimics legitimate traffic-contextualizing behavior is essential for accurate threat
identification.
- Continuous Learning: Threat detection skills improve over time with exposure to new attack techniques and evolving protocols.
### Task 5
Practical Analysis
- TCP SYN Flood Attack
- Wireshark's Statistics Tools
- Recognizing Attack pattern
![Screenshot 2025-02-18 121549](https://github.com/user-attachments/assets/5498d470-ea92-4509-aa82-95bde64f0c84)
![Screenshot 2025-02-18 121759](https://github.com/user-attachments/assets/72381bdc-3c01-4e4c-8219-ccd7ff84657c)
![Screenshot 2025-02-18 121816](https://github.com/user-attachments/assets/05f70fba-1f46-4f39-b24f-92c9ec87ad80)
![Screenshot 2025-02-18 121914](https://github.com/user-attachments/assets/225b9a9d-f949-4693-83c1-e60d4dcfba89)
![Screenshot 2025-02-18 122033](https://github.com/user-attachments/assets/4110a014-240b-4ede-aec8-92701d015231)
### Mitigating the Attack
- Server Configuration
- Firewall and Intrusion Detection Systems (IDS)
- SYN Cookies
### Key Takeaways
- Holistic Traffic Analysis: Leveraging multiple Wireshark tools like IO Graphs, Conversations, and Endpoints helps uncover attack patterns and verify anomalies.
- Efficient Filtering Techniques: Precise filters like tcp.flags.syn == 1 && tcp.flags.ack=0 enable faster isolation of relevant packets, saving time during analysis.
- Actionable Insights: Knowing how to filter and interpret SYN Flood traffic empowers users to identify and mitigate such attacks effectively.
  ***
  ### Commulative activity
  ![image](https://github.com/user-attachments/assets/5e39a538-796c-4b55-8339-0fe3d5196ebc)
tcp.flags.syn == 1 && tcp.flags.ack == 0
tcp.len < 60
[Wireshark-Cheat-Sheet.pdf](https://github.com/user-attachments/files/18850335/Wireshark-Cheat-Sheet.pdf)
![Screenshot 2025-02-18 123344](https://github.com/user-attachments/assets/79c382ce-977d-436a-8a04-094a3b591bf2)
![Screenshot 2025-02-18 123440](https://github.com/user-attachments/assets/c6bef4c7-fc83-49b8-a32e-079f28c48d58)
![Screenshot 2025-02-18 123632](https://github.com/user-attachments/assets/2f088c0a-9274-47d2-84e5-140476c20f42)
![Screenshot 2025-02-18 123841](https://github.com/user-attachments/assets/992efdff-ff9c-4d8a-bc5a-c15a350f0cc7)
![Screenshot 2025-02-18 124118](https://github.com/user-attachments/assets/c00e27cd-5f20-4b44-8cc4-235b57d82ec6)
![Screenshot 2025-02-18 125022](https://github.com/user-attachments/assets/3d69e029-af6e-4703-b5ed-f8948fc97ff3)
The traffic to port 4444 is suspicious and often linked to malware. Here’s what to do:

- Check the Device: Find out which device (192.168.1.56) is trying to connect to port 4444. Scan it for malware.

- Block the Port: Use your firewall to block traffic to port 4444 unless it’s needed.

- Update Systems: Make sure all devices and software are up to date to fix security holes.

- Monitor Network: Use security tools to watch for unusual activity.

- Educate Users: Teach users to avoid risky actions like clicking on suspicious links.
