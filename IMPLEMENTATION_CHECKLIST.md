# Implementation Checklist

Build the application yourself using `PROJECT_BRIEF.md`.

## Initial setup

- [ ] Read the project specification.
- [ ] Review the architecture and data model.
- [ ] Create a Python virtual environment.
- [ ] Install and pin the required dependencies.
- [ ] Configure credentials through environment variables.
- [ ] Review the data privacy and security requirements.

## Project acceptance criteria

- [ ] Upload endpoint returns 200 and file ID
- [ ] Extracted schema matches file preview
- [ ] Generated script passes basic syntax check
- [ ] Script reflects at least 80% of keywords from user intent
- [ ] Execution succeeds for 90% of test cases
- [ ] Agent produces corrected script after ≤2 iterations
- [ ] Preview matches expected transformation for provided test cases
- [ ] Download link returns correct file
- [ ] Set up FastAPI project
- [ ] Configure PostgreSQL + pgvector schema
- [ ] Implement file upload & schema extraction
- [ ] Integrate LangChain ReAct agent
- [ ] Create SchemaExtractor and CodeExecutor tools
- [ ] Add vector cache for scripts
- [ ] Build Docker sandbox image with limited resources
- [ ] Implement error feedback loop
- [ ] Write unit tests for execution safety
- [ ] Add minimal React UI for upload & preview
- [ ] Integrate OpenTelemetry tracing
- [ ] Write CI pipeline (GitHub Actions)
- [ ] Unit test each FastAPI route with pytest and httpx
- [ ] Integration test LLM agent using a mock LLM (responses stored in fixtures)
- [ ] Security test: ensure Docker sandbox cannot access host filesystem
- [ ] Load test: simulate 10 concurrent requests with locust
- [ ] Dockerize FastAPI app and sandbox image
- [ ] Compose services (api, db, sandbox, otel‑collector) for local dev
- [ ] Deploy to Render or Railway (managed Postgres) using Docker Compose
- [ ] Enable HTTPS via Let's Encrypt

## Before completion

- [ ] Implement the planned MVP features.
- [ ] Add unit and integration tests.
- [ ] Run the test suite.
- [ ] Measure the evaluation metrics in the brief.
- [ ] Record actual results and known limitations.
- [ ] Document setup and deployment.
- [ ] Update the README to reflect the implemented features.
- [ ] Add only verified outcomes to your resume.
