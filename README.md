## EXP-4 : AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL

### Name : SHERLIN JENIFA VS
### Reg No : 212225230263

## Activity-audit

**Step 1: Login to AWS**

1.	Open the AWS Management Console. 
2.	Sign in using your AWS account. 
3.	Search for S3. 
4.	Select Amazon S3. 

**Step 2: Select the S3 Bucket**

1.	Click Buckets. 
2.	Select the S3 bucket created in the previous experiment. 
3.	Record: 
o	Bucket name 
o	AWS Region 
o	Number/type of objects 
S3 bucket overview.:

<img width="1717" height="834" alt="image" src="https://github.com/user-attachments/assets/37675c8b-de14-48aa-b3fd-21b262e4912b" />


**Step 3: Check Block Public Access**

1.	Open the S3 bucket. 
2.	Select Permissions. 
3.	Locate Block public access (bucket settings). 
4.	Check Block all public access.
5.	
Record:
•	ON → Secure configuration 
•	OFF → Potential public-access risk
 Block Public Access settings:

<img width="1571" height="759" alt="Screenshot 2026-09-11 160036" src="https://github.com/user-attachments/assets/d8cb71c1-b36c-4003-a0b3-eeadf76ac2cb" />


<img width="1668" height="779" alt="Screenshot 2026-09-11 160205" src="https://github.com/user-attachments/assets/f5682c19-a4ad-4d82-a32b-2a1c64e4fbcc" />


**Step 4: Check Bucket Versioning**

1.	Select the Properties tab. 
2.	Locate Bucket Versioning.
3.	 
4.	Record whether it is: 
o	Enabled 
o	Disabled

Security purpose

Versioning helps recover previous versions of objects after accidental deletion or modification.
Bucket Versioning:

<img width="1595" height="784" alt="Screenshot 2026-09-11 160400" src="https://github.com/user-attachments/assets/349d1941-34a6-4f18-b1a4-c0164ab6b2f7" />



**Step 5: Check Default Encryption**

1.	Stay in the Properties tab. 
2.	Locate Default encryption. 
3.	Record the encryption type.

Possible configurations include:
•	SSE-S3 
•	SSE-KMS 
•	DSSE-KMS 

Security purpose
Encryption protects stored data from unauthorized disclosure.

Default Encryption:


<img width="1584" height="781" alt="Screenshot 2026-09-11 160743" src="https://github.com/user-attachments/assets/5d267b4c-a465-4e41-991c-35786d762c0e" />



**Step 6: Check Bucket Policy**

1.	Select Permissions. 
2.	Locate Bucket policy. 
3.	Check whether a bucket policy exists.
    
Record:
•	Policy exists 
•	No policy 

Note
A missing bucket policy is not automatically a vulnerability. Access may be controlled through IAM and other AWS security mechanisms.
 Bucket Policy section:

<img width="1668" height="835" alt="Screenshot 2026-09-11 161536" src="https://github.com/user-attachments/assets/9e5391c7-6d58-4f71-ab1e-19b778189918" />




**Step 7: Check Object Ownership and ACL**

1.	In Permissions, locate Object Ownership. 
2.	Record the current configuration.

A common secure configuration is:
Bucket owner enforced

This means:
•	ACLs are disabled. 
•	Objects are owned by the bucket owner. 
•	Access is controlled using policies.

Object Ownership:

<img width="1743" height="862" alt="Screenshot 2026-09-11 161741" src="https://github.com/user-attachments/assets/269e33b7-8159-4f55-8b59-e08fc52121be" />


**Step 8: Check Server Access Logging**

1.	Go to Properties. 
2.	Locate Server access logging.

4.	Record whether it is: 
o	Enabled 
o	Disabled
 
Security purpose
Logging helps investigate suspicious or unauthorized access to the bucket.

Server Access Logging:

<img width="1674" height="821" alt="Screenshot 2026-09-11 161904" src="https://github.com/user-attachments/assets/9f32aa44-3621-467d-83ad-6bb0dc1b8920" />


## RESULT :

Thus the experiment for auditing cloud activity using aws cloudtrail was executed successfully.

