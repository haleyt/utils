utils
=====

some scripts I want to put in my /usr/local/bin/, to help my daily work

- create_csprj: a bash script to help creating cscope tags
- create_filenametags: a bash script to help creating filename tags
- create_tags: a wrapper script to create tags (e.g. cscope tags and/or filename tags) for a folder/project
- create_cscope_db_list: a script to create cscope tags for all of each project in a repo manifest (utilizing repo-forall and create_tags).
	'vim' can *source* the generated cscope_db.list to connect to all the seperated cscope databases

