# Ticket triage and approval workflow

## Intake

1. Receive a structured report from Discord or GitHub.
2. Remove or hide accidentally posted secrets and personal information.
3. Check for duplicates and request missing reproduction details.
4. Assign an impact level and affected product or edition.

## Analysis

1. Reproduce against the current test package.
2. Identify the affected Magical Bundle product and whether the problem belongs to the plugin, Resolve, macOS, or an unsupported media source.
3. Summarize impact, likely cause, workaround, proposed correction, and risk.

## Approval gate

No source change begins until the product owner explicitly approves the proposed correction. Approval to investigate is not approval to publish.

## Implementation and release

1. Implement the approved correction in a separate work item.
2. Run automated tests and the relevant Resolve scenario.
3. Prepare a candidate package and release notes.
4. Obtain owner approval before replacing customer downloads.
5. Close the issue only after the reporter or team verifies the result.
