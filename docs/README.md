## [21pleb](https://21pleb.github.io)/[_config_automoderator](/_config_automoderator)

### Script

```
    
# Filter comments from accounts with low karma
    author:
        comment_karma: "< -50"
    action: filter
    action_reason: "comment karma < -50"

---

# send modmail when a comment receives 5 reports
    reports: 5
    action_reason: 5+ reports
    modmail: "A {{kind}} by /u/{{author}} has received 5 reports please check on it.  {{permalink}}"

---
```
