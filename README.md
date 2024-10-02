# Online Voting System with Face Recognition and Two-Factor Authentication

## Project Overview

This project is a secure digital voting system developed using the Django framework. It leverages face recognition and two-factor authentication to ensure that the voting process is reliable and secure. The system is designed for both administrators (Election Commission) and voters, offering a streamlined interface for each role.

### Key Features

- **Admin Login**: Handled by the Election Commission to manage the election, including candidate registration and election monitoring.
- **Voter Login**: Handled by registered voters using their Voter ID number and password.
- **Face Recognition**: Voters are required to use face recognition to validate their identity via a webcam or mobile camera.
- **Two-Factor Authentication (2FA)**: After successful face recognition, voters must pass a 2FA process to submit their vote.
- **Candidate Information**: Voters can view candidate profiles (income, works, etc.) to make informed voting decisions.
- **Single Vote**: Each voter can cast only one vote per election, ensuring a secure and tamper-free voting process.

## Prerequisites

- Python version 3.12.0
- PostgreSQL version 16.1
- API Key generated from 2factor. 
- App Password generated from Google account, refer Sign in with app passwords.

  
## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/online-voting-system.git
