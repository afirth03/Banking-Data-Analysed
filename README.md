# Data-Exam

Background
Business Domain
In the bustling UK financial landscape, a well-established bank provides multiple financial
services dedicated to individual customers. These services encompass a comprehensive suite
of offerings, including but not limited to managing various types of accounts, facilitating the
provision of loans, issuing credit cards tailored to different customer needs, and overseeing a
wide range of financial transactions.
Acknowledging the importance of data in driving effective, accurate, fair and transparent
decision-making, the CEO of the bank has established the Data Intelligence team, designating
you as its leader.
Aim: The Data Intelligence team is expected to implement a data science project and present its
main findings to the key stakeholders of the bank. These findings will serve as a cornerstone for
improving customer service and inform data-driven decision-making within the organisation, for
instance, to perform customer risk assessment and establish a customer retention scheme to
reward high-value and loyal customers.
Data Overview
The bank maintains records of its clients, including an identifier, birth number (a number based
on the date of birth, assigned by the bank), the residential city of the client, and a list of
demographic statistics of the city. The demographics include an identifier of the UK city (a1), city
name (a2), region of the city (a3), no. of inhabitants (a4), no. of municipalities with inhabitants
<500 (a5), no. of municipalities with inhabitants 500-1999 (a6), no. of municipalities with
inhabitants 2000-10000 (a7), no. of municipalities with inhabitants >10000 (a8), no. of cities in
the region (a9), ratio of urban inhabitants (a10), average salary (a11), unemployment rate 1995
(a12, a measure of the unemployed labour force in 1995), unemployment rate 1996 (a13, a
measure of the unemployed labour force in 1996), no. of entrepreneurs per 1000 inhabitants
(a14), no. of committed crimes in 1995 (a15), and no. of committed crimes in 1996 (a16).
Each client has one or more accounts, which serve as the primary repository for their financial
activities. The stored details include an account identifier, opted frequency of account
statements, and account creation date. These accounts facilitate transactions, standing payment
orders, loans, and other financial operations. An account is owned by a single individual as a
registered owner (called owner), but may also have another individual as a disponent owner1
(called disponent). The disposition details are stored with a disposition identifier that links a client
(via client identifier) with an account (account identifier) and the type of disposition (whether
owner or disponent).A client can perform various types of transactions using their account. Each transaction captures
essential details, providing a comprehensive overview of the financial activities within the bank.
The recorded details include a transaction identifier that enables tracking and management of
individual transactions, an identifier of the account performing the transaction, date of
occurrence, type of transaction, nature of financial operation carried out, transaction amount,
remaining balance, detailed characterisation of the transaction, bank of the partner involved in
the transaction, and account of the partner involved in the transaction. The transaction details
form a crucial component of the bank’s database, providing critical insights into the financial
health and operational dynamics of the institution.
A client can also initiate a permanent standing order using their account. The bank keeps a
record of all the initiated orders. Each record holds details related to the processing of payment
orders. These include an order identifier enabling their systematic tracking, the identifier of the
account that initiated the respective order, the recipient bank involved in the payment order, the
recipient account to which the payment is to be made, the amount of the order, and the payment
type characterising the nature of the payment.
Furthermore, the bank offers loans to eligible clients based on predetermined criteria. The bank
maintains a record of all approved loans, including a loan identifier, an identifier of the account
associated with the loan, approval date, amount approved, duration, monthly payments, and loan
status.
The bank also issues credit cards to clients, enabling them to make purchases and access credit
within predefined limits. The credit card usage is closely linked to the clients’ financial behaviour
and creditworthiness. In this regard, the bank stores a credit card identifier, a disposition
identifier to which the card is issued, its type (gold, classic, or junior), and its issue date.
