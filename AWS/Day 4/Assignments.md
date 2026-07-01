# AWS Day 04 Assignment

## Q1. What is Amazon S3?

Amazon S3 (Simple Storage Service) is an object storage service that allows users to securely store and retrieve any amount of data from anywhere.

---

## Q2. What is a Bucket?

A Bucket is a logical container used to store objects in Amazon S3. Bucket names must be globally unique.

---

## Q3. What is an Object?

An Object is a file stored inside an S3 bucket. It consists of the file data, metadata, and a unique key.

---

## Q4. Explain S3 Storage Classes.

S3 Standard:
Frequently accessed data.

S3 Intelligent-Tiering:
Automatically moves objects between access tiers.

S3 Standard-IA:
For infrequently accessed data.

S3 One Zone-IA:
Lower-cost storage in a single Availability Zone.

S3 Glacier Instant Retrieval:
Archive data with fast retrieval.

S3 Glacier Flexible Retrieval:
Long-term archival with flexible retrieval times.

S3 Glacier Deep Archive:
Lowest-cost storage for rarely accessed data.

---

## Q5. What is Versioning?

Versioning stores multiple versions of the same object, allowing recovery from accidental deletion or overwrites.

---

## Q6. What is a Lifecycle Rule?

Lifecycle Rules automatically transition or delete objects based on defined conditions to optimize storage costs.

---

## Q7. What is Static Website Hosting?

Static Website Hosting allows HTML, CSS, JavaScript, and images stored in S3 to be served as a website without a web server.

---

## Q8. Difference between IAM Policy and Bucket Policy.

IAM Policy:
Attached to users, groups, or roles.

Bucket Policy:
Attached directly to an S3 bucket and controls bucket access.

---

## Q9. Why must bucket names be globally unique?

Bucket names are globally unique because Amazon S3 uses a single global namespace for bucket names across all AWS accounts.

---

## Q10. Give three real-world use cases of Amazon S3.

- Website Hosting
- Backup and Disaster Recovery
- Image and Video Storage