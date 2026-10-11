# Decision-model recommendation: legal-source maintenance

Date: 2026-10-11. Public-source proposal, not legal or tax advice.
Reviewed [README](https://github.com/Ethical-Tech-CoLab/us-entity-structure-guide/blob/0338ec7ded53676b16e359d6ba3f5fec62308e17/README.md),
including its primary-source contribution requirement.

## Useful bounded task

Assist maintainers with source relevance and claim support during updates:
does a current IRS/state-authority passage establish a particular statement
for the stated jurisdiction, entity type and date? Return supports /
contradicts / not established / insufficient evidence.

Check fee arithmetic, deadlines and explicit form identifiers in code.
Separate incorporation jurisdiction from registration-to-do-business duties.
Retain the guide's legal-advice disclaimer and date every source.

## Do not automate the founder's decision

Do not select a legal entity, claim tax exemption or authorize a filing based
on model probability. Entity resolution here concerns document/source identity,
not equivalence of legally distinct organizations. A confident model cannot
substitute for counsel or an authoritative current filing requirement.

## Evaluation

Compare a human checklist and exact source checks with local classifiers,
Jev's [citation pattern](https://docs.typesafe.ai/cookbooks/citation_check.md),
Microsoft-Decision-1 and Sage on public authority documents.
Split by authority/jurisdiction and time. Include superseded forms, fiscal
sponsorship versus exemption, federal/state scope mismatches and absent fees.

Measure false support, relevant-source recall, calibration, unknown handling
and cost per accepted maintenance item. Preserve disagreements for qualified
human review. Hosted models need approved use; exact proprietary weights are
not available locally.

## Gate

Start offline; no changes to fees, legal statements or decision paths without
a primary-source citation and maintainer approval. This recommendation contains
no new legal claim and does not update existing numbers. Proceed only if review
benefit exceeds added inference and correction costs.
