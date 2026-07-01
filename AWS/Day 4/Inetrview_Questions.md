# AWS Day 04 Interview Questions

## Theory Questions

1. What is Amazon S3?
2. What is a Bucket?
3. What is an Object?
4. Explain S3 Storage Classes.
5. What is Versioning?
6. What is Lifecycle Management?
7. What is Static Website Hosting?
8. Difference between IAM Policy and Bucket Policy.
9. Why are bucket names globally unique?
10. What is Object Metadata?
11. What is Glacier?
12. Explain Intelligent Tiering.
13. What is S3 Standard?
14. Can S3 host dynamic websites?
15. What is Object Lock?
16. What is Replication?
17. What is Bucket Versioning?
18. What is Public Access Block?
19. How secure is Amazon S3?
20. Why is Amazon S3 important?

20 Scenario-Based Interview Questions with Answers

1. Your company's website contains only HTML, CSS, JavaScript, and images. Which AWS service would you recommend?

Answer: Amazon S3 Static Website Hosting because it is simple, scalable, and cost-effective for static websites.

2. A developer accidentally overwrites index.html. How can you recover the previous version?

Answer: Enable Versioning and restore the earlier version of the object.

3. Your manager wants old backup files automatically moved to cheaper storage after 30 days. What feature would you use?

Answer: S3 Lifecycle Rules.

4. Your S3 website returns "Access Denied." What should you check?

Answer:

Bucket Policy
Public Access Block settings
Object permissions
Static Website Hosting configuration
Index document name
5. Why shouldn't you make every S3 bucket public?

Answer: Public buckets can expose sensitive data. Only buckets intended for public content, such as static websites, should allow public read access.

Practice Questions (6–20)

6. When would you use Glacier instead of S3 Standard?
7. How would you securely share a private file stored in S3?
8. Why are bucket names globally unique?
9. What happens if Versioning is disabled after being enabled?
10. How would you reduce storage costs for old log files?
11. When would you use Intelligent-Tiering?
12. What is the difference between an object and a bucket?
13. Why can't S3 run PHP or Java applications?
14. What is the purpose of metadata in S3?
15. How would you host images for an EC2-hosted website?
16. What is the benefit of enabling Versioning before production deployment?
17. How would you prevent accidental deletion of important files?
18. When would you use a Bucket Policy instead of an IAM Policy?
19. How would you troubleshoot a missing image on an S3 website?
20. What AWS security best practices would you follow for S3?