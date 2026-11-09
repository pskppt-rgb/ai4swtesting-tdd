**Accuracy**

1. **How is time rounded to half-hour units?**
   If I work 40 minutes, is it recorded as 0.5 hours, 1 hour, or rejected? The rounding rule (up, down, nearest) is not stated, so the stored totals could differ from the time actually worked.

2. **What is the minimum and maximum amount of time that can be entered?**
   Can a user enter 0 hours, a negative value, or more than 24 hours in a day? Without limits, the history could hold impossible values.

3. **When is time attributed: by the date the work happened or the date it was entered?**
   If I log Monday's work on Wednesday, which date does the history show? This decides whether "time spent on a project" per period is correct.

4. **What does "specific projects" mean, and where do projects come from?**
   Are projects picked from a predefined list, or typed in as free text? Free text could split one project into several, for example "Website" and "website redesign", which makes the totals wrong.

5. **Who counts as "I" when deciding visibility?**
   Does "only I" exclude managers, admins, and payroll? If someone else can see or edit entries, the claim that the data belongs only to the user, and is accurate, is weakened.

**Consistency**

6. **How should time be shown across the system: as decimals (1.5) or as hours and minutes (1h 30m)?**
   If entry, history, and reports use different formats, users may misread or re-enter values in different ways.

7. **Why does completing a timesheet need only a project and an amount of time? Isn't a date also required?**
   A history usually needs a date. If some screens ask for a date and others don't, the records will not match.

8. **What happens when the same project is logged more than once on the same day?**
   Are the entries added together, does the new one replace the old one, or is it blocked? The behaviour should be the same everywhere the user can enter time.

9. **How are entries treated after they are submitted? Can they be edited or deleted?**
   If edits are allowed in some places but not others, or if edits don't update totals everywhere, the history will contradict itself.

10. **Where is the time history shown, and do all views show the same totals?**
    The per-project totals, daily views, and any summaries need to add up to the same number. Otherwise different screens give different answers.
