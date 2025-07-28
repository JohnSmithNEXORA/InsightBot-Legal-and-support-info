# InsightBot for Power BI
## Professional User Support Guide

*Version 2.0 | July 2025*

---

## Overview
InsightBot is an advanced AI-powered custom visual for Microsoft Power BI that leverages large language model APIs to provide conversational data analysis and insights. This enterprise-grade solution enables users to interact with their data through natural language queries, enhancing data exploration and business intelligence capabilities.

## System Requirements

### Software Requirements 
- **Power BI Desktop**: Latest version recommended, minimum 2023 release
- **Power BI Service**: Full compatibility with all current plans
- **Browsers**: Microsoft Edge (latest 3 versions), Chrome (latest 3 versions), Firefox (latest 3 versions), Safari (latest 3 versions)

### Network Requirements
- Stable internet connection (minimum 5 Mbps)
- Firewall configuration that allows API calls to selected LLM providers
- Corporate proxy settings that permit external AI service connections

## Implementation

### Installation
1. Import the InsightBot custom visual from the Power BI Marketplace
2. Add the visual to your report canvas
3. Configure data bindings to connect the visual to your dataset
4. Set up API authentication in the visual properties panel

### Configuration

#### API Integration
- **Provider Selection**: Choose from supported LLM providers or connect to your organization's private API endpoint
- **API Authentication**: Enter your API key in the secure credential manager
- **Model Selection**: Specify which model to use based on your performance and capability requirements
- **Endpoint Configuration**: Enter the complete API endpoint URL from your provider's documentation

#### Context Management
- **Data Explorer**: Navigate the data context panel to view which tables and fields will be used to respond to queries
- **Context Limitation**: Set maximum token limit for context (recommended: 2000+ tokens for optimal responses)
- **Prompt Engineering**: Customize system prompts to guide the AI's behavior and response format

#### Visual Customization
- **Branding Options**: Set your organization's name, logo, and color scheme
- **Welcome Message**: Configure the initial greeting displayed to users
- **Interaction Settings**: Configure streaming behavior, response formatting, and user/bot avatar display
- **Refresh Controls**: Use the reset function to apply visual configuration changes

## Advanced Features

### Developer Mode
- Access comprehensive logging and debugging tools
- View token usage metrics per query
- Examine raw API responses for troubleshooting
- Configure advanced prompt engineering templates

### Enterprise Integration
- **Data Residency Controls**: Configure to use only your organization's hosted models to maintain data sovereignty
- **Audit Logging**: Track all queries and responses for compliance and governance
- **SSO Integration**: Connect with your organization's identity provider for seamless authentication
- **Role-Based Access**: Configure different capabilities based on user permissions in Power BI

## Performance Optimization

### Response Time Improvement
- Use streaming mode for immediate feedback during query processing
- Implement query caching for frequently asked questions
- Select geographically closer API endpoints where available

### Quality Enhancement
- Increase context token limitation for more comprehensive data understanding
- Use custom prompt templates tailored to your specific data domain
- Configure temperature settings based on need for creativity vs. precision

## Troubleshooting

### Authentication Issues
| Error Message | Probable Cause | Resolution |
|---------------|----------------|------------|
| "API Key is missing" | No API key provided in configuration | Navigate to API settings and enter a valid key |
| "Invalid API Key" | Expired or incorrect API key | Verify and update API key in settings |
| "Authentication failed" | Permission issues with API provider | Check subscription status and permissions |

### Connectivity Problems
| Error Message | Probable Cause | Resolution |
|---------------|----------------|------------|
| "Network connection lost" | Internet connectivity issues | Verify network connection and proxy settings |
| "Error Communicating with AI service" | Endpoint unavailability or timeout | Verify endpoint URL and try an alternative provider |
| "Bad request" | Incorrect model specification or API parameters | Confirm model name and parameter format in configuration |

### Response Quality Issues
| Symptoms | Probable Cause | Resolution |
|----------|----------------|------------|
| Inaccurate analysis | Insufficient context | Increase token limit and improve prompt engineering |
| Incomplete responses | Token limit constraints | Adjust maximum response token settings |
| Irrelevant answers | Poor context understanding | Refine system prompt to better define expected analysis |

## Support Resources

### Technical Support
- **Email**: johnsmithnexora@gmail.com
- **Response SLA**: Within 24 business hours for standard issues, 4 hours for critical issues
- **Support Hours**: 24/7 for critical issues, 8AM-6PM PT Mon-Fri for standard issues


### Support Request Information
Please include the following when contacting support:
- Power BI version and build number
- Visual version number
- Detailed issue description with steps to reproduce
- Error messages (screenshots or logs)
- API provider in use
- Data volume/schema information (if relevant)

## Service Level Agreement

### Availability
- 99.9% uptime guarantee for the visual component
- Scheduled maintenance windows: Sundays, 2-4 AM ET (announced 72 hours in advance)


### Performance Metrics
- Average response time: Under 3 seconds for standard queries
- Throughput: Up to 100 queries per hour per user
- Concurrent users: Up to 50 per Power BI capacity node

## Known Limitations
- Response quality varies by selected LLM provider and model
- Complex visualizations cannot be generated within chat responses
- Maximum context size varies by LLM provider (see provider documentation)
- Some regulatory/compliance restrictions may apply to certain data types

## Roadmap & Updates
- Quarterly feature updates (no user action required)
- Monthly performance optimizations
- Custom visualization response capabilities (Coming Q2 2025)
- Multi-language support expansion (Coming Q3 2025)

## Feedback and Continuous Improvement
We actively solicit and incorporate user feedback to enhance InsightBot. Submit feature requests and improvement suggestions through:
- In-app feedback button
- Email: johnsmithnexora@gmail.com



---

© 2025 Nexora Labs  
250 Quantum Blvd, Mountain View, CA 94043  
Enterprise Support: +1 (831) 273-3563  
