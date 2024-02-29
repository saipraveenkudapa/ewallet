Digital – Wallet Project

The purpose of this document is to present a detailed description of the e-Wallet System and describe the files and code that has been developed for the same. This document is intended for both the stakeholders and the developers of the system.

This system will be an e-Wallet designed for use by the students of BITS Pilani, Goa Campus. The main objective is to provide the students/vendors at Bits Goa with a simple software that will enable easy, secure payment at all of the outlets available on campus and therefore facilitate a new technology-driven means by virtue of which, every student can do away with the burden of having to worry about carrying cash around campus for various needs.

Currently, some of the issues brought out by the students include the fact that they do not receive change in cash, on making purchases at most outlets on campus. Added to this is the problem of most students having to wait for a long time to get the bill settled after a small purchase. Even worse are scenarios where the outlet owners are robbed of their money when the students manage to get away without payment when there is a huge rush. The e-Wallet system has the potential to solve all of these issues if implemented across campus.

Currently, the system is designed for usage only by students of Bits Goa. Further additions could be made to the system to make this facility available to any on-campus resident, say, staff members, wardens, hostel assistants, etc.


The software component that handles the payment and associated data and provides the user( in our case, a student) with options to make payments, recharge and avail loyalty benefits provided by the vendors.

* Database
Collection of all the information, i.e., payment logs, credit balances and dues, account balances and registered student information is monitored by this system.

* Vendor
Person/outlet on campus who(which) receives the payment from the students when a purchase is made by them.
* Payment tracker
A system which facilitates the secure payment process by interacting with the student and the database and the vendor.

* Loyalty benefit
Special offers made by outlets on campus to students who make purchases from their outlets using the e-Wallet system.

* Logs
Refers to data that indicates the proceedings of various transactions between the student and the vendor. In a way, they behave as a sort of proof of payment.

* Account
Refers to the unique account maintained for each registered student which comprises a security pin, balance amounts, unique name and id.

* Recharge
Recharge here, is used to refer to the transfer/translation of money from the student’s swd-account to e-Wallet cash, which the student can use at the various on-campus outlets.

* User
The term user has been used along with the term Student in this document. In all cases both terms refer to a student as described above.


