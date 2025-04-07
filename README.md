# ciq-backlog
List of prioritized features and technical debt work items

## Features

| ID | Requested By | Description                                                                                                                              | Status      | Priority | Creation Date |
|----|--------------|------------------------------------------------------------------------------------------------------------------------------------------|-------------|----------|---------------|
| F1 | jrs          | As an admin user I want to be able to retrieve a list of brands so that I confirm the presence and state of the set of persisted brands. | In Progress | 1.002    | 3-13-2025     |



## Feature Tasks

| ID | Created By | Feature ID | Component | Description                                                     | Creation Date | Status                                                        |
|----|------------|------------|-----------|-----------------------------------------------------------------|---------------|---------------------------------------------------------------|
| T1 | jrs        | F1         | schema    | Define, document, and implement the appropriate data structures | 3-13-2025     | [Complete](https://github.com/jrstiffler16/ciq-schema/pull/1) |
| T2 | jrs        | F1         | api       | Implement read brands list                                      | 4-07-2025     | Pending                                                       |


## Technical Debt/Technical Specs

| ID  | Created By | Description                                                                                                                                                             | Status  | Priority | Creation Date |
|-----|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------|----------|---------------|
| TD1 | jrs        | As a system owner I want to be able to matriculate component changes to specific environments (shared dev, test, uat, prod) so that a robust pipeline can be supported. | Pending | 1.001    | 04-04-2025    |

## Technical Debt/Technical Specs

| ID   | Created By | Tech Debt ID | Component | Description                                            | Creation Date | Status      |
|------|------------|--------------|-----------|--------------------------------------------------------|---------------|-------------|
| TDT1 | jrs        | TD1          | schema    | Set up db environments and profile-specific migrations | 04-07-2025    | In Progress |