Images for Rackspace Cloud Core Infrastructure Services User Guide
=======================================================================
All images must reside in this *_images* directory.

"All images" includes:

* Figures

Figures are drawings related to an idea discussed 
in the text. The drawings show how things work conceptually but 
not procedurally. Figures visually explain a concept.

*Use the figure directive to include figures; 
give each figure alternate text and a caption.*

* Logos

Logos represent a single word or phrase such as the  
the name of a product 

*Use the image directive to include logos; 
give each logo alternate text.*

* Screenshots

Screenshots show how a Cloud Control Panel session looks. 
Screenshots visually demonstrate a process 
or a portion of a process.

*Use the figure directive to include screenshots; 
give each screenshot alternate text and a caption.*

For everything stored in *_images*, 
use this *README* to maintain an inventory describing what we have, 
where we got it, and how we use it. 


----
To include any image in the guide:

* Save the image (probably of type .png) 
  in the *_images* directory 
  with a descriptive filename. "CloudServerCreation" 
  is a descriptive filename; "Image01" is not.

* On the page where you intend the image to appear, 
  at the location where you intend it to appear, 
  call for it from ``/_images/`` followed by its filename, 
  providing descriptive alternate text 
  so non-visual browsers can verbally summarize its meaning.
  
  If the image is a figure or a screenshot, 
  also provide an italicized caption.  
  Follow this model:

```
  .. figure:: /_images/screenshots/ExampleProcess.png
     :alt: Cloud Servers are awesome.
           If I say more than one line, 
           I indent.
           
     *Italicize a caption explaining the screenshot.*
```

* Update the inventory (below), connecting the image to 
  its intended use, its age, its source, and at least one human 
  responsible for it.
  Keep the inventory grouped by image type 
  (figures, logos, screenshots) 
  and alphabetized by filename within image type.

----
**Inventory of figures**

* **CloudImagesHandshaking.png**
  * used at /cloud-config/compute/cloud-images-product-concepts/sharing-images/models.html
  * source here, in CloudImagesHandshaking.xml; 
    to change the drawing, open the XML in https://www.draw.io/, 
    then export a new .PNG and save it here
  * collection date 2015-06-09
  * contributed by Nate Archer

* **CloudServerNetworkRemovalResults.png**
  * used at /cloud-config/network/cloud-networks-product-concepts/network-cloud-servers.html
  * source here, in CloudServerNetworkRemovalResults.xml; 
    to change the drawing, open the XML in https://www.draw.io/, 
    then export a new .PNG and save it here  
  * collection date 2015-06-08
  * contributed by Nate Archer
  
* **CloudServerOnMetalArchitecture.png**
  * used at /cloud-config/compute/cloud-servers-product-concepts/index.html
  * source here, in CloudServerOnMetalArchitecture.xml; 
    to change the drawing, open the XML in https://www.draw.io/, 
    then export a new .PNG and save it here 
  * collection date 2015-06-05
  * contributed by Nate Archer

* **CloudServerVirtualArchitecture.png**
  * used at /cloud-config/compute/cloud-servers-product-concepts/index.html
  * source here, in CloudServerVirtualArchitecture.xml; 
    to change the drawing, open the XML in https://www.draw.io/, 
    then export a new .PNG and save it here 
  * collection date 2015-06-05
  * contributed by Nate Archer
  
* **core-infrastructure.png**
  * used at /cloud-intro/core-infrastructure.html
  * source here, in core-infrastructure.xml; 
    to change the drawing, open the XML in https://www.draw.io/, 
    then export a new .PNG and save it here
  * collection date 2015-06-04
  * contributed by Nate Archer

* **RackConnectEnterpriseConfig.png**
  * used at /cloud-config/network/cloud-networks-product-concepts/network-rackconnect.html
  * source here, in RackConnectEnterpriseConfig.xml; 
    to change the drawing, open the XML in https://www.draw.io/, 
    then export a new .PNG and save it here
  * collection date 2015-06-12
  * contributed by Nate Archer
  

----
**Inventory of logos**

* **logo-cloudblockstorage-50x50.png**
  * used at /index.html
  * original size here, logo-cloudblockstorage.png;
    resized to 50px x 50px with SnagIt Editor
  * collection date 2015-06-07
  * original from Lane Fielder, resized by Rose Coste
  
