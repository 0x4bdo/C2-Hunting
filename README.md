# C2-Hunting-Resources

**C2-Hunting-Resources** is a repository for Command & Control (C2) infrastructure hunting and threat intelligence research.  
It provides practical resources for detecting and tracking malicious servers and panels using **urlscan.io queries**, **SHA256-based hunting**, and **favicon hash fingerprints**.

---

## Repository Structure

```

C2-Hunting-Resources/
│
├── URLScan/
│   ├── URLScan_C2_Queries.md
│   ├── C2-Hunting-SHA256-URLSCAN.md
│
├── Favicon-Hashes/
│   └── C2-Panel-Favicon-Hashes.md

```

- **URLScan/**: Contains pre-built queries and SHA256-based hunting techniques for detecting potential C2 activity using urlscan.io.  
- **Favicon-Hashes/**: Contains favicon hash mappings to identify C2 panels across different malware families.

---

## Usage

1. Browse the markdown files to understand the queries and hashes.  
2. Apply the urlscan.io queries to investigate suspicious URLs.  
3. Use the SHA256 hashes and favicon fingerprints to identify potential C2 servers.  
4. Combine with your threat intelligence workflows or SOC investigations.

---

## Who Is This For?

This repository is intended for:  
- Threat Hunters  
- SOC Analysts  
- Blue Teamers  
- Malware Researchers  

It provides structured and reusable techniques for discovering and tracking C2 infrastructure.

---

## Contributing

Contributions are welcome!  
- Add new urlscan.io queries or SHA256/favicons from your research.  
- Submit issues for errors or suggestions.  

---

## Disclaimer

This repository is for **educational and research purposes only**. Do **not** use the resources for illegal activities.
```

