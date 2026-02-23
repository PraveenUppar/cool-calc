<p align="center">
  <img src="screenshots/banner.png" alt="CoolCalc Logo" />
</p>

<h1 align="center">CoolCalc — Cool Storage Cost Saving with IOPS Calculator</h1>

<p align="center">
  An Azure Storage Cost Optimization &amp; IOPS Recommendation Tool
</p>

<p align="center">
  <a href="https://dev-blocks.vercel.app/">
    <img src="https://img.shields.io/website?url=https%3A%2F%2Fdev-blocks.vercel.app&label=Live%20Demo" alt="Website" />
  </a>
  <img src="https://img.shields.io/github/issues/PraveenUppar/Dev-Blocks" alt="Issues" />
  <img src="https://img.shields.io/github/last-commit/PraveenUppar/Dev-Blocks" alt="Last Commit" />
</p>

---

## Description

Optimizing cloud storage costs while ensuring adequate performance is a critical challenge for businesses. **CoolCalc** is a React-based calculator that helps users make informed decisions about their Azure storage strategies by providing real-time cost comparisons and tailored IOPS subscription recommendations across various storage tiers and geographical regions.

The application will guide you through entering your dataset size, number of users, per-user IOPS requirements, and desired region to calculate and compare storage costs and receive IOPS recommendations.

## Features

- **Real-time Cost Comparison:** Instantly view monthly and annual cost differences with and without "cool access" storage options.
- **Regional Cost Analysis:** Calculate savings across Azure regions (Australia, US, Europe, Asia, etc.) with regional pricing variations.
- **Tailored IOPS Recommendations:** Personalized IOPS subscription suggestions based on data size, user count, and per-user IOPS requirements.
- **Multiple Storage Options:** Compare costs across 5 Azure storage tiers:
  - Standard Storage
  - Premium Storage
  - Ultra ANF (Azure NetApp Files)
  - Azure Files
  - Azure Files Premium
- **Scalability Scenarios:** Handle complex scenarios such as 1,000 users each needing 100 IOPS.
- **Interactive Charts:** Visualize cost savings with Chart.js-powered graphs.
- **Intuitive UI:** User-friendly interface to input parameters and understand results at a glance.

## Screenshots

|            Savings Graph            |        IOPS Calculator        |
| :---------------------------------: | :---------------------------: |
| ![Savings](screenshots/savings.png) | ![IOPS](screenshots/iops.png) |

|      Cost Comparison Graph      |
| :-----------------------------: |
| ![Graph](screenshots/graph.png) |

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/cool-storage-iops-calculator.git
cd cool-storage-iops-calculator
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm start
```

## Support

If you encounter any issues or have questions, please [open an issue](https://github.com/your-username/cool-storage-iops-calculator/issues) on GitHub.

## Contributing

Contributions are welcome! To get started:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## Project Status

This project is actively maintained. Contributions, feedback, and suggestions are always welcome!
