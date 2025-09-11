## Summary
Briefly describe what this PR does (1–2 lines).

## Branch Naming Convention
Branch must follow this format:  
`[firstLetterFirstName][firstLetterLastName]/[type]/[action]`

**Examples**
- `ae/feature/add-company-api`
- `ae/bug/fix-login-issue`
- `ae/refactor/cleanup-dto`

## Type
- [ ] Feature
- [ ] Bug Fix
- [ ] Refactor
- [ ] Chore/Build
- [ ] Docs

## Checklist
- [ ] Branch name follows the convention above.
- [ ] Code follows naming conventions (PascalCase classes, camelCase vars, `_camelCase` private fields).
- [ ] No business logic in Controllers (move to Application/Services).
- [ ] Proper validation (FluentValidation/DataAnnotations) with clear messages.
- [ ] Unit tests created/updated for new logic.
- [ ] No hardcoded secrets or connection strings.
- [ ] RESTful endpoints (GET /companies, POST /companies).
- [ ] API responses use ProblemDetails format for errors.
- [ ] Swagger docs updated (summary, tags, response codes).
- [ ] Migrations run locally ( `dotnet ef database update` successful ).
- [ ] Code formatted (`.editorconfig` rules applied).
- [ ] Logs are meaningful (no sensitive data).
- [ ] Avoid unnecessary materialization (`ToList()` on large queries).

## Screenshots / Evidence
(Optional) UI changes, Swagger examples, request/response samples.

## Linked Issue / Ticket
closes #ISSUE_ID
