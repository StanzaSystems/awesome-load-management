# Awesome Load Management

A repo of links to articles, papers, conference talks, and tooling related to load management in software services: loadshedding, circuitbreaking, quota management and throttling.
PRs welcome.

# Table of contents
  - [Loadshedding](#loadshedding)
  - [Fairness and Isolation](#fairness-and-isolation)
  - [Circuit Breaking and Adaptive Concurrency Control](#circuit-breaking-and-adaptive-concurrency-control)
  - [Quota Management and Ratelimiting](#quota-management-and-ratelimiting)


## Loadshedding

### Articles and Papers
 
 * [Handling Overload, from the Google SRE Book, by Alejandro Forero Cuervo and edited by Sarah Chavis](https://sre.google/sre-book/handling-overload/)
 * [Managing Load, from the Google SRE Workbook, by Cooper Bethea et al.](https://sre.google/workbook/managing-load/)
 * [Using load shedding to avoid overload, from the AWS Builders Library, by David Yanacek](https://aws.amazon.com/builders-library/using-load-shedding-to-avoid-overload/)
 * [Timeouts, Retries, Backoff, and Jitter, from  the AWS Builders Library, by Marc Brooker](https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/)
 * [FIFO Considered Harmful, by Jos Visser](https://medium.com/swlh/fifo-considered-harmful-793b76f98374)
 * [Using load shedding to survive a success disaster—CRE life lessons, from Google Cloud Blog, by Dave Rensin and Adrian Hilton](https://cloud.google.com/blog/products/gcp/using-load-shedding-to-survive-a-success-disaster-cre-life-lessons/)
 * [How to avoid a self-inflicted DDoS Attack—CRE life lessons, from Google Cloud Blog, by Dave Rensin and Adrian Hilton](https://cloud.google.com/blog/products/gcp/how-to-avoid-a-self-inflicted-ddos-attack-cre-life-lessons/)
 * [Keeping Netflix Reliable Using Prioritized Load Shedding, from the Netflix Tech Blog, by Manuel Correa, Arthur Gonigberg, and Daniel West](https://netflixtechblog.com/keeping-netflix-reliable-using-prioritized-load-shedding-6cc827b02f94)
 * [Why Disaster Happens at the Edges: An Introduction to Queue Theory, by Avishai Ish-Shalom](https://thenewstack.io/an-introduction-to-queue-theory-why-disaster-happens-at-the-edges/)
 * [Applying Back Pressure When Overloaded, by Martin Thompson](https://mechanical-sympathy.blogspot.com/2012/05/apply-back-pressure-when-overloaded.html)

### Videos

 * [Load Shedding—Approaches, Principles, Experiences, and Impact in Service Management
by Acacio Cruz, at SREcon EMEA 2016](https://www.usenix.org/conference/srecon16europe/program/presentation/cruz)
 * [Envoy, Take the Wheel: Real-time Adaptive Circuit Breaking, by Tony Allen, at KubeCon + CloudNativeCon Europe 2020](https://www.youtube.com/watch?v=CQvmSXlnyeQ)

## Fairness and Isolation

### Articles and Papers
 * [Amazon DynamoDB: A Scalable, Predictably Performant, and Fully Managed NoSQL Database Service, Mostafa Elhemali et al., Amazon Web Services](https://www.usenix.org/system/files/atc22-elhemali.pdf)
 * [Fairness in multi-tenant systems, from the AWS Builders Library, by David Yanacek](https://aws.amazon.com/builders-library/fairness-in-multi-tenant-systems/)

## Circuit Breaking and Adaptive Concurrency Control

### Articles and Papers

 * [Method overloading the circuit, Christopher Meiklejohn et al.](https://dl.acm.org/doi/pdf/10.1145/3542929.3563466)
 * [Service mesh circuit breaker: From panic button to performance management tool, by Mohammad Reza Saleh Sedghpour, Johan Tordsson](https://dl.acm.org/doi/abs/10.1145/3447851.3458740)
 * [Will circuit breakers solve my problems?, by Marc Brooker](https://brooker.co.za/blog/2022/02/16/circuit-breakers.html)
 * [Performance Under Load: Adaptive Concurrency Limits @ Netflix, by Eran Landau, William Thurston, Tim Bozarth](https://netflixtechblog.medium.com/performance-under-load-3e6fa9a60581)


## Quota Management and Ratelimiting

 * [Envoy Proxy Global Ratelimiting](https://www.envoyproxy.io/docs/envoy/latest/intro/arch_overview/other_features/global_rate_limiting)

