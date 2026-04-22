# Thunderbird-Issue-2nd-Occurrence

User experienced another Thunderbird disconnect. Previous work on this [issue](https://github.com/ryanschmitt2/Thunderbird-Issues).

<h2>Skills and Tools: </h2>

-Remote Desktop (AnyDesk)\
-Domain knowledge of networking and security\
-Diagnostic and verification skills\
-User communication and customer-service skills\
-Structured troubleshooting methodology

<h2>Initial Information: </h2>

User reached out again to report the same issue occurring as before. Another failed connection from Thunderbird on initial startup. 

<img src="https://i.imgur.com/Y9LQ3zC.jpeg" height="30%" width="30%" alt="UDR7"/>

<h3>Identify the Problem: </h3>
Thunderbird once again failed to connect on startup. This suggests resetting the password is only a temporary fix, and there is an underlying issue.

<h3>Establish a Theory of Probable Cause: </h3>

1. <s>Credentials are being flagged by Comcast</s>
2. Thunderbird client is the problem. Check the saved account information to see if there is a mismatch or conflict. &#9989;


<h3>Test the Theory to Determine the Cause: </h3>

1. Contacted Comcast support on behalf of the customer and asked if the account was being security flagged for some reason. It was not.
2. Check Account Settings > Privacy & Security > Saved Passwords. There are several saved credentials here that are probably conflicting.

<h3>Establish a Plan of Action and Implement the Solution:</h3>

1. Backup Thunderbird user config. Config file saved locally and a cloud backup for redundancy.
2. Go to Account Settings > Privacy & Security > Saved Passwords.
3. Delete all current credentials.
4. Add the current and verified user credentials.
5. Close and restart Thunderbird.

<h3>Verify Full System Functionality and Preventative Measures: </h3>

Thunderbird once again has full access to the user's email. User is able to receive and send test emails. User is also still able to log into the comcast email web portal without issue. 

<h3>Document Findings, Actions, and Outcomes: </h3>

-Documentation (hi again!)\
-User is informed of the believed problem and solution. They have been told to avoid adding any new credentials without deleting the previous set to avoid this situation in the future.	
