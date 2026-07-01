# AWS Day 02 – IAM Commands & Console Navigation

## AWS Console Navigation

AWS Console
→ IAM
→ Users
→ Create User

AWS Console
→ IAM
→ User Groups
→ Create Group

AWS Console
→ IAM
→ Policies
→ Create Policy

AWS Console
→ IAM
→ Roles

AWS Console
→ Account
→ Security Credentials
→ MFA

---

## AWS Managed Policy Used

AmazonS3ReadOnlyAccess

---

## Custom Policy Created

EC2ReadOnlyCustomPolicy

---

## JSON Policy Example

{
  "Version":"2012-10-17",
  "Statement":[
    {
      "Effect":"Allow",
      "Action":"ec2:Describe*",
      "Resource":"*"
    }
  ]
}

---

## Security Best Practices

- Enable MFA
- Avoid using Root User
- Follow Least Privilege
- Use IAM Roles instead of Access Keys
- Rotate credentials regularly