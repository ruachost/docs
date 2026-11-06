# Ruach API Documentation

This repository contains the documentation for Ruach messaging APIs, including SMS, WhatsApp, and SMTP email.

## Overview

Ruach provides APIs for sending SMS and WhatsApp messages, managing messaging resources, and tracking delivery. This documentation covers the available endpoints, authentication methods, payloads, and integration examples.

## Features

- **Complete API Reference**: All endpoints with examples in multiple languages
- **Authentication Guide**: Step-by-step authentication setup
- **WhatsApp Templates**: Connector discovery, template lookup, and bulk or personalized sends
- **Rich WhatsApp Messages**: Media, location, OTP, and carousel payload examples
- **Error Handling**: Comprehensive error codes and handling strategies
- **Webhook Integration**: Real-time delivery report setup
- **Code Examples**: Ready-to-use code samples in JavaScript, Python, PHP, and cURL

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## API Endpoints

### Core Features
- **SMS Sending**: Send individual and bulk SMS messages
- **WhatsApp Messaging**: Send approved templates with shared or per-recipient variables
- **Rich Media**: Add media, location, and carousel content to WhatsApp templates
- **Campaign Management**: Create and track SMS campaigns
- **Group Management**: Organize contacts into groups
- **Template System**: Create reusable message templates
- **Sender ID Management**: Manage approved sender IDs
- **Delivery Reports**: Real-time webhook notifications

### Authentication
All API requests require:
- `ApiKey`: Your unique API key
- `ClientId`: Your client identifier

## Publishing Changes

Changes are automatically deployed when pushed to the main branch. The documentation is hosted on Mintlify and updates in real-time.

## Support

For API support and questions:
- **Email**: support@ruach.ng
- **Documentation**: This site contains all the information you need
- **Integration Help**: Contact our technical team for custom integrations

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Mintlify Community](https://mintlify.com/community)
