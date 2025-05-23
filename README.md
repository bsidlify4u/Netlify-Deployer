# Netlify Deployer

A secure and feature-rich desktop application for managing and deploying Netlify sites.

## Features

- **Secure Deployment**: Deploy sites to Netlify with token-based authentication
- **A/B Testing**: Create and manage A/B tests to compare site variants
- **Build Management**: Configure and run build commands before deployment
- **Deployment History**: Track all your deployments with detailed logs
- **Configuration Management**: Save and load deployment configurations
- **TOML Configuration**: Edit netlify.toml configuration through the UI
- **Security Features**: Password protection and secure credential storage

## Installation

### Prerequisites

- Python 3.8 or higher
- PyQt6
- Netlify account and API token

### Setup

1. Clone the repository:
   ```
   git clone https://github.com/your-username/netlify-deployer.git
   cd netlify-deployer
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   python app.py
   ```

## A/B Testing

The A/B Testing feature allows you to:

1. Create tests comparing your original site with a variant
2. Configure traffic split between variants
3. Track visitor and conversion metrics
4. Visualize performance data
5. Promote winning variants

### Creating an A/B Test

1. Go to Features → A/B Testing
2. Click "Create New Test"
3. Enter test details:
   - Name
   - Original site URL
   - Variant directory
   - Traffic split percentage
   - Conversion goal
4. Click "Create"

### Managing Tests

- **View Details**: Click on any test to see detailed metrics
- **Pause/Resume**: Control test status
- **Promote Winner**: Replace the original with the better-performing variant

## Security

This application implements several security measures:

- Password protection for application access
- API token encryption
- Secure file operations with atomic writes
- Input validation and sanitization
- Error handling and logging

## Development

### Running Tests

```
pytest
```

### Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Netlify for their API
- PyQt6 team for the GUI framework
- Contributors to this project 
