# Allocator Bookkeeping Repository for 1001XR


## Pathway description

1001XR is the strict open-commons allocator specializing in verifiably reproducible, openly licensed datasets with clear public benefit. Clients who publish a public reproducibility pipeline receive priority and <24 h approvals. Highest standards of transparency and legal compliance – no enterprise/private data ever.

## Allocator JSON Link
https://github.com/filecoin-project/Allocator-Registry/blob/main/Allocators/1001xr.json  

## Contact Information

- Website: https://1001xr.com
- Allocator Email: zhangys@1001xr.com
- Slack (Filecoin): @1001xr
- GitHub: https://github.com/meiiss4
- Bookkeeping Repository: https://github.com/meiiss4/1001xr-Bookkeeping
- Organization Wallet: f2kedaxt4fls43ngrnnw5hf4amtnaie6sgrsllfgy
- Allocator Wallet: f2cp4py4vzsfqjxw3gdedrcdyzx5k27equaqdtyoq


## Client Diligence

We exclusively serve open-commons clients and apply the following layered verification process:

1. **Identity Verification & Sybil Resistance**  
   - Mandatory authentication via verified GitHub account (>1 year old, meaningful activity) + institutional/corporate email domain  
   - For requests >100 TiB or any risk flags: government-issued ID (individuals) or KYB (organizations – business registration, legal entity proof)  
   - Strict rate limiting: one primary entity per GitHub org / email domain / legal entity  
   - All verification steps logged with timestamps and evidence hashes in the bookkeeping repo

2. **Legitimate Rights & Open License Verification**  
   - Clients must provide source URL/provenance + explicit open license (CC0, CC-BY, CC-BY-SA, ODbL, MIT, Apache-2.0, Public Domain, etc.) that permits unrestricted redistribution  
   - We manually verify license authenticity and that the client has lawful redistribution rights  
   - Self-certification of legal compliance (no PII unless anonymized + compliant, no export-control violations, etc.)

3. **Technical & Graduated Trust (Tranche System)**  
   - Strictly follow Fil+ tranche schedule (5% → 10% → 15% → 20% → 25%, never 2× previous tranche)  
   - Advancement requires 100% compliance on prior tranches: successful deals, SP diversity (≥3 unrelated SPs), geographic diversity (≥2 continents from tranche 3), retrieval checks passed

4. **Audit Trail**  
   - All verification evidence (anonymized where required) is permanently stored in https://github.com/meiiss4/1001xr-Bookkeeping  
   - Complete trail available to Governance within 7*24 hours of request

## Description of Data Diligence

We perform rigorous pre-allocation checks tailored to open, reproducible datasets:

1. **Scope & Public Benefit Verification**  
   - Dataset must demonstrably serve scientific, cultural, educational, civic, or governmental purposes  
   - Must be released under verified open license with no commercial restrictions

2. **Content & Integrity Validation**  
   - CID resolution via public gateways + cid.contact  
   - Spot sampling of payload content to confirm match with client declaration  
   - Metadata cross-check (schema, size, format, license)

3. **Reproducibility Mandate**  
   - All allocations ≥10 TiB require a public GitHub (or equivalent) repository containing a complete, working pipeline that regenerates raw sources → exact final CID  
   - We execute the pipeline on our infrastructure whenever feasible – failure = rejection

4. **On-Chain & Network Compliance Monitoring**  
   - Post-allocation: monitor IPNI compliance (datacapstats.io)  
   - Verify real storage deals (no placeholders/self-deals) via Filscan/Filfox Explorer  
   - Enforce SP diversity and geographic distribution

5. **Audit-Ready Evidence**  
   - Full diligence package per allocation stored publicly: application form, license proof, reproducibility repo URL + execution logs, CID validation screenshots, legal self-certification, on-chain deal list  
   - All records immutable in bookkeeping repository from day one


## Allocation policy

1. Only openly licensed, public-benefit datasets  
2. Reproducibility pipeline mandatory for ≥10 TiB  
3. Strict tranche schedule enforced (5/10/15/20/25%, never 2× previous)  
4. New clients capped at 50 TiB initial allocation  
5. From tranche 3: ≥3 unrelated SPs + ≥2 continents  
6. Max 150 TiB/week per verified entity  
7. All allocations require human review (no automation bypass)

## Risk Mitigation Strategies

- Every allocation manually reviewed  
- Reproducibility requirement = strongest sybil defense  
- Rate limits + tranche system  
- Immediate revocation for non-compliance  
- All diligence artifacts public and immutable  
- Real-time monitoring dashboard + alerts  
- Quarterly third-party tooling audit

## Dispute Resolutions

**Internal (client ↔ 1001XR):** 7-day appeal window → final binding decision within 72 h  

**External (governance / other allocators):** Full diligence trail provided within 48 h. We accept Governance decisions as final and will claw back DataCap immediately if required.

## Compliance Audit Check

- All records public in this repo from day one  
- Monthly automated compliance reports (/audits folder)  
- Quarterly retrieval testing on ≥10% of deals >50 TiB  
- Annual external audit starting 2026 (report published)  
- Full cooperation with Governance audits (additional records within 72 h of signed request)
