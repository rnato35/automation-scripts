# Automation Scripts

Collection of automation scripts organized by cloud provider and service.

## Structure

```
automation-scripts/
├── AWS/                    # AWS-specific scripts
│   ├── requirements.txt    # Python dependencies
│   ├── .venv/             # Virtual environment (created locally)
│   └── ...scripts...
└── ...other-providers...
```

## Getting Started

### AWS Scripts
Navigate to the AWS directory and follow the setup instructions:

```bash
cd AWS/
```

See [AWS/README.md](AWS/README.md) for detailed setup and usage instructions.

## Organization

- Each cloud provider has its own directory (AWS, Azure, GCP, etc.)
- Each directory contains its own virtual environment and requirements
- Scripts are organized by service or function within each provider directory