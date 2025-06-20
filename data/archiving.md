---
title: Archiving
description: TODO:FIXME
layout: libdoc_page.liquid
eleventyNavigation:
    parent: Data Management
    key: Archiving
    order: 2800
date: git Last Modified
---
Archiving records in ServiceNow is weird. Next paragraph

How archiving works is you set up an archive rule for a specific table you say when these conditions are met archive these recordsand what happens to those records is they are removed from the current table and put on a magic table that doesn't extend the table you're currently on but is still referenced a bull by the records that referenced the originating table.

This helpsimprove performanceby reducing the rows that you're searching when loading listsand searching or filtering for data on the table that's large.

However if you need to retain that data for any duration of time once it's archived it's near impossible to deal withthe only action you can take is to unarchive the record.



1. [Over your storage limit? Archiving may not be your friend - 07/26/2023](https://www.servicenow.com/community/developer-forum/over-your-storage-limit-archiving-may-not-be-your-friend/m-p/2624658)
2. [Over your storage limits? Wrangling in Knowledge articles - 08/03/2023](https://www.servicenow.com/community/developer-forum/over-your-storage-limits-wrangling-in-knowledge-articles/m-p/2633650)
3. [Over your storage limit? sys_email is loud (and full of junk) - 08/30/2023](https://www.servicenow.com/community/developer-forum/over-your-storage-limits-sys-email-is-loud-and-full-of-junk/m-p/2624675)
4. [Over your storage limit? Reducind our storage footpring; our lessons learned - 01/08/2024](https://www.servicenow.com/community/developer-forum/over-your-storage-limit-reducing-our-storage-footprint-our/m-p/2623398)

[Perspectium Archive Rules (and Destory Rules) Explained Blog Post](https://www.perspectium.com/blog/servicenow-archive-rules-explained/)
