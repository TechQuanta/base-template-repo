```mermaid
flowchart TD
    A[Repository Root]

    A --> B[.github]
    A --> C[README.md]
    A --> D[CONTRIBUTING.md]

    B --> B1[ISSUE_TEMPLATE]
    B --> B2[workflows]
    B --> B3[CODEOWNERS]
    B --> B4[CODE_OF_CONDUCT.md]
    B --> B5[LICENSE]
    B --> B6[PULL_REQUEST_TEMPLATE.md]
    B --> B7[SECURITY.md]
    B --> B8[dependabot.yml]

    B1 --> B11[bug_report.md]
    B1 --> B12[bug_report.yml]
    B1 --> B13[config.yml]
    B1 --> B14[custom.md]
    B1 --> B15[feature_request.md]
    B1 --> B16[feature_request.yml]

    B2 --> B21[lint.yml]

    A --> E[Base Template / Source]
    E --> E1[src]
    E --> E2[templates]
    E --> E3[configs]
    E --> E4[output]
