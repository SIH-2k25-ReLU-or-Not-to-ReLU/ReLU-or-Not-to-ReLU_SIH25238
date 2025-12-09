# InsightGuard - Complete Folder Structure Overview

**APT_RULES_ELK/** - Pre-built ELK detection rules organized by MITRE ATT&CK tactics (reconnaissance, initial access, persistence, privilege escalation, defense evasion, exfiltration) with action connectors for automated response.

**Attack_Scripts/** - APT simulation scripts covering the full kill chain from reconnaissance to exfiltration, including setup utilities, individual attack modules, and complete attack chain execution.

**Documentation/** - Project documentation, research papers, and reference materials related to APT detection and ELK Stack implementation.

**ELK-Results/** - Contains test results, dashboards, and detection outputs from running the attack scenarios against the ELK infrastructure.

**Implementation_Manual/** - Step-by-step deployment guide with ELK server setup, network monitoring configuration, attack scenario walkthroughs mapped to MITRE ATT&CK framework stages.

**Machine-Learning/** - ML-driven anomaly detection module featuring DRL agents, synthetic data generation, C2 traffic detection using FFT analysis, and behavioral threat identification.

**Test-Exploitation/** - Proof-of-concept exfiltration tools testing DNS tunneling and HTTP-based data exfiltration methods to validate detection rule effectiveness.