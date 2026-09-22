## Summary

<!-- What does this change do, and why? 2-4 sentences. -->

## Jira Ticket

<!-- The Jira ticket ID is now required and verified in the PR TITLE itself,
     e.g. "fix(PROJ-123): correct retry logic" - not required here anymore.
     Use this section only for extra context: related/linked tickets, or
     "No related ticket" if genuinely none. -->

## Type of Change

* [ ] Bug fix (non-breaking change which fixes an issue)
* [ ] New feature (non-breaking change which adds functionality)
* [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
* [ ] This change requires a documentation update

## Configuration / Values Changes

<!-- Does this PR add, remove, or change any Helm values, environment variables,
     or configuration keys? Answer Yes or No. If Yes, list the keys. -->

## Feature Flag

<!-- If this change ships behind a feature flag, name it and its default state
     (on/off). Write "N/A" if this change is not flag-gated. -->

## Breaking Change Details

<!-- Required only if "Breaking change" is checked above.
     Describe what breaks and the migration/upgrade path. -->

## Local Agent Impact

<!-- This is checked automatically against the files this PR actually
     changes (Compute, Orchestrator, or Proxy code) - but please also
     confirm below regardless of what you expect the automatic check to say. -->

* [ ] Yes - this PR changes Compute, Orchestrator, or Proxy code
* [ ] No - this PR does not affect the Local Agent

## Local Agent Impact Details

<!-- Required only if 'Local Agent Impact' is Yes above, or if this PR's
     file changes are automatically detected as touching Local Agent code.
     Describe the impact and how it was tested. Leave blank if Local Agent
     Impact is No and no relevant files changed. -->

## Testing

<!-- How was this verified? What did you run or check? -->

## Checklist

* [ ] My code follows style guidelines
* [ ] I performed a self-review of my code
* [ ] I commented my code, particularly in hard-to-understand areas
* [ ] I made corresponding changes to the documentation
* [ ] My changes generate no new warnings
* [ ] I added tests exercising my implementation
* [ ] New and existing unit tests pass locally with my changes
* [ ] I have checked my code and corrected any misspellings
* [ ] I considered security ramifications and mitigated to the best of my knowledge
* [ ] Any dependent changes have been merged and published in downstream modules
