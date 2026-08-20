# Pending payments — ISC-bound policies

_As of 2026-08-20. Built from Harper bound book (ISC / Integrated Specialty Coverages) crossed with open `FINAL_PAYMENT_PENDING`, `PAYMENT_FAILURE`, and `CANCELLATION_ALERT` tickets, then checked against email / SMS / call history on the highest-urgency items._

## How this list was built
1. Bound ISC book: `deals_v2` / placements where wholesaler is ISC (policy #s like `ISCP*`, `ISCSP*`, `ISCPC*`, `GLSISTC*`, `HSIC-ISC*`).
2. Open payment work: service tickets in payment-failure, final-payment-pending, and non-pay cancellation-alert stages.
3. Comms verification (email + SMS + phone) on priority accounts: Advanced Homes, Eagle, Alexandre, Smith & Co, C&C.

## A. Active pending payment / cure needed (46)

These ISC-bound accounts still need a payment, finance cure, or agency fee remittance.

### 1. Eagle Premium Exteriors (`911063`)
- **ISC / related policies:** ISCP04000084689, WC PC 946703-000
- **[PAYMENT_FAILURE]** ticket `127745` (blocked · priority critical): Confirm the $1,134 Pie workers compensation deposit is paid and policy WC PC 946703-000 remains in force without void-from-inception risk.
  - Pie deposit settlement and balance holder remain unverified; human task 7369 must complete any authorized payment and obtain carrier confirmation that WC policy WC PC 946703-000 remains in force.

### 2. JEJ Enterprises Handyman Services (`917154`)
- **ISC / related policies:** ISCPC04000088457
- **[CANCELLATION_ALERT]** ticket `126477` (blocked · priority critical): Restore documented active coverage through confirmed reinstatement or replacement, and notify the customer of the verified outcome.
  - ISC confirmed a finance NOC and cancellation effective August 16 for policy ISCPC04000088457. Coverage remains unverified/inactive; urgent human payment handling with Jump and NKLL DocuSign remain open before written reinstatement confirmation can be obtained.

### 3. William Hodge (`917144`)
- **ISC / related policies:** ISCSPCM000023230
- **[CANCELLATION_ALERT]** ticket `126478` (to_do · priority critical): Call customer to discuss reinstatement
  - The 04:32Z escalation-unanswered review found human task 6537 still todo with no written carrier reinstatement confirmation. The single due re-notification already occurred; preserve the human-only financed cure path and review at the 13:00Z daily sweep.

### 4. Advanced Homes Construction LLC (`917974`)
- **ISC / related policies:** ISCSP000023586
- **[PAYMENT_FAILURE]** ticket `127236` (in_progress · priority high): Monthly premium payment is completed before cancellation and the premium finance company confirms the account is current.
  - Payment guidance was delivered on 2026-08-18. Fresh goal check found no payment confirmation or Jump Premium Funding account-current confirmation; waiting on customer and rechecking in two business days.

### 5. Alexandre Painting & Handyman Services, LLC (`919640`)
- **ISC / related policies:** ISCSPCM000024320
- **[PAYMENT_FAILURE]** ticket `126050` (to_do · priority medium): Resolve financing error with PFA
  - Agile Premium Finance now also reports delivery failures for account 431073; Harper must verify the paid-in-full versus financed disposition and provide a confirmed valid insured email address.
- **[CANCELLATION_ALERT]** ticket `126048` (to_do): Settle account with finance company
  - A "Past Due Warning" has been issued by the premium finance company due to a processing error. Although the customer paid in full, the finance agreement was incorrectly activated. The brokerage must now settle the account with the finance company to prevent policy cancellation.

### 6. Bathhouse Remodeling LLC. (`909468`)
- **ISC / related policies:** GLSISTC012668226
- **[CANCELLATION_ALERT]** ticket `128516` (to_do · priority high): Keep policy GLSISTC012668226 in force by curing the premium-finance cancellation and obtaining written confirmation that the intent to cancel is rescinded.
  - Jump Premium Funding issued an intent-to-cancel notice for active policy GLSISTC012668226 after a missed financed-premium payment. Establish the notice deadline and complete the call-only financed cure before cancellation.

### 7. Beyond Painting (`918883`)
- **ISC / related policies:** ISCP04000089464
- **[CANCELLATION_ALERT]** ticket `126402` (to_do · priority high): Cancellation is rescinded in writing by Jump Premium Funding or the carrier before coverage terminates, with the outcome recorded on the issue.
  - Jump Premium Funding issued an intent-to-cancel notice for Beyond Painting LLC policy ISCP04000089464 after the first financed installment went unpaid; a call-only cure and written rescission confirmation are required.

### 8. Complete Handyman Solutions (`915479`)
- **ISC / related policies:** GLSISTC012579626
- **[CANCELLATION_ALERT]** ticket `126524` (to_do · priority high): Confirm whether the customer wants coverage restored and, if so, obtain written confirmation of reinstatement or replacement coverage; otherwise document the customer decision.
  - ISC reports a finance NOC for policy GLSISTC012579626 with cancellation dated August 16, 2026. The policy may already be lapsed; urgently call Derek to determine whether he wants reinstatement or replacement coverage, then verify exact cure and reinstatement terms with Jump or the carrier before making coverage stateme

### 9. Fang Metal Works (`915280`)
- **ISC / related policies:** ISCP04000089746
- **[CANCELLATION_ALERT]** ticket `128464` (to_do · priority high): Prevent cancellation of policy ISCP04000089746 or obtain written confirmation of the final policy status after the premium-finance cure is completed.
  - Jump Premium Funding sent an Intent to Cancel for active policy ISCP04000089746 after a missed financed installment; the cure deadline is already at risk and a call-only cure must be made immediately.

### 10. Kamazon Holdings LLC (`917216`)
- **ISC / related policies:** ISCP04000088651
- **[CANCELLATION_ALERT]** ticket `125895` (to_do · priority high): Obtain written confirmation from Agile Premium Finance or the carrier that the intent to cancel policy ISCP04000088651 has been rescinded after the overdue premium is cured.
  - Agile Premium Finance issued an intent-to-cancel notice for policy ISCP04000088651 due to an overdue $476.36 balance; the financed-account cure requires an immediate customer call and written rescission confirmation.

### 11. Kangaroo Contractors Scorp (`914866`)
- **ISC / related policies:** GLSISTC012587426
- **[CANCELLATION_ALERT]** ticket `126549` (to_do · priority high): Obtain written reinstatement or confirm the policy cannot be reinstated, with the insured informed of the verified coverage status.
  - ISC now corroborates that a finance NOC was received for policy GLSISTC012587426 with cancellation effective 2026-08-16; urgently verify the balance with Jump and obtain written reinstatement or no-reinstatement confirmation.

### 12. L&L Welding and Fabrication LLC (`916634`)
- **ISC / related policies:** ISCP04000088388
- **[CANCELLATION_ALERT]** ticket `126528` (to_do · priority high): Restore active coverage through documented reinstatement or replacement coverage and notify the insured with the verified outcome.
  - Policy ISCP04000088388 is reported cancelled effective August 16 for premium-finance non-payment. Human task 6764 is due by 13:00Z to call the insured, process the Jump cure, and send an NKLL through DocuSign; agent task 6561 waits on that action and written ISC reinstatement confirmation.

### 13. Middle Bay Contracting, LLC (`917785`)
- **ISC / related policies:** ISCP04000089708
- **[CANCELLATION_ALERT]** ticket `128432` (to_do · priority high): Prevent cancellation of policy ISCP04000089708 by satisfying the premium-finance cure and obtaining written confirmation that coverage remains active or is reinstated.
  - Jump Premium Funding holds the balance. $111.67 overdue plus a $5.58 late charge ($117.25 total) must be cured within the notice window. Financed-channel law requires a call; human task 7930 is due today to process payment with Jump, confirm the exact cancellation date, and obtain written rescission confirmation.

### 14. Optimum Site Prep (`917837`)
- **ISC / related policies:** ISCSPCM000023646
- **[CANCELLATION_ALERT]** ticket `125894` (to_do · priority high): Notify insured of cancellation risk
  - A cancellation notice has been issued for the customer's active General Liability policy due to a missed payment. The immediate priority is to alert the customer to resolve the outstanding balance and prevent a lapse in coverage. The pending endorsement request is a secondary priority.

### 15. Parker Tree Service LLC (`917360`)
- **ISC / related policies:** ISCSPCM000023903
- **[CANCELLATION_ALERT]** ticket `126486` (to_do · priority high): Obtain written confirmation that the intent to cancel policy ISCSPCM000023903 has been rescinded and the policy remains active after the financed payment cure.
  - Human call task 6549 remains open; fresh communications through 2026-08-20T11:13:16Z contain no financed payment cure or written rescission confirmation. Recheck at 2026-08-20T15:10:19Z.

### 16. RTYD Waterproofing Roofing And Repairs LLC (`918852`)
- **ISC / related policies:** ISCPC04000089444
- **[CANCELLATION_ALERT]** ticket `128816` (to_do · priority high): Prevent cancellation of policy ISCPC04000089444 by verifying the Agile Premium Finance cure amount and deadline, completing the required cure, and obtaining written confirmation that coverage remains in force.
  - Agile Premium Finance issued an intent-to-cancel notice after the missed installment; verify the notice terms and cure the financed balance before cancellation takes effect.
- **[CANCELLATION_ALERT]** ticket `128278` (to_do · priority medium): Contact customer for immediate payment
  - The policy is currently in a critical state and at risk of cancellation due to non-payment. A formal notice of intent to cancel has been issued by the premium finance company, making this a time-sensitive issue requiring immediate payment to maintain coverage.
- **[CANCELLATION_ALERT]** ticket `128277` (to_do): Contact insured to cure non-payment
  - The active policy is at risk of cancellation due to non-payment. The finance company has issued a 10-day notice. The service team must contact the customer to resolve the payment issue.

### 17. Rivera Landscaping, LLC (`918669`)
- **ISC / related policies:** GLSISTC012641326
- **[CANCELLATION_ALERT]** ticket `126571` (to_do · priority high): Cure the premium-finance delinquency and obtain written confirmation that policy GLSISTC012641326 remains active and the intent to cancel is withdrawn.
  - Jump Premium Funding sent an intent-to-cancel notice for non-payment on active policy GLSISTC012641326; contact Pablo Rivera, cure the overdue installment, and verify withdrawal in writing.

### 18. Robert Jackson Enterprises,llc (`918470`)
- **ISC / related policies:** GLSISTC012651026
- **[CANCELLATION_ALERT]** ticket `126533` (to_do · priority high): Prevent policy cancellation by curing the premium-finance nonpayment and obtain written confirmation that the intent-to-cancel notice is rescinded.
  - Jump Premium Funding issued an intent-to-cancel notice for active policies GLSISTC012651026 and IMEB18737; financed cure amount and cancellation effective date must be confirmed by phone.

### 19. Rusty's Tree Service LLC (`915476`)
- **ISC / related policies:** ISCP04000089798
- **[CANCELLATION_ALERT]** ticket `128580` (to_do · priority high): Prevent cancellation of policy ISCP04000089798 by curing the premium-finance delinquency and obtaining written confirmation that coverage remains in force.
  - Financed nonpayment cancellation remains uncured. An urgent human call is queued to verify Jump payoff and cancellation timing, process the customer-authorized cure, and obtain written confirmation that coverage remains in force.

### 20. Scott Honer (`917003`)
- **ISC / related policies:** GLSISTC012582726
- **[CANCELLATION_ALERT]** ticket `126542` (to_do · priority high): Obtain written confirmation whether policy GLSISTC012582726 can be reinstated, then document either completed cure and rescission or a rewrite handoff.
  - ISC confirmed a finance NOC for policy GLSISTC012582726 with cancellation date August 16. The existing human task to call Jump and the carrier for written reinstatement requirements or refusal remains the next action.

### 21. Supreme Plumbing Services LLC (`917747`)
- **ISC / related policies:** ISCPC04000088804
- **[CANCELLATION_ALERT]** ticket `125898` (to_do · priority high): Cancellation threat is removed and written confirmation shows policy ISCPC04000088804 remains active.
  - Agile Premium Finance issued an intent-to-cancel notice for non-payment; financed cure requires a call and written cancellation-rescission confirmation.

### 22. C&C Construction (`927539`)
- **ISC / related policies:** EIG6538584, HSIC-ISC01-0000959, ISCCX03000013362
- **[FINAL_PAYMENT_PENDING]** ticket `125305` (to_do): Await customer to set up autopay on Employers WC
  - Open payment ticket is for Employers WC EIG6538584 autopay. ISC GL HSIC-ISC01-0000959 and Excess ISCCX03000013362 were Jump-financed (statement 2026-08-14).

### 23. Smith & Co LLC (`919163`)
- **ISC / related policies:** ISCP04000090321, WC PI 4357737-000
- **[FINAL_PAYMENT_PENDING]** ticket `106402` (to_do): Pay $250 ISC broker fee
  - ISC withholding WC policy documents until Harper remits $250 broker fee via isc.epaypolicy.com

### 24. A&l Property Management, LLC (`919018`)
- **ISC / related policies:** ISCP04000089541
- **[CANCELLATION_ALERT]** ticket `127259` (to_do): Contact insured about cancellation notice
  - The policy is active but at immediate risk of cancellation due to non-payment to the premium finance company. Action is required to notify the insured and resolve the payment issue to prevent a lapse in coverage.

### 25. A1 Roofing (`918656`)
- **ISC / related policies:** GLSISTC012641226
- **[CANCELLATION_ALERT]** ticket `126377` (to_do · priority medium): Prevent cancellation of policy GLSISTC012641226 by curing the Jump Premium Funding default before the notice deadline and obtaining written confirmation that the cancellation is rescinded.
  - Jump Premium Funding issued an intent-to-cancel notice after the August financed installment was missed; verify the notice terms, call Brian Wood to arrange cure with Jump, then obtain written rescission confirmation.

### 26. Ace Welding And Fabrication, LLC (`916994`)
- **ISC / related policies:** ISCSPCM000023909
- **[CANCELLATION_ALERT]** ticket `126572` (to_do · priority medium): Keep policy ISCSPCM000023909 active by curing the premium-finance nonpayment and obtaining written confirmation that the intent to cancel is withdrawn.
  - Jump Premium Funding issued an intent-to-cancel notice for active policy ISCSPCM000023909 after the August 10 installment became overdue; cure is required before the cancellation window expires.

### 27. All Access Paving, LLC (`916858`)
- **ISC / related policies:** ISCSP000024001
- **[CANCELLATION_ALERT]** ticket `102141` (to_do): Contact insured to cure non-payment
  - The active policy is at risk of cancellation for non-payment. The service team needs to contact the insured to resolve the outstanding balance with the finance company.

### 28. All Island Home Improvement, Inc. (`918554`)
- **ISC / related policies:** ISCSP000024086
- **[CANCELLATION_ALERT]** ticket `112358` (to_do): Contact insured about cancellation notice
  - The customer's required Workers' Compensation policy was declined by all markets. Consequently, the customer has stopped making payments on their active General Liability policy, which has now triggered an "Intent to Cancel" notice from the premium finance company.

### 29. Avantstay Inc. (`916870`)
- **ISC / related policies:** ISCP04000088405
- **[CANCELLATION_ALERT]** ticket `118777` (to_do): Notify customer of pending cancellation
  - The policy is pending cancellation due to non-payment to the premium finance company. A formal notice has been issued, making the cancellation effective August 19, 2026. Urgent action is needed to inform the customer and resolve the payment issue to prevent a lapse in coverage.

### 30. Big A's Transport (`918606`)
- **ISC / related policies:** ISCPC04000089460
- **[CANCELLATION_ALERT]** ticket `126421` (to_do · priority medium): Keep policy ISCPC04000089460 in force by curing the Jump Premium Funding nonpayment before cancellation and obtaining written confirmation that the intent to cancel is rescinded.
  - Jump Premium Funding issued an intent to cancel for policy ISCPC04000089460; verify the notice amount and deadline, contact the insured by phone for the financed-payment cure, and obtain written rescission confirmation.

### 31. Carolina Wrenn General Contracting LLC (`916571`)
- **ISC / related policies:** ISCSP000023281
- **[CANCELLATION_ALERT]** ticket `128042` (to_do): Provide payment link to customer
  - The customer's policy is at immediate risk of cancellation for non-payment of their premium financing. The customer is aware and has requested a method to submit payment. The immediate task is to help the customer make the payment to the finance company to avoid cancellation.

### 32. Cassel Residential (`918945`)
- **ISC / related policies:** GLSISTC012653626
- **[CANCELLATION_ALERT]** ticket `127269` (to_do): Contact insured about cancellation notice
  - The policy is active, but a cancellation notice has been issued by the premium finance company due to non-payment. The immediate next step is to address this alert to prevent the policy from being cancelled.

### 33. Clean Slate Junk Removal And Demotion , LLC (`914254`)
- **ISC / related policies:** ISCPC04000089495
- **[CANCELLATION_ALERT]** ticket `127257` (to_do): Contact insured about pending cancellation
  - The policy is currently active but is at immediate risk of being cancelled. The premium finance company has issued an 'Intent to Cancel' notice due to a missed payment. The service team must intervene to prevent the policy from lapsing.

### 34. Clover General Contracting, Inc. (`917554`)
- **ISC / related policies:** ISCPC04000089496
- **[CANCELLATION_ALERT]** ticket `127268` (to_do): Contact insured about pending cancellation
  - The policy is active, but a cancellation notice has been issued for non-payment. Immediate follow-up with the customer is required to resolve the payment issue and prevent cancellation. The final policy documents are also ready to be sent.

### 35. Crownstone Construction (`914568`)
- **ISC / related policies:** ISCSP000023913
- **[CANCELLATION_ALERT]** ticket `126387` (to_do · priority medium): Prevent cancellation of policy ISCSP000023913 by curing the Jump Premium Funding delinquency before the cancellation effective date, evidenced by written confirmation that the policy remains in force.
  - Jump Premium Funding sent an intent-to-cancel notice for policy ISCSP000023913; cure amount and deadline must be verified and the insured contacted before cancellation.

### 36. David Rich (`916842`)
- **ISC / related policies:** ISCSP000024190
- **[CANCELLATION_ALERT]** ticket `128415` (to_do): Contact insured about cancellation notice
  - The policy is active but is now at risk of cancellation due to non-payment to the premium finance company. An "Intent to Cancel" notice has been issued. The insured needs to be contacted immediately to resolve the payment issue.

### 37. Garcia Builder Group LLC (`918841`)
- **ISC / related policies:** GLSISTC012649626
- **[CANCELLATION_ALERT]** ticket `126576` (to_do · priority medium): Cancellation threat is withdrawn in writing, or the policy status and next coverage action are confirmed with objective evidence.
  - Jump Premium Funding issued an Intent to Cancel for financed GL policy GLSISTC012649626; the cure amount and cancellation effective date are not visible in available email evidence, so a call-only cure is required now.

### 38. Hyman Roofing LLC (`914296`)
- **ISC / related policies:** ISCP04000088359
- **[CANCELLATION_ALERT]** ticket `125905` (to_do): Contact insured about cancellation notice
  - The policy is active but has received a cancellation notice from the premium finance company for non-payment. Action is required to prevent the policy from cancelling on August 22, 2026.

### 39. Jaime Paz Miranda (`919049`)
- **ISC / related policies:** ISCSPCM000024041
- **[CANCELLATION_ALERT]** ticket `101974` (to_do): Contact insured to cure non-payment
  - The policy is at risk of cancellation for non-payment. The service team must contact the insured to resolve the outstanding balance with the finance company.

### 40. Joe Construction Services, LLC (`918240`)
- **ISC / related policies:** ISCSPCM000023918
- **[CANCELLATION_ALERT]** ticket `105909` (to_do): Investigate and resolve cancellation notice
  - The customer's policy is facing cancellation from two sources: the carrier for non-compliance and the finance company for non-payment. The customer has urgently requested to stop the cancellation. The service team must investigate both issues and work to reinstate the policy.

### 41. Mike's Welding And Fabrication LLC (`916481`)
- **ISC / related policies:** ISCP04000089493
- **[CANCELLATION_ALERT]** ticket `127261` (to_do): Contact insured about cancellation notice
  - The policy is at risk of being cancelled due to non-payment of the premium finance installment. The most critical action is to contact the insured immediately to resolve the outstanding payment and prevent the policy from lapsing. An endorsement request is also pending, but it is secondary to the cancellation alert.

### 42. My Landscaper LLC (`918380`)
- **ISC / related policies:** ISCP04000089182
- **[CANCELLATION_ALERT]** ticket `127905` (to_do): Address cancellation notice with insured.
  - The policy is active but is now at risk of cancellation due to non-payment of a premium finance installment. The service team has received an official 'Intent to Cancel' notice and must take action to resolve the payment issue with the insured.

### 43. Ox Construction LLC (`919035`)
- **ISC / related policies:** ISCSPCM000024054
- **[CANCELLATION_ALERT]** ticket `127258` (to_do): Contact insured about cancellation notice
  - The policy is active, but a cancellation notice has been issued by the premium finance company due to non-payment. Urgent action is required to contact the insured and resolve the payment issue to prevent the policy from lapsing.

### 44. Remodeling With Quality (`918120`)
- **ISC / related policies:** ISCPC04000089829
- **[CANCELLATION_ALERT]** ticket `128430` (to_do · priority medium): Keep policy ISCPC04000089829 active by curing the Jump Premium Funding default and obtaining written confirmation that the cancellation is rescinded or called off.
  - Jump Premium Funding sent an Intent to Cancel notice for financed policy ISCPC04000089829. The cure amount and cancellation effective date are not visible in the available email preview; a call-only cure is required after reading the full notice.

### 45. The Honey Do Lister (`918674`)
- **ISC / related policies:** ISCP04000089709
- **[CANCELLATION_ALERT]** ticket `128429` (to_do · priority medium): Prevent cancellation of policy ISCP04000089709 by confirming the premium-finance delinquency is cured or obtaining documented reinstatement/continuation evidence before the cancellation window expires.
  - Human cancellation-cure task 7931 breached its 2026-08-20T08:30:00Z SLA after one re-notify and remains todo. Fresh reads found no call, cure payment, rescission, or continuation evidence. Operator must call Austin, verify the exact Jump payoff and cancellation date, cure through Jump if authorized, and obtain written 

### 46. Wc Trees LLC (`918408`)
- **ISC / related policies:** ISCSP000023809
- **[CANCELLATION_ALERT]** ticket `125226` (to_do · priority medium): Confirm customer made payment to avoid cancellation
  - Customer could not reach the previously provided payment contact; Harper sent corrected number 470-589-5486 in the same SMS thread. Cancellation cure remains open until payment is verified and Jump provides written rescission confirmation; human task 5704 remains the owner.

## B. Already cancelled for non-payment — cleanup still open (6)

### 1. Empire Ceilings And Painting LLC (`917275`)
- **Policies:** ISCP04000088534
- **[CANCELLATION_ALERT]** `126492`: Address policy cancellation with insured
  - The policy has been cancelled by the premium finance company due to non-payment. The service team needs to take action to address the cancellation status with the insured.

### 2. Greyling Homeworks (`917332`)
- **Policies:** GLSISTC012593326
- **[CANCELLATION_ALERT]** `126503`: Process cancellation request
  - The policy is being cancelled due to non-payment. The premium finance company has issued a formal cancellation notice that needs to be processed.

### 3. Junktion, LLC (`917249`)
- **Policies:** ISCPC04000088615
- **[CANCELLATION_ALERT]** `126508`: Process policy cancellation
  - The active policy has been cancelled by the premium finance company due to non-payment. The service team must process the cancellation.

### 4. Mark 1 Industries, LLC (`917239`)
- **Policies:** ISCPC04000088526
- **[CANCELLATION_ALERT]** `126501`: Contact customer regarding policy cancellation
  - The policy has been officially cancelled by the premium finance company due to non-payment. All binding steps were previously completed, but the policy is no longer active. Immediate action is required to inform the customer and discuss potential reinstatement or rewriting option

### 5. Qfw LLC (`917423`)
- **Policies:** ISCSPCM000023352
- **[CANCELLATION_ALERT]** `126515`: Process policy cancellation and notify agent.
  - The policy is no longer active and has been officially cancelled due to non-payment. The immediate issue is not part of the binding workflow, but rather a critical status change that requires internal processing and notification.

### 6. Svoge LLC DBA Final Spec Cleaning DBA  (`917337`)
- **Policies:** ISCSP000023290
- **[CANCELLATION_ALERT]** `126518`: Return financed broker fee
  - The policy has been flat cancelled for non-payment. The finance company has requested the return of the financed broker fee.

## C. Finance reinstatement confirmed — customer notify still open (1)

### 1. Pure Flow Cleaning Services Inc (`916798`)
- **Policies:** ISCSPCM000023192
- **[CANCELLATION_ALERT]** `127837`: Confirm reinstatement with customer
  - A missed payment triggered a cancellation notice, which has now been resolved with a reinstatement confirmation from the carrier. However, the customer is unaware of the resolution and has expressed significant frustration. The immediate priority is to communicate with the custom

## D. Related open COI work (on the payment accounts above)

- **C&C Construction** (`927539`) ticket `126380` [to_do/critical]: Issue COI with AI & WOS for Blue Moon
  - Goal not reached: human COI policy and holder validation task 6485 and callback task 6486 remain overdue; certificate delivery task 6488 remains blocked by task 6485. Next daily safety sweep is armed for 2026-08-20T12:00:00Z.
- **C&C Construction** (`927539`) ticket `3422` [open/P0]: Blue Moon Home Builders receives a valid workers compensation certificate for C&C Construction and the customer receives the requested callback.

## E. Related open endorsement work (on the payment accounts above)

- **Pure Flow Cleaning Services Inc** (`916798`) ticket `128414` [assigned/low]: Resolve the requested company change on the active policy; done when the carrier confirms the correct endorsement or rewrite path and the customer receives the resulting updated policy evidence.
  - Customer reports payment completed and asks to change the company on the reinstated active policy. Collect the exact new legal name and whether the EIN, ownership, address, or operations are changing before selecting the endorsement or rewrite path.

## Highest-urgency callouts (comms-verified)

1. **Advanced Homes Construction** (`917974`) — ISC GL `ISCSP000023586`. Jump Intent to Cancel; **$1,034.80** past due; cancel effective **2026-08-22**. Customer SMS asked how to pay (8/18); Harper sent Jump # 760-509-9830; **no payment confirmation yet**.
2. **Eagle Premium Exteriors** (`911063`) — ISC GL `ISCP04000084689` active; ISC-placed Pie WC `WC PC 946703-000` deposit **$1,134** unpaid (void-from-inception risk). Customer called repeatedly about deposit/COI confusion. ISC emailed invoices 8/17–8/18.
3. **Alexandre Painting** (`919640`) — ISC GL `ISCSPCM000024320`. Customer paid in full ($974.74) but Agile PFA also activated → Past Due Warning. Need Harper to settle financed vs paid-in-full with Agile and fix bounce email.
4. **Smith & Co** (`919163`) — ISC GL `ISCP04000090321` active; **$250 ISC broker fee** still past due (ISC email 8/3) blocking WC doc release. Pay at https://isc.epaypolicy.com/.
5. **C&C Construction** (`927539`) — ISC GL/Excess bound + Jump-financed; separate **Employers WC autopay** still open; **Blue Moon AI/WOS COI** still open/critical.

## Caveats
- Cancellation-alert queue pull is capped (~200 open rows); older ISC non-pay cancels beyond that window may exist.
- `service billing-ledger get` is not live yet, so money-state is inferred from tickets + finance-company emails/SMS/calls, not a single reconciled ledger.
- Some accounts show both GL (ISC) and WC (Pie/Employers) payment issues; both are listed when ISC placed/bound the account.