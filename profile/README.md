# welcome to my demo project

This organization serves as the project space for my exploration into building a "production-ready application" from 
end to end. The goal was to create a small, simple service and deploy it.

Although I have professional experience with Docker, Terraform, and various AWS services, much of that was done as part 
of a team where responsibilities were divided. I had not personally owned the entire deployment lifecycle. This project 
provides me with an opportunity to fill those gaps and deepen my understanding by seeing code deployed live in the 
cloud.

The service itself exposes a few basic endpoints that serve no real business purpose other than to be hit and simulate 
traffic. Using GitHub Actions and local testing, I was able to build a Docker image, push it to AWS Elastic Container 
Registry (ECR), and deploy it on AWS Elastic Kubernetes Service (EKS).

To make the service more realistic and incorporate more data and metrics which I love, I added metrics to the endpoints 
and set up Prometheus scraping with Grafana dashboards to monitor throughput, latency, and error rates.

I also explored creating and managing AWS resources with Terraform and service accounts, which reinforced the 
importance of Infrastructure as Code to make deployment repeatable and consistent.