* **logo-cloudimages-50x50.png**
  * used at /index.html
  * original size here, logo-cloudimages.png;
    resized to 50px x 50px with SnagIt Editor
  * collection date 2015-06-07
  * original from Lane Fielder, resized by Rose Coste
  
* **logo-cloudnetworks-50x50.png**
  * used at /index.html
  * original size here, logo-cloudnetworks.png;
    resized to 50px x 50px with SnagIt Editor
  * collection date 2015-06-07
  * original from Lane Fielder, resized by Rose Coste
  
* **logo-cloudservers-50x50.png**
  * used at /index.html
  * original size here, logo-cloudservers.png;
    resized to 50px x 50px with SnagIt Editor
  * collection date 2015-06-07
  * original from Lane Fielder, resized by Rose Coste

----
**Inventory of screenshots**

* **AccountResourceLimits.png** 
  * used at /cloud-interfaces/gui/index.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-18
  * contributed by Rose Coste

* **ChromeViewDeveloper.png** 
  * used at /cloud-interfaces/api/cloudservers-api.html
  * used at /cloud-interfaces/api/cloudnetworks-api.html
  * used at /cloud-interfaces/api/cloudimages-api.html
  * used at /cloud-interfaces/api/cloudblockstorage-api.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-15
  * contributed by Rose Coste
  
* **CloudBigData0clusters.png** 
  * used at /cloud-ops/somethingnew.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-19 
  * contributed by Rose Coste

* **CloudBlockStorage0volumes.png** 
  * used at /cloud-interfaces/api/cloud.rackspace.com/ 
  * collection date 2015-04-30
  * contributed by Rose Coste
  
* **CloudBlockStorage1volume.png** 
  * used at /cloud-interfaces/api/cloudblockstorage-api.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-04-30
  * contributed by Rose Coste
  
 * **CloudBlockStorageListVolumesGET.png** 
  * used at /cloud-interfaces/api/cloudblockstorage-api.html
  * collected from http://api.rackspace.com/ 
  * collection date 2015-04-30
  * contributed by Rose Coste 

* **CloudBlockStorageSDKPHP.png** 
  * used at /cloud-interfaces/api/cloudblockstorage-api.html
  * collected from https://developer.rackspace.com/docs/cloud-block-storage/getting-started/ 
  * collection date 2015-04-30
  * contributed by Rose Coste

* **CloudDNSAddReverse.png** 
  * used at /cloud-config/network/cloud-networks-product-concepts/dns.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-06-16 
  * contributed by Rose Coste 
  
* **CloudDNSAddReverseDetails.png** 
  * used at /cloud-config/network/cloud-networks-product-concepts/dns.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-06-16
  * contributed by Rose Coste 
  
* **CloudDNSCreateDomain.png** 
  * used at /cloud-config/network/cloud-networks-product-concepts/dns.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-03-01 
  * contributed by Rose Coste
  
* **CloudImagesListAll.png** 
  * used at /cloud-interfaces/api/cloudimages-api.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-11
  * contributed by Rose Coste 
  
* **CloudImagesListImagesGET.png** 
  * used at /cloud-interfaces/api/cloudimages-api.html
  * collected from http://api.rackspace.com/ 
  * collection date 2015-05-11
  * contributed by Rose Coste 
  
* **CloudImagesSDKpython.png** 
  * used at /cloud-interfaces/api/cloudimages-api.html
  * collected from https://developer.rackspace.com/docs/cloud-images/getting-started/ 
  * collection date 2015-05-11
  * contributed by Rose Coste 
  
* **CloudNetworksListAll.png** 
  * used at /cloud-interfaces/api/cloudnetworks-api.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-07
  * contributed by Rose Coste 
  
* **CloudNetworksListNetworksGET.png** 
  * used at /cloud-interfaces/api/cloudnetworks-api.html
  * collected from http://api.rackspace.com/ 
  * collection date 2015-05-07
  * contributed by Rose Coste 
  
