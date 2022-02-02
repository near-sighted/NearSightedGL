# Discord

This is where all the data imported from [Discord](https://discord.gg/JVgm7dGf42) is displayed. 

![](https://hackmd.io/_uploads/H1f0w0wCt.png)

## Views

### Incoming

### Grouping & Sorting

#### 1. Conversation
* item_no: This is also the table's primary key. It's a combination of the ISO 8601 UTC-based timestamp of of when the post was made plus the user_id of the poster.
* timestamp: This is a sequence of characters or encoded information identifying when a certain event occurred, usually giving date and time of day, sometimes accurate to a small fraction of a second.
* message_link: This is the `URI` to the relevant message in Discord.  
* message_id: This is the `unique id` for the message
* parent_message_id: This is only available if the current message is a reply to a previous message. It is only there if the user clicked on `reply` before typing in the message.
* parent_record: This is the parent message's `item_no`.
* content: This is a combination of both the `user_id` and the text (string) of the message posted. If the message is not a string, it would be empty. If it is a combination of string and other data types, it would contain only the string, with the other data types displayed in the `attachments` cell.
* attachments: This is a link poin
* conversation 
* code block
* notes
* tags
* embeds 
* intention
* intention_done
* intention_done_all
* raw_json
* duplicate
* ignore
* imported time
* Channels Table Link
* user_details
* Last Modified
* Last Modified By
* message_link
* parent_record
* potential_thread
* User
* discord_handle (from Users)
* discord_avatar (from Users)
* is_team (from Users)
* discord_uid (from Users)
* channel_id (from Users)

### Collaborators

## Filters

* Hidden Fields

* Filtered by

* Grouped by






