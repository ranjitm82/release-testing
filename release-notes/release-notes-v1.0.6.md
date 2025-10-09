# Production Release Notes

| Key | Value |
| --- | ----- |
| Service | Rewards Gateway |
| Release Version | v1.0.6 |
| Environment | Production |
| Team | D2C Engineering |
| Release Type | Major |
| Release Date | 2025-10-09 |
| Jira Ticket | RC-100 |

## 1. Overview
This release includes new features, bug fixes, and infra updates.

## 2. Merged Pull Requests from 2025-10-01 to 2025-10-08
| PR | Commit | Title | Author | Labels |
|----|--------|-------|--------|--------|
| [#2](https://github.com/ranjitm82/release-testing/pull/2) | [`ad2c9fd`](https://github.com/ranjitm82/release-testing/commit/ad2c9fd36b9b7ac61adaf948aefd0e30c16b6ec5) | Create test2.txt | ranjitm82 | - |
| [#1](https://github.com/ranjitm82/release-testing/pull/1) | [`92f9f42`](https://github.com/ranjitm82/release-testing/commit/92f9f422b9c381ce2fb6b84ed9bb7793c295069e) | Create hello.txt | ranjitm82 | - |

## 3. Technical Changes
- Upgraded database cluster
- Updated authentication service
- Code refactoring in billing module

## 4. Post-Deployment Checks
- Smoke testing
- Dashboard & API monitoring
- Log analysis

## 5. Stakeholders
| Role | Name | Responsibility |
|------|------|----------------|
| Release Manager | John Doe | Oversees deployment |
| Test Lead | Jane Smith | Post-deployment validation |
| Tech Lead | Ranjit Kumar | Technical sign-off |

## 6. Rollback Plan
- Rollback to previous stable version (v1.0.4) if critical failure occurs.
- DB schema is backward compatible (if any).
