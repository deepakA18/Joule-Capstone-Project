Joule: Specialized Lending Protocol for Redeemable Assets on Solana
Project Overview
Joule is a specialized lending protocol built on Solana that optimizes for redeemable assets like staked SOL derivatives (e.g., jitoSOL). This protocol enables extremely capital-efficient borrowing while maintaining a robust safety profile.
Key Innovations
Capital-Efficient Borrowing

High LTV Ratios: Supports borrowing up to 70% LTV, significantly higher than traditional lending platforms
Focus on Redeemable Assets: Specifically designed for assets that can be converted back to their underlying token

Enhanced Safety Mechanisms

Liquidator of Last Resort: Automatic unstaking of collateral when positions reach 73% LTV
Zero Bad Debt Design: Eliminates the possibility of bad debt through automated liquidation processes
Delayed Weighted Average Interest Rate Model: Prevents manipulation and sudden APR spikes

Dual Yield Structure
Joule creates two effective tranches:

For Borrowers: Higher-yield, higher-risk position
For Depositors: Lower-yield but highly secure and liquid position

This structure creates value for all participants:

Traders: Execute efficient carry trades with optimal capital efficiency
Depositors: Access secure yields with enhanced liquidity

Technical Architecture
The protocol consists of several interconnected Solana programs:

Core Lending Engine: Manages deposits, loans, and interest calculations
Liquidator Service: Monitors positions and executes the "liquidator of last resort" mechanism
Rate Oracle: Implements the delayed weighted average interest rate model

Roadmap
Current Implementation

Core lending protocol functionality
Basic liquidation mechanisms
Interest rate modeling

Future Development

Liquidator of Last Resort: Full implementation of automatic unstaking mechanism
Delayed Weighted Average Interest Rate Model: Complete implementation with market-responsive adjustments
Integration with Additional Staked Derivatives: Expanding beyond jitoSOL to other redeemable assets

Solana Turbine Builder Cohort
This project was developed as part of the Solana Turbine Builders Cohort program. The repository contains:

Joule-Capstone-Project: Main lending protocol implementation
Other directories containing learning materials and practice programs from the cohort

🔧 Getting Started
bash# Clone the repository
git clone https://github.com/yourusername/solana-turbine-cohort.git

# Navigate to the project directory
cd solana-turbine-cohort/Joule-Capstone-Project

# Install dependencies
npm install

# Run tests
npm test

# Build the project
npm run build
📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.