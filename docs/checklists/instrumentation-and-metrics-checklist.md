# Instrumentation and Metrics Checklist

This minimal checklist ensures product changes are observable and measurable.

Pre-development
- [ ] Define success metrics and KPIs (Data Lead/Product)
- [ ] Identify events to instrument and required properties
- [ ] Add tracking plan entries or tickets for instrumentation work

During development
- [ ] Implement event instrumentation according to tracking plan
- [ ] Add server-side and client-side validations for event schema
- [ ] Ensure privacy/compliance considerations are met (PII avoidance)

Pre-release
- [ ] Validate events in staging using QA or analytics tools
- [ ] Ensure dashboards or alerts are prepared for key metrics
- [ ] Confirm data quality checks are in place

Post-release
- [ ] Monitor initial metric changes and validate data
- [ ] Triage anomalies and iterate on measurement gaps
