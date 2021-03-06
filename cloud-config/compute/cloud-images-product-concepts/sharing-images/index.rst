.. _cloud-images-sharing:

^^^^^^^^^^^^^^
Sharing images
^^^^^^^^^^^^^^
Cloud images can be created as snapshots of a cloud server. They can
also be imported using the Cloud Images Import feature.

No matter how you create an image, you can share it from one
Rackspace cloud account to another, on an on-demand basis. This can be
useful for many scenarios:

* Share an image of a new server you have created or customized to a
  colleague for testing and comments.

* If you have multiple cloud accounts at Rackspace, for example to
  support different internal organizations or company branches, you can
  create a single central image and then share it with other accounts
  so they do not have to create one themselves.

An image producer is also called an image owner. An image owner can
share an image with one or more image consumers.

An image consumer is also called an image member.

A shared image is an image that an image owner has made available to one
or more image members.

Exporting shared images
-----------------------
If a consumer has created a cloud server image/snapshot from a shared
image, they should consider the following concerns if they choose to
export that image:

* The image should not contain software not intended to be distributed
  beyond the image producer and consumer.

* The image will be subject to any limitations on image export that
  already exist within Rackspace (for example, Windows Server images
  may not be able to be exported).

Preparing to share an image
'''''''''''''''''''''''''''
Before you can share an image to one (or more) users, you will need to
complete some preparatory steps:

1. Create a snapshot of a cloud server, or import an image that you will
   be sharing.

2. Obtain the UUID (also known as *image ID*) of the image that you will
   be sharing. The UUID is available from the API or 
   the Cloud Control Panel.

3. Gather the tenant ID(s) (also known as *DDI* or *customer number*) of
   the consumer(s) to whom you will be sharing. This is a numeric ID
   that the consumer can find in their Cloud Control Panel or using their API.
   
   .. NOTE::
      The target consumer must provide their tenant ID to you; 
      you cannot search, browse, or otherwise discover 
      their unique ID.

Offering to share an image
''''''''''''''''''''''''''
Once the image producer has the proper information, the sharing process
is very straightforward.

1. The image producer uses the API or tools to issue the image share
   request to one or more image consumers.

2. The image consumer uses the API or tools to either accept or reject
   the image, determining whether the image
   will be available in their image
   list (their "member status").

The image producer repeats this process for each additional image and
for each additional consumer that needs to be added as a member to each
image.

Removing members from a shared image
''''''''''''''''''''''''''''''''''''
An image can have some or all of its members removed using the API or
tools. The image producer has complete control over this action, and is
the only one that can delete members from the image.

Any members that *rejected* the share request are technically still
members, even though they will not have visibility or access to the
image. The image producer can and should delete these members from the
image if they no longer have reason to be included.




.. toctree:: :hidden:
   :maxdepth: 2

   models
   planning
   support
