# Lab 02 - Interactive automobile-sales dashboard

## Features

- report-type dropdown for yearly or recession-period statistics;
- year dropdown for yearly reports;
- callback that disables the year selector during recession reports;
- four Plotly charts per report mode;
- responsive chart grid.

## Run

```bash
pip install -r ../../requirements.txt
python dashboard.py
```

Open the local URL printed by Dash.

## Screenshots

| File | Description |
|---|---|
| `lab02-01-output.png` | Initial dashboard output |
| `lab02-02-input.png` | Report selector |
| `lab02-03-input.png` | Output container |
| `lab02-04-recession-report.png` | Recession-period report |
| `lab02-05-yearly-report.png` | Yearly statistics report |

The dashboard loads its dataset from a course-hosted public CSV URL and requires internet access.