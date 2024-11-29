
# Overdue 

```tasks
((due before today) OR (no due date)) AND (not done)
hide created date
```

# Due by today

```tasks
((due on or before today) OR (no due date)) AND (not done)
hide created date
group by priority
```

# Followups

```tasks
(tag include #T/followup) AND (not done)
hide created date
```

# Delegation

```tasks
(tag include #T/delegate) AND (not done)
hide created date
```

# Action Items

```tasks
((tags include #T/action) OR (tags include #T/reply)) AND (not done)
hide created date
```

# Due this week

```tasks
not done
due before in 7 days
sort by due date
group by priority
hide created date
```

# Tasks Completed today

```tasks
done on today
```