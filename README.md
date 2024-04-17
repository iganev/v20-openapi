[![validate](https://github.com/iganev/v20-openapi/actions/workflows/validate.yml/badge.svg)](https://github.com/iganev/v20-openapi/actions/workflows/validate.yml)

# OANDA v20 API OpenAPI Specification

Fork of the original [oanda repository](https://github.com/oanda/v20-openapi).

## Goals

Goals of this repository:

- [x] fix OpenAPI v2 schema to pass validation
- [x] convert OpenAPI v2 schema to valid OpenAPI v3 schema
- [x] fix OpenAPI v3 schema authentication mechanism
- [x] add environments (fxPractice / fxTrade) to OpenAPI v3 schema
- [ ] fish out inconsistencies, deprecations and downright wrong endpoints

## Disclaimers

- To reduce the amount of effort necessary I have dropped the support for the separate (category based) schema files.
- I have abandoned OANDA's original ChangeLog. Refer to the [Goals](#goals) section instead.
- Nothing is guaranteed. Use at your own risk.