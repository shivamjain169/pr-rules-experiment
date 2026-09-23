<!-- PR title must include the Jira ticket key(s), e.g.
     "SCRUM-123: fix retry logic" or "SCRUM-123 SCRUM-124: fix retry logic".
     Prefix the title with "WIP" to skip ticket validation while in progress. -->

## Summary

<!-- What does this change do, and why? 2-4 sentences. -->

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

<!-- "Yes" is ticked automatically (once) when this PR changes Compute,
     Orchestrator, or Proxy files. If that detection is wrong for this PR,
     untick "Yes" and tick "No" - a reviewer will be asked to confirm. -->

* [ ] Yes - this PR changes Compute, Orchestrator, or Proxy code
* [ ] No - this PR does not affect the Local Agent

## Local Agent Impact Details

<!-- Required if 'Local Agent Impact' is Yes. Describe the impact and how it
     was tested. Leave blank if Local Agent Impact is No. -->

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