* **CloudNetworksSDKjava.png** 
  * used at /cloud-interfaces/api/cloudnetworks-api.html
  * collected from https://developer.rackspace.com/docs/cloud-networks/getting-started/ 
  * collection date 2015-05-07
  * contributed by Rose Coste 
  
* **CloudOrchestrationRailsFlavors.png**
  * used at /cloud-preprod/stack.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-03-26
  * contributed by Rose Coste
  
* **CloudServerCreateFlavorStandardInstance.png**
  * used at /cloud-config/compute/cloud-servers-product-concepts/server-region.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-03-01
  * contributed by Rose Coste
  
* **CloudServerCreateImageUbuntu.png**
  * used at /cloud-config/compute/cloud-servers-product-concepts/server-region.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-03-01
  * contributed by Rose Coste 

* **CloudServerCreateOnMetal.png** 
  * used at /cloud-config/compute/cloud-servers-product-concepts/flavor-class/index.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-03-01
  * contributed by Rose Coste
  
* **CloudServerCreateRegionDFW.png**
  * used at /cloud-config/compute/cloud-servers-product-concepts/server-region.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-03-01
  * contributed by Rose Coste  
  
* **CloudServerCreateVirtual.png** 
  * used at /cloud-config/compute/cloud-servers-product-concepts/flavor-class/index.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-03-01
  * contributed by Rose Coste
  
* **CloudServersListAll.png** 
  * used at /cloud-interfaces/api/cloudservers-api.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-04-28
  * contributed by Rose Coste
  
* **CloudServersListServersGET.png** 
  * used at /cloud-interfaces/api/cloudservers-api.html
  * collected from http://api.rackspace.com/ 
  * collection date 2015-04-29
  * contributed by Rose Coste

* **CloudServersSDKpython.png** 
  * used at /cloud-interfaces/api/cloudservers-api.html
  * collected from https://developer.rackspace.com/docs/cloud-servers/getting-started/ 
  * collection date 2015-04-28
  * contributed by Rose Coste

* **CreateTicketServersResourceLimit.png** 
  * used at /cloud-interfaces/gui/index.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-18
  * contributed by Rose Coste
  

* **flavorclass-network-speed.png**
  * used at /cloud-config/network/cloud-networks-product-concepts/network-cloud-servers.html
  * collected from https://mycloud.rackspace.com/
  * collection date 2015-06-16
  * contributed by Rose Coste

* **NetworkingGroup.png** 
  * used at /cloud-interfaces/gui/cloudnetworks-gui.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-13
  * contributed by Rose Coste
  
* **NetworkingNetworks.png** 
  * used at /cloud-interfaces/api/cloudnetworks-api.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-07
  * contributed by Rose Coste  
  
* **quickstart-shell.png** 
  * used at /cloud-interfaces/cli/curl.html
  * collected from https://developer.rackspace.com/docs/cloud-block-storage/getting-started/ 
  * collection date 2015-05-26
  * contributed by Rose Coste
  
* **ReleaseNotesFeed-api.png** 
  * used at /cloud-interfaces/api/moreinfo-api.html
  * collected from http://docs.rackspace.com/cbs/api/v1.0/cbs-releasenotes/ 
  * collection date 2015-05-19
  * contributed by Rose Coste 

* **ReleaseNotesFeed-SDK.png** 
  * used at /cloud-interfaces/api/moreinfo-api.html
  * collected from https://developer.rackspace.com/sdks/ 
  * collection date 2015-05-19
  * contributed by Rose Coste 

* **ServersGroup.png** 
  * used at /cloud-interfaces/api/cloudimages-api.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-12
  * contributed by Rose Coste 
  
* **ServersSavedImages.png** 
  * used at /cloud-interfaces/gui/cloudservers-gui.html
  * used at /cloud-interfaces/gui/cloudimages-gui.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-12
  * contributed by Rose Coste 
  
* **StorageGroup.png** 
  * used at /cloud-interfaces/gui/cloudblockstorage-gui.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-05-13
  * contributed by Rose Coste

* **StorageBlockStorageVolumes.png** 
  * used at /cloud-interfaces/api/cloudblockstorage-api.html
  * collected from https://mycloud.rackspace.com/ 
  * collection date 2015-04-30
  * contributed by Rose Coste
