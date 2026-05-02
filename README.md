# Robocorp

Robocorp is an open source RPA and workflow automation platform for building Python-based automation bots. The platform provides the Control Room API for managing workspaces, workers, processes, work items, assets, vaults, webhooks, and task packages. Robocorp also provides the RPA Framework, an open-source collection of Python libraries for robotic process automation including browser, desktop, email, Excel, PDF, and cloud service automation. The platform has evolved toward Sema4 AI for AI-powered automation actions.

**Website:** [https://robocorp.com](https://robocorp.com)

**GitHub:** [https://github.com/robocorp](https://github.com/robocorp)

**Documentation:** [https://robocorp.com/docs](https://robocorp.com/docs)

## APIs

### Robocorp Control Room API

The Robocorp Control Room API provides programmatic access to the orchestration platform for RPA automations. Authentication uses API keys with the `RC-WSKEY` prefix in the Authorization header.

- **Base URL:** `https://cloud.robocorp.com/api/v1`
- **Authentication:** API Key (`RC-WSKEY` prefix)
- **Documentation:** [https://robocorp.com/api](https://robocorp.com/api)
- **OpenAPI Spec:** [https://robocorp.com/api/openapi.json](https://robocorp.com/api/openapi.json)

#### Resource Categories

| Category | Description |
|----------|-------------|
| Workspace | Workspace details and configuration |
| Workers | Worker agent management and link token generation |
| Worker Groups | Worker organization and group assignment |
| Processes | Automation process definition and management |
| Process Runs | Process execution monitoring and control |
| Step Runs | Individual step output and artifact retrieval |
| Work Items | Input/output queue management for producer-consumer patterns |
| Assets | File and data asset storage |
| Vault | Secure secret and credential management |
| Webhooks | Process event notification configuration |
| Task Packages | Robot code deployment from zip, GitHub, or GitLab |
| Assistants | AI assistant management |

### RPA Framework

An open-source collection of Python libraries for robotic process automation.

- **Documentation:** [https://rpaframework.org/](https://rpaframework.org/)
- **GitHub:** [https://github.com/robocorp/rpaframework](https://github.com/robocorp/rpaframework)
- **PyPI:** [https://pypi.org/project/robocorp/](https://pypi.org/project/robocorp/)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [openapi/robocorp-control-room-openapi.yml](openapi/robocorp-control-room-openapi.yml) | Control Room API — workers, processes, work items, vault, webhooks, task packages |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [rules/robocorp-control-room-rules.yml](rules/robocorp-control-room-rules.yml) | Control Room API linting rules enforcing workspace ID patterns and RC-WSKEY auth |

### Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/automation-orchestration.yaml](capabilities/automation-orchestration.yaml) | Unified workflow for RPA automation orchestration |
| [capabilities/shared/control-room.yaml](capabilities/shared/control-room.yaml) | Shared Control Room API consumed definition |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [json-schema/robocorp-process-schema.json](json-schema/robocorp-process-schema.json) | Automation process with steps and schedules |
| [json-schema/robocorp-work-item-schema.json](json-schema/robocorp-work-item-schema.json) | Work item with state and payload |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [json-structure/robocorp-process-structure.json](json-structure/robocorp-process-structure.json) | Field documentation for the process object |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [json-ld/robocorp-context.jsonld](json-ld/robocorp-context.jsonld) | Linked data context mapping Robocorp terms to schema.org |

### Examples

| Example | Description |
|---------|-------------|
| [examples/robocorp-start-process-run-example.json](examples/robocorp-start-process-run-example.json) | Trigger a process execution run with variables |
| [examples/robocorp-create-work-item-example.json](examples/robocorp-create-work-item-example.json) | Add a work item to a process queue |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [vocabulary/robocorp-vocabulary.yml](vocabulary/robocorp-vocabulary.yml) | RPA domain terms including Process, WorkItem, Worker, Vault, TaskPackage |

## Tags

RPA, Workflow Automation, Python, Open Source, Automation
