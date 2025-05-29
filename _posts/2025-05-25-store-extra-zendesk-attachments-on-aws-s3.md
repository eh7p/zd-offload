---
layout: post
description: 'Easily move Zendesk attachments to your AWS S3 bucket and access them through our Zendesk sidebar app. Secure, seamless, and affordable storage management.'
---

Have an AWS S3 account and want to store your Zendesk attachments there? Our solution enables you to offload Zendesk attachments directly to your AWS S3 bucket, while keeping them accessible in Zendesk through a convenient sidebar app.

---

As your company grows, so does your customer service, and with that, your Zendesk Storage demands. Once you exceed your Zendesk Storage allowance, you can be charged up to $60 for each 25GB block of additional storage, coming out to an extortionate rate of $2.4/GB. On top of that, even if you are only using 1GB over you need to pay for a full 25GB block of storage!

There are multiple ways to save on these fees, but our favourite is the [Zendesk Attachment Storage Offload](https://eh7p.com/zd-offload/) solution. The solution aims to be as transparent and frictionless as possible, replicating Zendesk storage as closely as possible. While other solutions can delete or export attachments, the offload solution moves attachments into external storage, but through the sidebar app agents can continue to view and access those offloaded attachments!

![Zendesk Offload Sidebar App]({{ site.baseurl }}/assets/img/side-app-big.png){:.shadow-md}

# Extract to AWS S3

You can easily connect up your AWS S3 bucket to be used as the storage backend for the Zendesk Storage Offload solution. 

The first step is to create a new bucket in your AWS account. Secondly, create credentials so we can connect to your bucket. Finally, insert the credentials when signing up to the solution. Now the extracted attachments will be stored on your AWS S3 account for long term storage and retrieval.

We seamlessly and securely connect between your Zendesk account, our processing servers, and your AWS S3 bucket, offloading attachments from Zendesk into your S3 bucket, and retrieving and displaying those attachments when requested through our sidebar app in the Zendesk interface.

Read more about the whole AWS S3 setup process in our tech guide here: [https://eh7p.com/zd-offload-docs/docs/bring-your-own-storage/aws-s3-storage](https://eh7p.com/zd-offload-docs/docs/bring-your-own-storage/aws-s3-storage.html)

## The cheapest way to manage excess attachments

Using S3 as part of our Hybrid solution can be the cheapest way to store your attachments, though does come with risks as you are in charge of maintaining the final storage destination for your attachments. Our cloud solution provides the quickest and easiest solution where we manage all storage for you.

Additionally, we support other storage solutions such as Microsoft Azure Storage, Google Cloud Storage, and others. Get in touch if you don't see what you need and we can work with you to make a bespoke connector!