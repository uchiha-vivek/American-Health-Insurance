# American Health Insurance

<p align="center">
  <img src="assets/hcr.jpeg" alt="American health insurance" width="420">
</p>

American health insurance helps people manage medical risk and can support stronger families, healthier communities, and productivity.

Contributing to MAGA, Make America Great Again.

## Basic Ideas

Insurance is a way to manage risk.

In the USA, dental, vision, and health insurance are different.

Premium: the fee you pay to your provider, usually monthly, in order to keep up your health insurance.

Deductible: the amount you pay before insurance starts paying for covered services.

Example:

- Suppose your deductible is `$100`.
- Suppose your visit to the doctor or medical test costs `$100`.
- It is on us to pay that `$100`.
- Next time, when we go and get a `$100` service, insurance will pay for it.

Deductible resets on calendar year.

It resets on July 1.

Premium is inversely related to deductible:

```text
Premium proportional to 1 / deductible
```

Out-of-pocket max:

- Family OOP max: `$60,000`.
- OOP max means the maximum amount you would ever have to pay for health coverage during the year.

## Copayments And Coinsurance

Copayments or copays are a set amount of money that you have to pay whenever you receive certain medical procedures, prescription medicines, tests, etc.

Copays do not count toward your deductible.

Coinsurance:

- A `$100` test with `20%` coinsurance means that you will pay `$20`.
- `100%` coinsurance means you need to pay everything.
- Copay and coinsurance count toward the out-of-pocket maximum.

## Drug Tiers

- Tier 4: specialty drugs.
- Tier 3: non-preferred brand-name drugs.
- Tier 2: brand-name drugs.
- Tier 1: generic drugs.

## Enrollment And Provider Networks

Open enrollment: November 1 to January 15.

This is the only time of the year when everyone is allowed to change their health insurance.

In-network providers:

- They work with the insurance company.
- The procedures you get with them will be covered.

Out-of-network providers:

- Not covered.

## Plan Types

### HMO

HMO means Health Maintenance Organization.

- Most common individual marketplace plan.
- Preference: your doctors are in network.
- Low premium.
- You have to stay in network.
- Must be referred to a specialist by your primary care physician.

### PPO

PPO means Preferred Provider Organization.

- It has a wider network than HMO.
- Insurance means that your job pays for it as one of the benefits.

Pros:

- Large network of providers.
- Can use out-of-network providers.
- Do not need a PCP to refer you to a specialist.

Cons:

- High premium.

### EPO

EPO means Exclusive Provider Organization.

- You can go out of network, but you do not need to have a primary care physician.

### POS

POS means Point of Service.

- Allowed to go out of network.
- Need a PCP referral.

## Savings Accounts

HSA: Health Savings Account.

MSA: Medical Savings Account.

HDHP: High Deductible Health Plan.

- Need HDHP.

FSA: Flexible Spending Account.

HRA: Health Reimbursement Arrangement.

- Only available through a job.

## Government Programs

Medicare:

- Federal program.
- For people 65 years old and older.
- Medicare Advantage is through an insurer.

Medicaid:

- For low-income individuals and families.
- Federal program, but it is administered by each state.

Obamacare:

- Notes mention Obamacare, but no extra details were written.

## Math Notes From Screenshot

```text
(1 + x)^n => nC0 x^0 + nC1 x^1 + nC2 x^2 + ... + nCn x^n

nCu = n! / u!(n-u)!

Let the a, b, c map to r - 1, r, r + 1

nCr / nC(r-1) = b / a = (n - r + 1) / r

Similarly:

c / b = nC(r+1) / nCr = (n - r) / (r + 1)

Try to get rid of r by using equations 3 and 4, substitution.

a(n + 1) / (a + b) = (bn - c) / (b + c)

(an + a)(b + c) = (bn - c)(a + b)

abn + anc + ab + ac = bna + b^2n - ca - bc

ab + bc + ac + ca = b^2n - anc = n(b^2 - ac)

ab + bc + 2ac = n(b^2 - ac)

n = (ab + bc + 2ac) / (b^2 - ac)

Option B
```
