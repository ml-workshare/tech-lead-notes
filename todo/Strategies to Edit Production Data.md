@jqiu25

# Why we edit production data?
- internal tools unavailable
- edge cases
- needed now

# Strategies for safer editing
- raw sql spreadsheet
- local scripts
- existing server
- task runner
- script runner service

##1. develope a review process for manual edits.
record manual sql queries against production. - a checklist of things that need to be done.

1. add record to spreadsheet
name, date, description, the query, reviwer. why.

2. reviewer approves the qeury.
3. run the query inside a transaction. 

easy, provides audit trail. promotes the right behaviours.

## write script
-  scirpt on local machine against rmeote mahinces
- dry-run 

