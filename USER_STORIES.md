# Twinlane — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Head of data platform

- As a platform head, I want Production deadline attainment and Ad hoc wait times on one board, so that I stop starving SLA jobs for curiosity SQL.
- As a platform head, I want cost showback by lane and owner, so that capacity debates are factual.

### Analytics engineer / batch owner

- As an analytics engineer, I want to promote a tested Azkaban-class workflow from dev to prod with a review record, so that production stays reviewable.
- As an analytics engineer, I want deadline classes on scheduled jobs, so that Databee-like periodic batches are protected.
- As an analytics engineer, I want serving sink registration when I publish a dataset, so that consumers know freshness and owner.

### Data scientist (ad-hoc)

- As a data scientist, I want a performant Ad hoc lane with masked replicas, so that I explore without touching Production capacity.
- As a data scientist, I want GUI and CLI access scoped to Ad hoc by default, so that I cannot accidentally launch heavy jobs on the SLA cluster.
- As a data scientist, I want a clear path to request promotion when an experiment should industrialise, so that discovery can become product.

### Stream platform SRE

- As a stream SRE, I want Kafka-class topic ownership and consumer lag SLOs, so that activity pipelines match LinkedIn-style contracts.
- As a stream SRE, I want results feedback topics governed when Production writes back to the bus, so that loops remain safe.

### Steward / administrator

- As a data steward, I want lineage from federated DB dump or event log to BI cube, so that audit can replay trust.
- As an administrator, I want break-glass Production changes time-boxed with retrospectives, so that emergencies do not become culture.
- As an administrator, I want to deny replication of restricted fields into Ad hoc, so that discovery stays compliant.
