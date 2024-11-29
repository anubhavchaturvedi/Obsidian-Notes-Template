---
<%*
let filename = tp.file.title
if ( filename.startsWith("Untitled") ) {
  filename = await tp.system.prompt("Meeting title: ")
  await tp.file.rename(filename)
} 
%>
type: meeting_notes
meeting_date: <% tp.date.now() %>
created_ts: <% tp.date.now("YYYY-MM-DDTHH:mm:ssZ") %>
---
**Attendees:**

# Notes






# Followups


# Action Items


# Key Takeaways







