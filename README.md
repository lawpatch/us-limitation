# Limitation of Liability (United States)

### Purpose

The limitation language in this repo is language for limitation of liability positions in **United States** legal agreements.

The examples assume the use of the LawPatch description clause <a href="https://github.com/lawpatch/lawpatch-docs" target="_blank">here</a>.

### What is a Limitation of Liability Clause?

A limitation of liability clause limits the amount of exposure a party faces if a claim is made against it.

There are no "magic words" that must be invoked in order to create an effective limitation of liability clause. However, U.S. lawyers tend to follow a fairly tight set of conventions.

You may have seen limitation of liability clauses in all capital letters. This is not strictly required, but a liability clause should be "conspicuous" in order to improve the likelihood that it will be enforceable.

It's safe to assume that no court will enforce a limitation of liablity if doing so is contrary to established public policy. For example, where a party seeks to absolve itself of liability for acts that threaten the safety of the general public.

### What Happens if the Contract is Silent on Liability?

As a general rule, a party's ability to recover for a violation of the contract is limited to damages that were a "reasonably foreseeable" consequence of the breach.

It isn't necessary to disclaim liability for unforeseeable damages, as they're excluded by general contract law principles.

### Consequential vs. Direct Damages

Within foreseeable damages, there two sub-classifications: "consequential" and "direct" damages.

"Direct damages" are those damages that a reasonable person would expect to follow from a violation of the agreement.

"Consequential damages" are those damages that a reasonable person would expect to follow from a violation of the agreement *due to a special circumstance of the party suffering harm, where such special circumstance is known to the other parties*. You may see consequential damages referred to in some cases as "special damages" or "indirect damages".

A common misconception is that direct damages are foreseeable, and consequentials are not. This is incorrect. Consequential damages are, by definition, foreseeable damages. Unlike direct damages, though, consequentials are unique when compared to the circumstances of a theoretical "typical" seller, service provider, customer, etc., as the case may be.

### Spectrum of Positions

There are a number of liability positions available in this repo:

- `us-limitation-0.md` limits liability to the fullest extent possible under the law;
- `us-limitation-1.md` limits liability to the amount described;
- `us-limitation-2.md` limits consequential loss liabilities only; and
- `us-limitation-3.md` does not limit liability at all (except liabilities arising from implied conditions).

### Position Parameters

The language in this repo is *not* language that you can import wholesale with a simple incorporation by reference - it assumes that you have included certain information in the clause that imports it.

**us-limitation-0: Full liability limitation**

Position parameters are:

- `Limiting Party` - The party relying on the limitation;
- `Subject` (optional) - Determines the scope of the limitation of liability. The default Subject is the Agreement itself.
- `Risks` (optional) - A description of specific risks that liability is limited in relation to; and
- `Exception` (optional) - An exception to the limitation of liability.

Here is an example of language incorporating the full limitation of liability.

> Provider <a href="https://github.com/lawpatch/us-limitation/blob/df4f935cf5b84432aabfcae3b833768bebcf5493/us-limitation-0.md" target="_blank">limits liability to Customer as much as the law allows</a> for the Services, including liabilities caused by:
- data loss; and
- availability of any software or data.

**us-limitation-1: Amount limitation**

Position parameters are:

- `Amount` - Means the maximum amount of liability, in U.S. dollars or by reference to a reference (such as the amount spent under the Agreement);
- `Limiting Party` - The party relying on the limitation;
- `Subject` (optional) - Determines the scope of the limitation of liability. The default Subject is the Agreement itself.
- `Risks` (optional) - A description of specific risks that liability is limited in relation to; and
- `Exception` (optional) - An exception to the limitation of liability.

Here is an example of language incorporating the limitation to an amount.

> Provider limits liability to Customer for the Services to the cost of the Services in accordance with the <a href="https://github.com/lawpatch/us-limitation/blob/df4f935cf5b84432aabfcae3b833768bebcf5493/us-limitation-1.md" target="_blank">LawPatch amount limitation</a>, including liabilities caused by:
- data loss; and
- availability of any software or data.

**us-limitation-2: Covering liability (except limiting consequential loss)**

Position parameters are:

- `Limiting Party` - The party relying on the limitation;
- `Subject` (optional) - Determines the scope of the limitation of liability. The default Subject is the Agreement itself.
- `Risks` (optional) - A description of specific risks that liability is limited in relation to; and
- `Exception` (optional) - An exception to the limitation of liability.

Here is an example of language incorporating the limitation of consequential loss.

> Provider <a href="https://github.com/lawpatch/us-limitation/blob/df4f935cf5b84432aabfcae3b833768bebcf5493/us-limitation-2.md" target="_blank">covers liabilities (except for consequential loss)</a> to Customer for the Services, including liabilities caused by:
- data loss; and
- availability of any software or data.

**us-limitation-3: Covering all liability**

Position parameters are:

- `Subject` - What the Limiting Party is assuming liability in relation to (subject of limitation); and
- `Exception` (optional) - An exception to the limitation of liability.

Here is an example of language calling a module to cover all losses.

> Provider <a href="https://github.com/lawpatch/us-limitation/blob/df4f935cf5b84432aabfcae3b833768bebcf5493/us-limitation-3.md" target="_blank">covers all liabilities incurred</a> by Customer for the Services.

### Using Multiple Positions

The parties will often have different liability positions in respect of each other.  Here's an example.

> - Provider <a href="https://github.com/lawpatch/us-limitation/blob/df4f935cf5b84432aabfcae3b833768bebcf5493/us-limitation-0.md" target="_blank">limits liability to Customer as much as the law allows</a> for the Services, including liabilities caused by:
    - data loss; and
    - availability of any software or data.
- Customer <a href="https://github.com/lawpatch/us-limitation/blob/df4f935cf5b84432aabfcae3b833768bebcf5493/us-limitation-0.md" target="_blank">covers liability except for consequential losses</a> arising from or caused by breaches of the Agreement.

There is an optional exception parameter for each position listed above. Here's how it might look if you use it.  In this example, the Provider fully limits liability for services, but makes an exception for certain negligence or misconduct.

> Provider <a href="https://github.com/lawpatch/us-limitation/blob/df4f935cf5b84432aabfcae3b833768bebcf5493/us-limitation-0.md" target="_blank">limits liability to Customer as much as the law allows</a> for the Services, including liabilities caused by:
- data loss; and
- availability of any software or data,

> except that, to the extent of Provider's gross negligence and/or wilfull misconduct, Provider shall <a href="https://github.com/lawpatch/us-limitation/blob/df4f935cf5b84432aabfcae3b833768bebcf5493/us-limitation-3.md" target="_blank">remain fully liable</a>.

### Not Legal Advice

This is not legal advice. Lawyers are involved in producing these terms, but they obviously aren't familiar with your circumstances and don't represent you. Speak to your lawyer to make sure that the limitation language is well aligned with your circumstances.

As with any U.S.-based agreements, the requirements of applicable state and local laws may require adjustments to the baseline terms offered here.

### Licence

The limitation language is released under the license in license.md.
