# Class 16 Readings: Serverless Functions

## Reading

- [What is Serverless Computing?](https://www.ibm.com/cloud/learn/serverless)

## Additional Resources

- [venv - Creation of Virtual Environments](https://docs.python.org/3/library/venv.html)
- [Vercel - Get Started](https://vercel.com/docs/get-started)
- [Vercel - Get Started](https://pymotw.com/3/http.server/index.html)
- [Requests){:target=”_blank”}](https://requests.readthedocs.io/en/latest/)

## Videos

- [What is Serverless?](https://www.youtube.com/watch?v=vxJobGtqKVM)

## Bookmark and Review

- [Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions)
- [Effective Python Environment](https://realpython.com/effective-python-environment/)

## Reading Questions

1. What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?

    - **Provisioning time:** Measured in milliseconds for serverless, vs. minutes to hours for the other models.
    - **Administrative burden:** None for serverless, compared to a continuum from light to medium to heavy for PaaS, containers and VMs respectively.
    - **Maintenance:** Serverless architectures are managed 100% by the provider. The same is true for PaaS, but containers and VMs require significant maintenance including updating/managing operating systems, container images, connections, etc.
    - **Scaling:** Auto-scaling—including auto-scaling to zero—is instant and inherent for serverless. The other models offer automatic but slow scaling that requires careful tuning of auto-scaling rules, and no scaling to zero.
    - **Capacity planning:** None needed for serverless. The other models require a mix of some automatic scalability and some capacity planning.
    - **Statelessness:** Inherent for serverless, which means scalability is never a problem; state is maintained in an external service or resource. PaaS, containers and VMs can leverage HTTP, keep an open socket or connection for long periods of time, and store state in memory between calls.
    - **High availability (HA) and disaster recovery (DR):** Both are inherent in serverless with no extra effort and at no additional cost. The other models require additional cost and management effort. In the case of both VMs and containers, infrastructure can be restarted automatically.
    - **Resource utilization:** Serverless is 100% efficient because there are no such things thing as idle capacity—it is invoked only upon request. All other models feature at least some degree of idle capacity.
    - **Billing granularity and savings:** Serverless is metered in units of 100 milliseconds. PaaS, containers and VMs are typically metered by the hour or the minute.

2. How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?

    - Sign-up for Vercel and connect your Git provider
    - Create a new project by importing your existing project or using a template
    - deploy:

        - develop
        - preview
        - ship

3. What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?

4. What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?