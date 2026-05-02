# Reflect

Reflect is an AI-powered automated end-to-end testing platform that enables teams to effortlessly create, execute, and troubleshoot automated browser tests. Reflect provides a no-code test recorder and a REST API for integrating test execution into CI/CD pipelines with support for environment overrides.

**Human URL:** [https://reflect.run](https://reflect.run)

**API Documentation:** [https://reflect.run/docs/developer-api/documentation/](https://reflect.run/docs/developer-api/documentation/)

## Tags

- Testing
- AI Testing
- Automated Testing
- End-to-End Testing
- CI/CD
- QA
- Artificial Intelligence

## APIs

### Reflect API
REST API for listing tests, triggering test executions, and checking execution status.

**Base URL:** `https://api.reflect.run/v1`

- [Documentation](https://reflect.run/docs/developer-api/documentation/)
- [OpenAPI](openapi/reflect-openapi.yml)
- [Getting Started](https://reflect.run/docs/overview/quick-start/)

## Artifacts

### OpenAPI Specifications

| Specification | Description |
|---------------|-------------|
| [Reflect OpenAPI](openapi/reflect-openapi.yml) | REST API for test management and execution |

### Rules

| Ruleset | Description |
|---------|-------------|
| [Reflect Rules](rules/reflect-rules.yml) | Spectral ruleset for Reflect API conventions |

### Capabilities

| Capability | Description |
|------------|-------------|
| [Test Automation](capabilities/test-automation.yaml) | End-to-end test management and execution for CI/CD |

**Shared Definitions:**
- [Reflect API](capabilities/shared/reflect.yaml)

### JSON Schema

| Schema | Description |
|--------|-------------|
| [Test Schema](json-schema/reflect-test-schema.json) | Reflect test definition with ID, name, and tags |
| [Execution Schema](json-schema/reflect-execution-schema.json) | Test execution with status and per-test results |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [API Structure](json-structure/reflect-api-structure.json) | Structural documentation for all Reflect API endpoints |

### JSON-LD

| Context | Description |
|---------|-------------|
| [Reflect Context](json-ld/reflect-context.jsonld) | JSON-LD context for test and execution entities |

### Examples

| Example | Description |
|---------|-------------|
| [List Tests](examples/reflect-list-tests-example.json) | List all available tests |
| [Run Test](examples/reflect-run-test-example.json) | Trigger a test execution with overrides |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [Reflect Vocabulary](vocabulary/reflect-vocabulary.yml) | Domain vocabulary for automated testing and Reflect concepts |

## Common Properties

- [Pricing](https://reflect.run/pricing/)
- [Articles](https://reflect.run/articles/)
- [Sign Up](https://app.reflect.run/registration)
- [Terms of Service](https://reflect.run/terms-of-service/)
- [Privacy Policy](https://reflect.run/privacy-policy/)
- [Integrations](https://reflect.run/docs/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
