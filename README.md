# Phishing-Indicators-Report
This project analyzes a phishing email sample, identifying key red flags such as fake sender domains, urgency tactics, and suspicious links, to help improve phishing detection awareness.



## Email Overview
1. Sender: Captialone@update-win.com
2. Subject: Credit One Breach Information
3. Claim: Urgent breach alert about Capital One account.

## Identified Phishing Characteristics  
The sender is listed as Captialone@update-win.com.

✅ Red flag:
Domain update-win.com has no relation to the legitimate capitalone.com domain.
Misspelling: “Captialone” instead of CapitalOne.

## Urgency & Fear Tactics
Subject line: “Breach Alert!!!”
Body text: Claims account suspension and urges immediate action.

✅ Red flag:
Classic phishing technique to trigger panic and bypass critical thinking.

## Suspicious Links
“Review your current staus online” → misspelled “staus”.
✅ Red flag:
Hovering over the link (if available) would likely show a non-Capital One domain.
Poor spelling is often a sign of phishing.


## Generic Greeting

No personalization; just “Re: Your Capital One profile changes”.
✅ Red flag:
Legitimate companies usually address you by name, especially in sensitive alerts.

## Mismatched Branding
Header says: Capital One.
Subject line says: Credit One Breach Information.

✅ Red flag:
Credit One and Capital One are two separate companies.
Phishers often mix brands, assuming users won’t notice.

## Spelling & Grammar Errors

Example: “staus” instead of status.
✅ Red flag:
Professional companies proofread their customer communications


## Unverified Links (Potentially Malicious)

Sign In and visit our Information Protection Center likely lead to phishing pages.
✅ Red flag:
URLs should always be verified; suspicious domains can harvest credentials.

## Tools You Can Use
✅ Use a free online header analyzer (e.g., MXToolbox, Google Admin Toolbox) to inspect full email headers for:
SPF/DKIM/DMARC failures.
Sender IP reputation.
Originating server.

✅ Paste suspicious links (without clicking) into:
VirusTotal URL scanner or
PhishTank to check if they’re flagged as phishing.


## Conclusion & Recommendation
This email exhibits multiple clear phishing signs.
✅ Do NOT click any links.
✅ Report the email to your email provider as phishing.
✅ Forward the email to Capital One’s phishing report address (abuse@capitalone.com) if you’re a customer.

