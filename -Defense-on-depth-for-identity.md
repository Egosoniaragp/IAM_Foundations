 # Defense in Depth. Applied to IAM
 
Layer 1 - Identity Layer: WHO are you?-> Password + MFA. If password leaked, MFA stops attacker.
Layer 2 - Device / Network Layer: WHERE are you logging from?-> Is laptop trusted? Is it company managed? If not, block even with correct password.
Layer 3 - Data / Compliance Layer: WHAT can you see?-> Even if you passed Layer 1 and 2, can you open this salary file? No, because of compliance policy.

If hacker steals password (Layer 1 fails), Layer 2 (untrusted device) and Layer 3 (no permission to file) still protect data. That is defense in depth.
This is why companies need both IAM (Layers 1+2) and GRC (Layer 3 - rules).
