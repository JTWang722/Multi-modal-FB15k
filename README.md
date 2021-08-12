# Multi-modal-FB15k
Here is a multi-modal knowledge graph dataset based on FB15k. Hope it will be beneficial to multi-modal knowledge graph community.

I add visual modality to original FB15K dataset. There are 14,951 entities in total, each entity has up to 5 images.

To find the appropriate imgaes of each entity, I
- Link the entity to exsiting databases, including Wikidata and DBpedia. It's because the Freebase API has shut down, we only know the ID number of each entity, but can not figure out what it truly means. 
- Seek out the corresponding Wikipedia page and crawl down the images. 
- Filter out irrelevant images of each entity.

Please click at https://drive.google.com/file/d/16fMV4uzT1r82FANo0L1uipMr2rSQNFkP/view?usp=sharing to get this dataset.

If you want to know more detailed information, just email me at jtwang@seu.edu.cn~~

Have a good day!
