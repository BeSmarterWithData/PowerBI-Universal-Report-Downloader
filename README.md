# Power BI Universal Report Downloader

A lightweight tool that downloads Power BI reports from any workspace using the Fabric API and saves them in **PBIR (Power BI Report) / Project structure** format.

**Works on any report** — including legacy format reports and PBIR reports. Most importantly, this tool can download reports that are **unable to be downloaded directly from the Power BI service**.

## Quick Start Instructions  

### 🟢 One-Click Update & Run Tool
Always up-to-date and the easiest way to get started.  

➡️ [**Download One-Click Update & Run Tool**](https://github.com/BeSmarterWithData/PowerBI-Universal-Report-Downloader/releases/download/1.0/PowerBIReportDownloader.bat)

## How It Works

1. **Run `Universal Power BI Downloader.bat`** — downloads the latest version of this repo and executes the downloader script inline.
2. **Select your Power BI environment** (Public, USGov, China, etc.).
3. **Authenticate** with your Power BI account.
4. **Pick a workspace**, then **select one or more reports** to download.
5. Reports are saved to `C:\Power BI Backups` in PBIR / Project structure format.

<img width="311" height="351" alt="2" src="https://github.com/user-attachments/assets/e4b1d514-67d5-45af-8763-9191124ae1fe" /> <img width="310" height="353" alt="1" src="https://github.com/user-attachments/assets/15f01326-5638-4d96-8e2e-e9fdcbf3da5c" />


## Auto-Update

Every time you run **`Universal Power BI Downloader.bat`**, it automatically pulls the latest version of the script from this repository. There is no need to manually download updates — just keep using the same `.bat` file and you'll always be on the newest version.

## Compatibility

This tool works with **both legacy and PBIR formatted reports**. Regardless of the source format, every report is output in PBIR / Project structure format — and even legacy reports can be opened using the `.pbir` file.

## Output Format

Reports are downloaded in the **PBIR (Power BI Report) / Project structure** format. This is the same format used by Power BI Desktop's Developer Mode and PBIP projects.

Once downloaded, you can:

- **Open the `.pbir` file** in Power BI Desktop to view and edit the report.
- **Save as `.pbix`** from Power BI Desktop to convert to the standard packaged format.
- **Continue working in PBIP format** for source control, collaboration, and CI/CD workflows.

## Requirements

- Windows with PowerShell 5.1+
- Power BI account with access to the target workspace(s)
- The `MicrosoftPowerBIMgmt` PowerShell module (installed automatically if missing)

## Quick Start

Double-click **`Universal Power BI Downloader.bat`** and follow the prompts.

Same file to open and re-save when complete no matter which format the report is in:


Legacy format:

<img width="1336" height="422" alt="image" src="https://github.com/user-attachments/assets/bca4ca41-b545-4aea-9933-dd0f36fbec00" />

PBIR Format:

<img width="1193" height="362" alt="image" src="https://github.com/user-attachments/assets/edfe16ae-5264-4da1-8502-a1bcd3b66e70" />
