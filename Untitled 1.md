---
noteID: 2952c7a7-fb6f-420d-8cc7-e52340d3e534
---

“So, are we ready for 1,000,000 users?”

If you’re a product manager, you’ve likely heard some version of this question from stakeholders wondering whether the system can handle a massive user base.

Here are some of my observations to help you approach this question and find the answer yourself.

1. Handling a million users is not primarily a technical concern but a business concern. It is unlikely that a business will suddenly see that level of traffic overnight. If you are asked about scale, go to the person leading day to day operations and ask if they are prepared. If it is not their immediate concern, it should not be yours either. Scale follows business growth, not the other way around. Planning for theoretical extremes too early is often unnecessary.
    
2. Most non-technical stakeholders think of scaling as **enlargement**, not **extension**. Imagine storing rainwater after heavy rain. You can buy a **giant tank** or 10 small buckets and keep adding more. The giant tank seems practical, but if the rain stops, it sits underused. Extending many small buckets creates a system that grows with the rain. Managing many buckets requires effort. You must monitor, prevent overflow, and organize them. The trade-off brings flexibility and resilience.
    
3. Sometimes, you do need to be ready for sudden traffic spikes. Preparation should follow business signals, not hypothetical fears. Ask:
    
    - Is the product B2C?
        
    - Does the company practice product-led growth?
        
    - Have competitors experienced a similar influx?
        
    - Are people lining up to use your product?
        
    - Is significant media coverage expected?
        
    - Has a similar product gone viral online?
        
    - Could giants like OpenAI, Meta, or Google disrupt your market overnight?
        

If you answer yes to all except the last, you might need to contact cloud providers. Otherwise, focus on delivering value to users.

4. Every technical decision must align with business goals. If the company’s objective is to acquire 20% more customers next quarter, every line of code, PRD, Jira ticket, and email should contribute to that target, or you risk wasting time. Tasks like managing technical debt, security, or performance may not directly impact that goal but still support business sustainability. If asked to prepare for scale-up readiness, understand which business goal it serves.
    
5. Product managers are shared resources, 50% for the company and 50% for the customers. Advocating for users differentiates product managers from backlog managers. When building a feature, ask: what does this do for the business, and what does it do for the customer? You need a Yin and Yang balance. Effort to support a million users can backfire if user experience is ignored. Remember Skype? It was ready for three pandemics, yet today Google shows ads for Microsoft Teams. Ironic, isn’t it?
    

These are lessons I’ve learned from working with diverse stakeholders, customers, and supervisors. I am not here to tell you exactly how to manage your products. That is not something I do for free. But the key takeaway is to gather enough justification before diving into AWS pricing pages. And let me warn you, there is no AWS pricing page, figuratively speaking.

So the answer to the original question is: **“Yes, I am ready. Are you?”**

---

If you want, I can also create a **tightened, 1,500-character version** that reads like a punchy book chapter without losing examples or humor. Do you want me to do that?