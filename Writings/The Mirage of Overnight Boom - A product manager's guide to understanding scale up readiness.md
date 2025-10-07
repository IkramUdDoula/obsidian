“So, are we ready for 1,000,000 users?”

If you’re a product manager, you’ve likely heard some version of this question where stakeholders are wondering whether the system can handle a massive user base.

Here are some of my personal observations on how to approach this question, so you can confidently determine the answer yourself.

1. Handling a million users is not primarily a technical concern, but a business one. It’s highly unlikely that a business will suddenly see that level of traffic overnight. Here’s a small tip. If you ever find yourself asked about handling that kind of scale, go to the person leading day-to-day operations and ask them if they’re prepared. If it is not their headache at the moment, you don’t need to worry about it either. The point being, scale follows business growth, not the other way around. Planning for theoretical extremes before the business is ready is often unnecessary.
    
2. Most of the non-technical stakeholders you interact with think of scaling up as **enlargement**, instead of **extension**. Imagine you’re trying to store some rainwater since it’s been raining cats and dogs for a few days. You can either buy a **giant water tank**, or you can buy 10 small buckets and keep adding new ones as they fill up. Now buying a giant tank may seem practical because you want to save as much water as you can, but it’s not always realistic because the rain might stop the moment you set up the tank, and you’ll end up with a huge, underused investment. But if you keep extending your army of small buckets, you’ll have a more flexible and optimized system that grows with the rain instead of guessing how long it’ll last. Of course, managing a lot of small buckets isn’t free of challenges. You’ll need to monitor them, make sure none overflow, and spend more time organizing them. But this trade-off brings resilience and adaptability.
    
3. There are times, however, when you do need to be ready for a sudden jump in traffic. These cases are well documented, studied, and solved. The idea is that preparation should be guided by business signals, not hypothetical fears. Your business should meet certain criteria before worrying about traffic surges.
    
    - Is the product targeted to the B2C segment?
        
    - Does the company practice product-led growth?
        
    - Have competitors ever experienced a similar influx?
        
    - Do you see people lining up in front of your office to use your product?
        
    - Is there significant media coverage or press attention expected?
        
    - Has a similar product gone viral on social or digital platforms before?
        
    - Can giants like OpenAI, Meta, or Google launch a feature to thanos-snap your business overnight?  
    
    If you have answered yes to all of those questions except for the last one, you better start sending emails to Amazon or Microsoft. Otherwise, relax and focus on how you are going to create more value for the users.
        
4. Every technical decision must align with business goals. For instance, if the company’s only objective is to acquire 20% more customers in the next quarter, then every line of code, PRD, Jira ticket, and even every single email should contribute toward that target, or else you risk wasting time and resources. Now, some tasks, like managing technical debt, ensuring security, or optimizing performance, may not directly impact that specific goal. But they still support the broader objective by safeguarding the business’s sustainability and long-term health. So if you are asked to prepare for scale-up readiness, make sure you understand which business goal it serves.
    
5. Product managers are shared resources, 50% for the company and 50% for the customers. You need to advocate for the users you are shipping your products to. It is one of the key characteristics that differentiate product managers from backlog managers. Whenever you are asked to build a feature or take on a task, ask yourself two questions. What does this do for the business? What does it do to the customers? You need to find a Yin & Yang kind of balance here. The amount of effort and money it needs to build a system robust enough to handle a million users will stab you in the back if you are not thinking about the user experience around your product. Remember Skype? Skype was supposedly ready to handle three pandemics. Now, if you Google "Skype," you will see ads for Microsoft Teams (ironic, right?).
    

These are the lessons I’ve learned from working with a diverse group stakeholders, customers, and supervisors. See, I’m not here to tell you exactly how to manage your products. That’s not something I do for free. But the key takeaway is to gather enough justification before you spend time diving into AWS pricing pages. And let me warn you, there’s no AWS pricing page, figuratively speaking.

So the answer to the question is: “Yes, I am ready. Are you?”