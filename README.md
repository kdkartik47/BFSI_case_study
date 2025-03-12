# BFSI_case_study

All BFSI institutions are faced with a major default problem: not every individual that takes a loan has the willingness, ability and/or integrity to pay it back. Thus, an average of 2-5% default rate is observed across banks for different loan categories like personal loan, education loan, vehicle loan, business loan etc. Given the fact that banks can never get this number to zero, it has to keep it within limits, and rather keep it at the lowest possible levels to be able to retain the money inflow.

Broad Types of Loans:
Secured Loan: A secured loan is one which requires the applicant to submit a collateral with the bank, in exchange of the loan amount, till the tenure of the loan finishes. If the applicant keeps on defaulting his/her payments, the bank can seize the collateral in return. For example, a home loan requires collateral for most of the cases.
Unsecured Loan: An unsecured loan is one which does not require the applicant to submit any collateral. Generally unsecured loans have low sanctioned amounts. For example, a two-wheeler loan does not require any collateral.

Credit Default Definition:
In BFSI, a borrower is said to have defaulted, when he/she fails to make one or more scheduled payments for the loan they have taken. A default can occur on a secured loan or an unsecured loan. When the borrower of a secured loan defaults even after the grace period (period till when if applicant does not pay, the collateral can’t be seized, usually 4/5 months), the bank is liable to seize the collateral. On unsecured loans too, as per the agreement, there might be several severe consequences like the applicant might not get any loan in future from the bank or any other financial institutions (due to reporting with Credit Bureaus), or if the case is declared too significant, a lawsuit might also get registered against the applicant by the bank.
To address the problem of credit default, the bank relies on past behaviour data of the customers on the loans taken so far, with the bank and with other banks. 

Here comes the concept of Credit Bureaus.
Credit Bureaus:
Credit Bureaus are regulated organizations (TransUnion CIBIL, Equifax, Experian, and CRIF) TransUnion CIBIL, which officially collects, stores and shares information about banking borrowers and lenders. These credit bureaus also provide a ‘Credit Score’, which is based on their rules designed on top of the collected trades.
Banks and non-banking financial companies are bound by a periodic mandate to report all of the trades of its borrowers to the Credit Bureaus. Credit Bureaus then aggregate information from each institution and store it. When a bank places a request for information about any upcoming lender with the Credit Bureau, it will get consolidated information about this lender from all institutions. 
Why does the bank not make decisions directly on Credit Scores?
Banks want to use their internal expertise to build a mechanism, instead of relying on the credit scores from Credit Bureaus so as to stay ahead of the competition since all BFSI firms know credit scores of their customers and it is not a proprietary information. 

Other than bureau data, banks also leverage their internal information which they capture in the course of their digital journeys. For example, the customer’s demographic information  like age, location etc., is not provided by the bureaus, but banks themselves have these information available from the application form that the applicant fills. If the applicant is an existing customer of the bank and holds a salary account with the same bank, the bank could also use the very important estimated monthly salary that the applicant is drawing, and which firm does he/she work for. For existing to bank customers, bank also saves and utilizes behavioral and transaction level information on-the-go. Such information when clubbed with the bureau information would be much richer for model development, then only the bureau information.

For banks, there is a constant trade-off between acquiring new customers and managing risk effectively. When a bank is too strict in their risk assessment, they may struggle to gain new customers, and conversely, if they are too lenient, they risk taking on too much risk. For each product, the bank’s business teams design their own strategies, on how much risk they can withstand. Based on this, for each product, the bank designs its own bad definition (example customers who missed 3 payments could be considered bad for the model development of one product, while for a stricter product, missing even 1 payment can be considered as a bad). 

With this information, let’s move to the next section and discuss the actual problem statement in the next segment.
