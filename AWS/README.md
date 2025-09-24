# Automation Scripts

Collection of AWS cost audit and automation scripts.

## Setup

### First Time Setup
```bash
# Create virtual environment
python3 -m venv .venv

# Activate virtual environment
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### Daily Usage
```bash
# Activate virtual environment (run this each time you work on scripts)
source .venv/bin/activate

# Your scripts will now work
python3 cost_audit_v2.py --region us-east-1
```

## Scripts

### cost_audit_v2.py
Python script for EC2 cost auditing and optimization recommendations.

**Usage:**
```bash
python3 cost_audit_v2.py --region us-east-1
```

### cost-auditv2.sh
Bash version of the cost audit script.

**Usage:**
```bash
./cost-auditv2.sh
```

## Requirements
- AWS CLI configured with credentials
- Python 3.x
- AWS permissions for EC2 describe operations
