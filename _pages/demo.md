---
layout: page
title: Demo
---

During normal agent interaction, tickets are unaffected with attachments showing normally under each ticket comment.

![Image]({{ site.baseurl }}assets/img/demo/ticket_standard.png){: .shadow-md}

In the dashboard, you can setup the parameters for offloading. 
{: .pb-0 .mb-0 }
For this setup, once a ticket is closed for 30 days, and there is more than 50GB in Zendesk Storage, the attachments will be offloaded.
{: .text-sm .text-gray-400 .mt-0 .pt-0}

![Image]({{ site.baseurl }}assets/img/demo/dashboard.png){: .shadow-md}

Once offloaded, the attachments are redacted but can easily be accessed from the sidebar app.

![Image]({{ site.baseurl }}assets/img/demo/ticket_offloaded.png){: .shadow-md}