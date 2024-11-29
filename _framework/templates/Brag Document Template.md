---
<%*
let filename = tp.file.title
if ( filename.startsWith("Untitled") ) {
  await tp.file.rename(`Brag document - ${tp.date.now("MMMM YYYY")}`)
} 
%>
type: brag_document
created_ts: <% tp.date.now("YYYY-MM-DDTHH:mm:ssZ") %>
month_year: <% tp.date.now("MMMM YYYY") %>
year: <% tp.date.now("YYYY") %>
month: <% tp.date.now("MM") %>
---

Guidelines: [[Brag Documents/README|README]]

# Add sections accordingly