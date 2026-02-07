# Banking Agent - Yellow.ai Super Agent

## 🏦 Project Overview

A professional **Banking Agent** built with Yellow.ai's AI platform for the NextWave AI assignment. This super agent demonstrates multi-step OTP authentication, secure loan information retrieval, and token-optimized API integration.

**Bot Access Link:**
```
https://cloud.yellow.ai/bot/x1770463151741
```

## ✨ Key Features

### 1. **Multi-Step Authentication Flow**
- Intent Recognition: "I want to check my loan details"
- Data Collection: Phone number and Date of Birth
- OTP Trigger & Verification via banking API
- Secure Access to Loan Information

### 2. **Core Workflows**
- **triggerOTP**: Generates and sends OTP to user's registered phone
- **getLoanAccounts**: Fetches user's loan account list after authentication
- **loanDetails**: Retrieves detailed loan information including:
  - Outstanding balance
  - Interest rate
  - Payment schedule
  - Maturity date

### 3. **System Prompt Configuration**
- English-only communication enforcement
- Professional banking domain expertise
- Token optimization for efficient API calls
- Edge case handling (language attempts, invalid inputs)

### 4. **Mock API Integration**
- **Beeceptor Mock Server**: https://mp8c302d141e66cd4d86.free.beeceptor.com
- Endpoints:
  - `POST /trigger-otp` - OTP generation
  - `GET /loan-accounts` - Fetch accounts
  - `GET /loan-details` - Get loan information

## 🛠️ Technical Stack

- **Platform**: Yellow.ai Enterprise AI Platform
- **Model**: GPT-4 (gpt-4_1-2025-04-14)
- **Authentication**: Multi-step OTP-based
- **Mock APIs**: Beeceptor
- **Workflows**: Automated banking workflows
- **Testing**: Yellow.ai Playground

## 📋 Assignment Requirements Met

✅ **Objective**: Multi-step authentication banking agent  
✅ **Scenario**: Happy path with 8-step flow  
✅ **Technical Constraints**: Token optimization  
✅ **Resources**: Mock APIs + Workflows  
✅ **Submission**: Bot renamed + Access shared  

## 👥 Access & Sharing

**Bot Name**: Nagaraju Yellow Bank Agent

**Shared Team Members** (Admin Access):
- manasvi.sharma@yellow.ai
- kushagra.shrivastava@yellow.ai

## 🚀 Quick Start

1. **Access the Bot**: https://cloud.yellow.ai/bot/x1770463151741
2. **Test in Playground**: Use queries like "Show my loan details"
3. **Review Workflows**: Check Banking Workflows category
4. **View Mock APIs**: https://mp8c302d141e66cd4d86.free.beeceptor.com

## 📊 Project Stats

- **Workflows Created**: 3 (triggerOTP, getLoanAccounts, loanDetails)
- **Mock API Endpoints**: 3
- **System Prompt**: Fully configured
- **Team Members**: 2 (Shared access)
- **Testing Status**: ✅ Verified in Playground

## 📝 Notes

This project demonstrates enterprise-grade AI bot development with:
- Proper authentication mechanisms
- Token-optimized API responses
- Professional system prompts
- Secure information handling
- Multi-step workflow automation

## 📄 Assignment Details

**Project**: Banking Agent with Yellow.ai  
**Created**: February 7, 2026  
**Author**: Nagaraju Kattuboyina  
**Status**: Complete & Tested  

---

**Repository**: https://github.com/NAGARAJU4582/Banking-Agent-Yellow-AI  
**Yellow.ai Bot**: https://cloud.yellow.ai/bot/x1770463151741
