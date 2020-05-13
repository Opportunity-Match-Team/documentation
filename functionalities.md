# Functionalities

## Versions
* version 1  
    * Database with opportunity, expert, match, resource entities
    * Challenge and partner profile entry, update, deletion; authentication
    * Profile/challenge indexing, keyword-based search and browsing
    * Semantic matching using document embeddings
    * Partner profile import from PURE/ROAG and Covid19 UoE research hub
    * Access control: public/internal/private profiles, privileged/admin access
* version 2  
    * Automated email notification service of matches, adjustable matching threshold 
    * Detection of duplicate entries through offline batch comparison of entries
    * Profile enrichment through free-text scraping from URLs added to profiles 
    * Deployment-ready package of components for easy cloud deployment
    * API for automating data ingestion from other data sources through simple scripts
    * User feedback, feature request submission, discussion/enquiry forum
* version 3  
    * User-based match validation and feedback-based adaptation of matching models 
    * Background analytics and visualisation of matches and user engagement
    * Navigable similarity maps of experts and opportunities
    * Mobile app frontend using the same backend
    * Interoperation with Salesforce IRM
    * Linked management of multiple installations with controlled tiers of data visibility

## Units
* Data  
    * Version 1
        * Database (shiyao)(Yu)
        * Indexing(Yu)
        * Profile import from existing database (shiyao)
* UI
    * Version 1
        * Profile editing page (Chen) (shiyao)
        * Search page (Chen) (shiyao)
        * Matches page (Chen) (shiyao)
        * Profile page (Chen) (shiyao)
    * Version 2
        * User feedback, discussion page (Chen) (shiyao)
        Version 3
        * Analytics and visualisation (for operation staffs) (shiyao)
        * Navigable similarity maps of profiles (for users)
        * Mobile app (shiyao)
* Function
    * Version 1
        * CRUD @Zhaoyu
        * Semantic matching @Zhaoyu (Yu)
        * Access control @Zhaoyu
    * Version 2
        * Automated email (email server) @Zhaoyu
        * Adjustable matching threshold @Zhaoyu
        * Duplicated entries detection @Zhaoyu (shiyao)
        * Profile enrichment through URLs (shiyao) @Zhaoyu 
        * API (shiyao) @Zhaoyu
    * Version 3
        * Match validation and adaptive matching model
        * Interoperation with Salesforce
* Flow
    * Version 2
        * Deployment-ready package for cloud 
