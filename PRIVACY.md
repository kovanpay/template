# Privacy Policy

**Last Updated:** January 2025

## 1. Introduction

This Privacy Policy describes how this application ("Bot") collects, uses, and protects your information when you use our Twitter/X giveaway tracking service.

## 2. Information We Collect

### 2.1 Information You Provide
- Twitter API credentials (stored locally in `.env`)
- Wallet addresses (EVM, Solana) for airdrop participation
- Account preferences and settings

### 2.2 Information Collected Automatically
- Tweet interaction history
- Search queries and keywords
- Action logs (likes, retweets, comments)
- Error logs and performance data

### 2.3 Information We DO NOT Collect
- ❌ Private keys
- ❌ Seed phrases / Mnemonic phrases
- ❌ Passwords
- ❌ Email addresses
- ❌ Phone numbers
- ❌ Real identity information
- ❌ Payment information

## 3. How We Use Your Information

We use collected information to:
- Provide giveaway tracking and participation services
- Filter legitimate campaigns from scams
- Generate wallet addresses for airdrops
- Maintain action history and logs
- Improve Bot performance and features

## 4. Data Storage

### 4.1 Local Storage
All data is stored locally on your device:
- `.env` - API credentials (chmod 600)
- `wallet.txt` - Wallet addresses & keys (chmod 600)
- `database.db` - Action history & logs
- `bot.log` - Activity logs

### 4.2 Security Measures
- File permissions set to 600 (owner only)
- No cloud storage of sensitive data
- No transmission of private keys
- Encrypted local storage recommended

## 5. Data Sharing

We DO NOT share, sell, or transmit your data to:
- Third parties
- Advertisers
- Data brokers
- Government agencies

**Exceptions:**
- Twitter/X API (required for functionality)
- Groq API (for AI content analysis)
- Legal requirements (court orders, subpoenas)

## 6. Third-Party Services

This Bot integrates with:

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| Twitter/X API | Tweet search & actions | https://twitter.com/privacy |
| Groq API | AI content filtering | https://groq.com/privacy |
| EVM Networks | Wallet generation | Network-specific |
| Solana Network | Wallet generation | https://solana.com/privacy |

## 7. Data Retention

We retain data:
- **API Credentials:** Until you delete `.env` file
- **Wallet Data:** Until you delete `wallet.txt` file
- **Action Logs:** Indefinitely (stored in `database.db`)
- **Error Logs:** 30 days (stored in `bot.log`)

You can delete all data by removing the Bot directory.

## 8. Your Rights

You have the right to:
- Access all stored data
- Delete any or all data
- Export your data
- Opt-out of data collection (by discontinuing use)

## 9. Children's Privacy

This service is not intended for users under 18 years of age. We do not knowingly collect information from children.

## 10. International Data Transfers

Data is processed and stored locally on your device. API requests may be transmitted to:
- Twitter/X servers (global)
- Groq API servers (US-based)

## 11. Security

We implement security measures:
- Local storage only (no cloud)
- File permission restrictions (chmod 600)
- No transmission of sensitive data
- Regular security updates

**However, no method is 100% secure. You use at your own risk.**

## 12. Changes to This Policy

We may update this Privacy Policy periodically. Changes will be posted on our GitHub repository with updated "Last Updated" date.

## 13. Contact Us

For privacy questions or concerns:
- **GitHub:** https://github.com/yourusername
- **Email:** [Your Email]
- **Issues:** https://github.com/yourusername/repo/issues

## 14. Consent

By using this Bot, you consent to this Privacy Policy and agree to its terms.
