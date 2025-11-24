# AIM Crisis Dashboard

**Open-source monitoring system for tracking societal mimetic dynamics using the Appetites-Intrinsic Motivation-Mimetic Desire (AIM) Framework.**

## Overview

This repository provides tools to:
- Collect public data on happiness, polarization, trust, and political violence
- Compute AIM weights (wA, wI, wM) using transparent Bayesian methodology
- Visualize crisis trajectories and mimetic escalation patterns
- Enable early detection of mimetic crisis thresholds

## Theoretical Foundation

Built on the AIM Framework for understanding human motivation at individual and societal scales:
- **A (Appetites)**: Physiological needs, material security
- **I (Intrinsic Motivation)**: Autonomy, competence, relatedness
- **M (Mimetic Desire)**: Status competition, social comparison, rivalry

See `docs/methodology.md` for detailed theoretical grounding.

## Features

- **Data Collection**: Automated scrapers for WHR, V-Dem, GSS, GDELT, CDC
- **AIM Weights Calculation**: Bayesian estimation from observable indicators
- **Interactive Dashboards**: Real-time crisis index visualization
- **Mimetic Contagion Tracking**: Social media keyword/network analysis
- **Open & Reproducible**: All code, data, and methods publicly auditable

## Quick Start

```bash
# Clone repository
git clone https://github.com/lnxchange/AIM-Crisis-Data-Hub.git
cd AIM-Crisis-Data-Hub

# Install dependencies
pip install -r requirements.txt

# Run sample dashboard
streamlit run dashboards/streamlit_app.py
```

## Data Sources

- World Happiness Report (WHR)
- Varieties of Democracy (V-Dem) Project
- DW-Nominate Congressional Polarization
- General Social Survey (GSS)
- GDELT Global Events Database
- CDC Youth Risk Behavior Surveillance
- Harvard Youth Poll

## Documentation

- [Methodology](docs/methodology.md) - Theoretical framework and weight calculation
- [Data Sources](docs/data-sources.md) - APIs, access methods, update frequencies
- [Deployment Guide](docs/deployment-guide.md) - Self-hosting and cloud options

## Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License - see [LICENSE](LICENSE)

## Citation

If you use this tool in research, please cite:

```
Guttenbeil, Y. (2025). AIM Crisis Dashboard: Open-source monitoring 
for mimetic dynamics. GitHub. https://github.com/lnxchange/aim-crisis-dashboard
```

## Theoretical Papers

- [AIM Motivation Framework - Comprehensive Foundation](link-to-ssrn)
- [Methodology for AIM Weight Estimation](link-to-methodology)
- [The Easterlin Paradox: AIM Resolution](link-to-paper)

## Contact

[Your contact information or issues link]

## Disclaimer

This is a diagnostic tool for research and public awareness. It is not predictive 
of specific events and should not be used as sole basis for policy decisions. 
All data interpretation requires contextual expertise.
