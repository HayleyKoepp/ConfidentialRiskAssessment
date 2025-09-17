# Confidential Risk Assessment System

A privacy-preserving risk evaluation system built on Ethereum blockchain using Zama's Fully Homomorphic Encryption (FHE) technology. This system enables secure, confidential risk assessments for companies while maintaining complete data privacy.

## 🔑 Core Concepts

### Fully Homomorphic Encryption (FHE)
The system leverages Zama's FHE technology to perform computations on encrypted data without ever exposing the underlying sensitive information. This ensures that:
- Risk assessment data remains encrypted at all times
- Calculations are performed on encrypted values
- Only authorized parties can decrypt specific data points
- Complete privacy is maintained throughout the entire process

### Confidential Risk Data Architecture
The system handles multiple dimensions of risk assessment:
- **Financial Risk**: Credit worthiness, cash flow stability, debt ratios
- **Operational Risk**: Process efficiency, operational failures, business continuity
- **Reputational Risk**: Brand perception, market standing, public relations impact
- **Compliance Risk**: Regulatory adherence, legal compliance, audit results

Each risk metric is encrypted using FHE before storage, ensuring that even the smart contract cannot access the raw values while still enabling risk score calculations and comparisons.

## 🛡️ Privacy Risk Data Protection

### Multi-Layer Encryption
- **Data Encryption**: All risk values are encrypted using Zama's FHE before blockchain storage
- **Access Control**: Granular permissions ensure only authorized assessors and companies can access specific data
- **Computation Privacy**: Risk calculations occur on encrypted data without decryption
- **Zero-Knowledge Comparisons**: Risk level comparisons between companies without revealing actual scores

### Confidential Data Types
The system protects various types of sensitive business information:
- Industry-specific risk factors
- Company size and operational metrics
- Geographic risk exposure
- Historical assessment records
- Comparative risk analysis results

## 🚀 Key Features

### 🔐 Privacy-First Architecture
Complete data confidentiality using state-of-the-art homomorphic encryption, ensuring sensitive risk data never leaves encrypted form during processing.

### 📊 Multi-Dimensional Risk Analysis
Comprehensive assessment framework covering financial stability, operational efficiency, reputational standing, and regulatory compliance.

### ⚡ Real-Time Encrypted Computations
Instant risk score calculations and comparisons performed directly on encrypted data without compromising privacy.

### 🏢 Company Registration System
Secure onboarding process for companies seeking risk assessments with encrypted profile management.

### 👥 Authorized Assessor Network
Controlled access system ensuring only qualified professionals can perform risk evaluations.

### 📈 Historical Assessment Tracking
Complete audit trail of all risk assessments while maintaining data confidentiality.

### 🔄 Secure Risk Comparisons
Compare risk levels between companies without exposing actual assessment data.

## 💼 Contract Information

**Contract Address**: `0x4C8A88dB129bCFFA79024c59dfDe83090a5B7fF6`

**Network**: Sepolia Testnet (Chain ID: 11155111)

**Deployment Status**: Active and operational

## 🎥 Demonstration Materials

### Video Demo
The project includes a comprehensive demonstration video (`ConfidentialRiskAssessment.mp4`) showcasing:
- Complete wallet connection process
- Company registration workflow
- Risk assessment creation
- Encrypted data handling
- Real-time risk calculations

### On-Chain Transaction Screenshots
Transaction verification screenshots (`ConfidentialRiskAssessment.png`) demonstrate:
- Successful smart contract deployment
- Company registration transactions
- Risk assessment creation transactions
- Encrypted data storage confirmations

## 🌐 Live Application

Experience the Confidential Risk Assessment System:
**Website**: [https://confidential-risk-assessment.vercel.app/](https://confidential-risk-assessment.vercel.app/)

## 📊 Technical Architecture

### Smart Contract Features
- **FHE Integration**: Native support for Zama's Fully Homomorphic Encryption
- **Role-Based Access**: Owner, assessor, and company permission levels
- **Event Logging**: Comprehensive activity tracking for audit purposes
- **Data Validation**: Input sanitization and range validation for all risk metrics

### Encryption Workflow
1. **Data Input**: Risk values entered through secure web interface
2. **Client-Side Validation**: Input validation before encryption
3. **FHE Encryption**: Data encrypted using Zama's FHE library
4. **Blockchain Storage**: Encrypted data stored on Ethereum blockchain
5. **Computation**: Risk calculations performed on encrypted values
6. **Access Control**: Granular permissions for data access

### Security Measures
- **Input Validation**: All risk values validated within 0-100 range
- **Address Verification**: Ethereum address validation for all participants
- **Access Control**: Multi-level permission system
- **Event Logging**: Complete audit trail of all operations

## 🎯 Use Cases

### Financial Institutions
- Credit risk assessment for loan applications
- Investment portfolio risk evaluation
- Regulatory compliance monitoring

### Insurance Companies
- Policy risk evaluation
- Premium calculation based on risk factors
- Claims prediction modeling

### Corporate Risk Management
- Vendor risk assessment
- Partnership due diligence
- Supply chain risk evaluation

### Regulatory Compliance
- Risk-based audit planning
- Compliance monitoring
- Regulatory reporting

## 🔍 Risk Assessment Process

1. **Company Registration**: Secure onboarding with encrypted profile creation
2. **Assessor Authorization**: Qualified professionals granted assessment permissions
3. **Risk Data Collection**: Multi-dimensional risk factors gathered and encrypted
4. **Encrypted Computation**: Risk scores calculated on encrypted data
5. **Secure Storage**: All data stored encrypted on blockchain
6. **Confidential Reporting**: Risk levels communicated without exposing raw data

## 📊 Risk Scoring Methodology

The system employs a weighted scoring algorithm:
- **Financial Risk**: 30% weight
- **Operational Risk**: 25% weight
- **Reputational Risk**: 25% weight
- **Compliance Risk**: 20% weight

All calculations are performed on encrypted values, ensuring complete privacy while maintaining accurate risk assessment capabilities.

## 🔗 Repository

**Source Code**: [https://github.com/HayleyKoepp/ConfidentialRiskAssessment](https://github.com/HayleyKoepp/ConfidentialRiskAssessment)

---

*This project demonstrates the practical application of Fully Homomorphic Encryption in real-world risk assessment scenarios, providing enterprise-grade privacy protection while enabling sophisticated risk analysis capabilities.*