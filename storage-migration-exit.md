# Storage Decisions, Migrations, and Exit Strategy
One valuable tool for archives is the [NDSA Levels of Preservation](http://www.digitalpreservation.gov:8081/ndsa/working_groups/documents/NDSA_Levels_Archiving_2013.pdf). Below, the levels for Storage and Geographic Location are readable in a checklist format. If you are just getting started with digital preservation, understanding the key concepts embodied in the NDSA Levels of Preservation is a valid and valuable goal. Checking off any of the items is a step forward in improved digital preservation management. The levels are intended to be progressive, however your organization’s current actions are more informed when understanding their context within future commitments of an ongoing digital preservation plan.

> “Commitments made today are not commitments for all time. But actions must be taken today to ensure flexibility in the future” ([Blue Ribbon Task Force on Sustainable Digital Preservation and Access](http://brtf.sdsc.edu/biblio/BRTF_Final_Report.pdf), 2010, p. 5).

When archivists talk about preservation, we mean long term: decades turning into centuries. At the same time, we change these long-term, open-ended time spans into action-oriented, manageable timelines. You may not know the kind of storage and how much storage your organization will need in 10+ years. Since organizations often work on strategic planning cycles, [Jacob Nadal](http://www.jacobnadal.com/) recommends a digital preservation planning cycle length of: institutional [(strategic planning cycle) x 2] + 1 that is easier for organizations to conceptualize. At KBOO Community Radio, I [estimated storage needs](https://docs.google.com/spreadsheets/d/196C8ZJiRhqyIBS3iZxQvPc-HZfPE_DAg7wj7GtlpJ1E/edit) and our IT consultant estimated the cost for an enterprise network server and an external hard drive. I calculated the filesize of current digital audio assets, as well as estimated annual growth of newly digitized files so that the organization could understand how long it would take to fill up this space.

You may not have the luxury of a future archives budget or be in the position to know your organization’s digital preservation needs 10+ years out. But you can take steps to ensure that you have a centralized storage system now. 

***Level 1***  
__ Secure a storage system for your digital files.  
__ Determine all locations of your digital media (this includes optical discs and multiple hard drives). Consolidate the locations into your storage system.  
__ Secure a second storage location (backup) for your files that is not in the same physical location as your first storage location to avoid physical disaster risks. 

***Level 2***  
__ Make a third location for your digital files. Ensure one of the three copies is in a different geographic location. Are you able to join a consortium (MetaArchive, California Audiovisual Preservation Project) or go in on shared storage with your own partners for a less expensive option? Are you able to backup some or all of your files to archive.org or americanarchive.org? Note: you cannot submit materials that you do not hold rights to. How will you define a trustworthy repository and where to store your materials?  
__ Document details of your storage system(s), i.e. the make, model, type of backup and setup, i.e. is it a RAID system? What kind? What is the total storage capacity of your storage system? What do you need to use them?

***Level 3***  
__ Ensure one of the three copies is in a different geographic location with a different disaster threat (i.e. flood vs earthquake).  
__ The advancement of technology makes previous versions of technology obsolete. Make sure your storage system and your media formats do not become obsolete. Refer to the [Library of Congress’s Sustainability of Digital Formats](https://www.loc.gov/preservation/digital/formats/) resource and read documents from the information technology industry such as [BackBlaze’s Hard Drive Reliability](https://www.backblaze.com/blog/hard-drive-reliability-stats-q1-2016/) quarterly statistics. This may require a data migration or file format migration project. Stay up to date on the reliability, relevance, and performance of your storage system and media formats.

***Level 4***  
__ Ensure the location of your three copies of data each have different disaster threats.  
__ Create a comprehensive plan that will keep files and metadata on currently accessible media or systems

### Why have a migration and exit strategy?  
Selecting a storage system means selecting maintenance and upgrades of the storage into the future. If the services change and no longer meet your institution’s needs, if the cost for a service becomes prohibitive, or if the technology is failing, you may need to migrate your data to another storage system. For organizations considering network attached storage, [most findings about hard drives](https://www.storagecraft.com/blog/life-expectancy-nas-device/) show that their average lifespan is 3-5 years. For organizations considering linear-tape open (LTO), LTO tapes are read and write backwards compatible one generation, and read-only backwards compatible with two generations, meaning that you can read back LTO5 on LTO 7 drives, but you can’t write to LTO 5 tapes using our LTO 7 drive. [Read one archivist’s experience](http://ndsr.nycdigital.org/ltowoes/) migrating data from LTO 5 to LTO 7. Since [technology is always superseded by newer technology](http://www.dpworkshop.org/dpm-eng/oldmedia/obsolescence1.html), data migration becomes necessary storage system maintenance responsibilities, and should be included in digital preservation budgets. [Exit Strategies and Techniques for Cloud-based Preservation Services](https://ipr16.organizers-congress.org/frontend/organizers/media/iPRES2016/_PDF/IPR16.Proceedings_4_Web_Broschuere_Link.pdf) Matthew 
. iPres 2016. (Proceedings p. 276-7/ PDF p. 139) discusses the need for an exit strategy when organizations use cloud-based preservation services, migrate to or from a cloud-hosted service. 

### What about cloud storage?  
Although [locally managed storage is less expensive over time](https://www.researchinformation.info/news/analysis-opinion/cloud-storage-answer-preservation including the staff knowledge and time required to maintain it, many organizations opt for cloud storage options. Bert Lyons of AVPreserve [warns](https://groups.google.com/forum/#!searchin/digital-curation/storage$20cloud$20network%7Csort:relevance/digital-curation/sulGo1-RDg8/zX-LpZPC26oJ):  “[cloud storage] services are rarely, almost never, explicitly intended for preservation. Their service models and user agreements bear this out, but this doesn't mean they are completely useless for these purposes…. Successful use of these services requires a thorough understanding of your collection and organization's requirements and a comprehensive infrastructure of policy and procedure to manage the application of the services.”

[Consider cloud storage](#considering-cloud-storage-read-these-primers) as it relates to security of the storage medium, integrity of the data you store (i.e. ensuring the file you save remains unchanged, options for detecting and repairing corrupted data, virus checking), and options for storage in multiple physical locations. AVPreserve has done some legwork with its [Cloud Storage Vendor Profiles](https://www.avpreserve.com/papers-and-presentations/cloud-storage-vendor-profiles/). Solely taking a vendor’s sales pitch at its word is not enough to ensure the safety of your digital assets. Do your best to learn what it means to put content in one storage system--what is the exit strategy? If you need to move content, how long will it take to retrieve all your data, i.e. what is the given download speed for your amount of digital content? What kinds of important metadata will be bundled with your data? How will you check the integrity of the data?

> “Any third party solution is a preservation risk due to potential changes in support or the discontinuation of a product (or the discontinuation of a service provider). Preservation decisions are inherently risk management decisions — determining where trade offs are acceptable and where higher risks are allowed or lower risks are required” ([Ranger](https://www.avpreserve.com/blog/digital-preservation-is-people/), 2014).

Some cloud storage services are more preservation-friendly and offer the types of tools and monitoring that libraries and archives are keen on, at cost, i.e. Duracloud, Archivum, Preservica, and Chronopolis.

### Considering Cloud Storage? Read these primers:

Anderson, S. (2014). Feet on the ground: A practical approach to the cloud. Nine things to consider when assessing cloud storage. Retrieved from http://www.avpreserve.com/wp-content/uploads/2014/02/AssessingCloudStorage.pdf 

Toussaint, M. G. & Rounds, S. (2013). Report on digital preservation and cloud service. Retrieved from
http://www.mnhs.org/preserve/records/docs_pdfs/Instrumental_MHSReportFinal_Public_v2.pdf

### Additional Readings

Addis, M. (2016). Exit strategies and techniques for cloud-based preservation services. In *iPres 2016 Proceedings*. Paper presented at iPres 2016: 13th International Conference on Digital Preservation, Bern, Switzerland (Proceedings p. 276-7/ PDF p. 139). Retrieved from https://ipr16.organizers-congress.org/frontend/organizers/media/iPRES2016/_PDF/IPR16.Proceedings_4_Web_Broschuere_Link.pdf

Boyd, D. A. (2012). The digital mortgage: digital preservation of oral history. In D. Boyd, S. Cohen, B. Rakerd, & D. Rehberger (Eds.), Oral history in the digital age. Institute of Library and Museum Services. Retrieved from http://ohda.matrix.msu.edu/2012/06/the-digital-mortgage/. 

Beagrie, N., Charlesworth, A., & Miller P. (2014). How cloud storage can address the needs of public archives in the UK. Retrieved from http://www.nationalarchives.gov.uk/documents/archives/cloud-storage-guidance.pdf 

Blue Ribbon Task Force on Sustainable Digital Preservation and Access. (2010). Sustainable Economics for a Digital Planet. Retrieved from http://brtf.sdsc.edu/biblio/BRTF_Final_Report.pdf 

Digital Preservation Coalition (n.d.). Storage. Retrieved from http://www.dpconline.org/handbook/organisational-activities/storage

Library of Congress. (2016). Designing storage architectures for digital collections 2016. Retrieved from http://www.digitalpreservation.gov/meetings/storage16.html 
*The DSA meeting brings together technical and industry experts; LC IT and subject matter experts; government specialists with an interest in preservation; decision-makers from a wide range of organizations with digital preservation requirements; and recognized authorities and practitioners of digital preservation. This meeting is by invitation only however presentation slides and the meeting’s background reading lists are available online from past meetings 2009-2016.

Henriksen, S. L., Seuskens, W., & Wijers G.  (2013). Best practices for a digital storage infrastructure for the long-term preservation of digital files. Retrieved from:
http://www.dca-project.eu/images/uploads/banners/DCA_D62_Best_practices_for_a_digital_storage_infrastructure_20130506_Version1.pdf 

Nguyen, Q. (2011). Digital preservation cloud services for libraries and archives [Powerpoint slides]. Retrieved from https://www.diglib.org/forums/2011forum/schedule/digital-preservation-cloud-services-for-libraries-and-archives/ 

Ranger, G. (2014). Digital preservation is people. Retrieved from https://www.avpreserve.com/blog/digital-preservation-is-people 

Sims Recycling Solutions. (2013). Data centers: The life cycle of a server. Retrieved from http://www.techrepublic.com/blog/data-center/infographic-the-life-cycle-of-a-server/ 


