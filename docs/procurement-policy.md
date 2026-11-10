# Procurement Policy — Annotation Capacity Renewal (FY2026)

Owner: Data Platform Finance
Applies to: annual renewal of third-party annotation capacity used by released corpora.

## 1. Approved pricing basis

The only admissible basis for the renewal comparison is the **annual list price of the Pro plan**
shown on the vendor's archived regional quote pages, converted to USD at the fixed rates in
section 4. The list price is the number printed on the Pro plan price row for each region, before any promotional credit.

## 2. License gate

The upstream dataset card governs which capacity tier may be purchased.

- Permissive licenses: `apache-2.0`, `mit`, `bsd-3-clause`, `cc-by-4.0`
  -> standard shared tier; `license_review_required` = false.
- Anything else (including no declared license, non-commercial or research-only terms,
  or an unrecognised identifier) -> isolated dedicated tier; `license_review_required` = true.

## 3. Tie-break

If two regions have the same list price in USD (within one cent), select the region code
that sorts first lexicographically.

## 4. Fixed FX rates for budget conversion

| Currency | Rate to USD |
|----------|-------------|
| EUR | 1 EUR = 1.08 USD |
| SGD | 1 SGD = 0.745 USD |
| USD | 1 USD = 1.00 USD |

## 5. Separate commercial programs

Gift cards, trade-in allowances, onboarding credits and installment financing are operated
as separate commercial programs under their own terms. Taxes and VAT are excluded from the
quoted amounts.

## 6. Record keeping

Commit the decision to `compliance/vendor_selection.json` with the fields defined in the
audit issue.
