# Attacks Mapping — SCADA-MV-IDS

This document maps the attack identifiers used in the **SCADA-MV-IDS** dataset to the names reported in the paper.

## Mapping Table

| Attack ID (Dataset)       | Paper Name (Article)       | Description                                |
| ------------------------ | -------------------------- | ---------------------------------------- |
| **AcunetixAutenticado**      | **XSS (Acunetix)**             | Cross-Site Scripting exploitation via Acunetix |
| **AcunetixDefaultXX**       | **SQL Injection (Acunetix)**   | SQL injection exploitation via Acunetix |
| **AcunetixScadaBRDefault**  | **SQL Injection (Arachni)**    | SQL injection exploitation via Arachni |
| **NexposeExaustiveNoFW**    | **Advanced scan (Nexpose)**    | Exhaustive vulnerability scanning without firewall |
| **AcunetixScadaAuthhm**     | **Auth Crawler (Acunetix)**    | Authenticated crawling of web applications |
| **AcunetixDefaultWire**     | **Nonauth Crawler (Acunetix)** | Non-authenticated crawling of web apps |
| **ArachniRodouporh**        | **Code Injection (Arachni)**   | Code injection attempts using Arachni |
| **SmodDosWriteAllRegisters**| **DoSAllRegisters (Smod)**     | DoS attack by writing to all Modbus registers |
| **SmodGetFunc**             | **Get Functions (Smod)**      | Enumeration of Modbus function codes |
| **ModFuzzer**              | **Scanner (ModFuzzer)**        | Fuzzing-based scanner for Modbus vulnerabilities |
| **Nmap**                   | **Portscan (Nmap)**            | TCP/UDP port scanning using Nmap |
| **PLCScan**                | **Modbus Scan (PLCScan)**      | Specialized scanning of PLCs and Modbus devices |
| **NessusDefault**          | **Basic scan (Nessus)**       | Default vulnerability scanning using Nessus |
| **NexposeFull**            | **Default scan (Nexpose)**    | Standard Nexpose vulnerability scan |
| **SmodScannerUID**         | **Scanner (Smod)**           | Modbus scanner for unit identifiers |
| **SmodDosWriteAllcoins**   | **DoSAllCoils (Smod)**      | DoS attack by writing to all Modbus coils |
