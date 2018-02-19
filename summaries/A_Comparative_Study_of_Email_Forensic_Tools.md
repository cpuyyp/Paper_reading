# A Comparative Study of Email Forensic Tools

## Outline
This paper compares and evaluates some previous research work.
In this paper, 5 popular email forensic tools are examined, including MainXaminer, Add4Mail, Digital Forensic Framework, eMailTrackerPro, and Paraben Email Examiner.

## Background Knowledge
An email has header and body.
Important information of an email: the recipient name or identity, the path between the sender and the recipient used for transporting the email, the client-side application used to compose the email, the timestamp when a message was generated, a unique message ID, etc.

### What are in header?
- Received
- From and To
- user-agent: shows the client side application used to compose the email.
- Multipurpose Internet Mail Extensions (MIME) version
- ContentDisposition: indicates the presentation style. Inline means that the message should be automatically displayed (as text also indicated by the content-type) and no attachment is present.
- X-Originating-IP: the source IP address where the email was originated from.
- Date
- message id: an automatically generated id where the timestamp information is present along with sender account information.
- X-HE-Spam-Level contains: the spam score computed at the client side.
- Status: see http://www.faqs.org/rfcs/rfc2076.html for details. For example, R means message is read or downloaded, and O means message is old but not deleted.
- Content-Length: in bytes.

##  Comparison based on nine criteria
Input file in disk, search option, information provided, recovery capability, format supported, visualization format supported, operating system supported, export format, and extended device support.

## Conclusion
Each software has its own pros and cons. Further research includes runtime performance (CPU, memory) and compatibility issue on working with other tools.

## Comments
More focus on software capacity but not how to design the detecting algorithm?
