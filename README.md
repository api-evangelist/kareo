# Kareo

Kareo, now part of Tebra, provides cloud medical software for independent practices. The platform offers APIs for integrating with clinical data, patient management, appointment scheduling, billing, collections, and insurance eligibility verification.

## APIs

### Kareo Integration SOAP API

The primary integration API is a SOAP-based web service available at `https://webservice.kareo.com/services/soap/2.1/KareoServices.svc`. It supports:

- Read access: patients, providers, appointments, transactions, charges, procedure codes, service locations, encounters, payments, and practices
- Write access: patients, appointments, encounters, and payments
- Authentication via username, password, and Customer Key

WSDL: `https://webservice.kareo.com/services/soap/2.1/KareoServices.svc?wsdl`

### Kareo Clinical Open API

A REST-based API for EHR clinical data access, documented with Swagger UI at `https://api.kareo.com/clinical/v1/swagger/`. Supports MACRA/MIPS reporting and clinical record access.

## Authentication

All API calls require:
1. Username and password credentials
2. A Customer Key issued by a System Administrator

The Customer Key must be generated and configured by the practice's System Administrator with appropriate security permissions.

## Documentation

- API Integration Guide: https://helpme.tebra.com/01_Kareo_PM/12_API_and_Integration
- Clinical Open API (Swagger): https://api.kareo.com/clinical/v1/swagger/
- API Terms of Use: https://www.tebra.com/api-terms-of-use/

## Pricing

API access is bundled with the Tebra platform subscription. No standalone API pricing is available. Platform pricing is quote-based, per clinical provider per month. Contact Tebra at (866) 938-3272 or visit https://www.tebra.com/demo.

## Status

Platform status: https://status.tebra.com

## Links

- Website: https://www.kareo.com
- Blog: https://www.tebra.com/theintake
- LinkedIn: https://www.linkedin.com/company/kareo
- GitHub: https://github.com/kareo
