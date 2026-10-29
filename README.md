# QA Environment Hub

Open `index.html` in a browser, or serve this folder through any static web server.

## Service Code Hub import format

The Service Code Hub uses a simple service-code sheet with exactly these columns:

| CODE | NAME | DESCRIPTION |
| --- | --- | --- |
| `PAY-400` | `Payment validation` | `Handles payment validation requests` |

CSV, XLSX, and XLS files are supported. Duplicate `CODE` values can be skipped or updated during import.

Environment names and details are maintained manually in **Environment Hub**. All app data is stored locally in the current browser; use **Export data** to create a backup.
