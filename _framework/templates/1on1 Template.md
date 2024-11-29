---
<%*
let filename = tp.file.title
if ( filename.startsWith("Untitled") ) {
  person = await tp.system.prompt("1:1 with: ")
  await tp.file.rename(`${tp.date.now()} - ${person}` )
} 
%>
type: 1-on-1 meeting
created_ts: <% tp.date.now("YYYY-MM-DDTHH:mm:ssZ") %>
meeting_date: <% tp.date.now() %>
---

# Topics to address


# Followups


# Action Items


# Key Takeaways


# Notes



