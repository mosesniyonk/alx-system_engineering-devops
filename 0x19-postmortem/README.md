# Postmortem

Learning how to write an Incident Report, also referred to as a Postmortem. This postmortem follows the guidelines used closely by Google engineers to file reports. The report comprises five parts: an issue summary, a timeline, root cause analysis, resolution and recovery, and corrective and preventative measures. Let's review each of these parts in detail.

### Issue Summary

- short summary (5 sentences)
- list the duration along with start and end times (include timezone)
- state the impact (most user requests resulted in 500 errors, at peak 100%)
- close to the root cause

### Timeline

- list the timezone
- covers the outage duration
- when the outage began
- when the staff was notified
- actions, events, …
- when service was restored

### Root Cause

- give a detailed explanation of an event
- do not sugarcoat

### Resolution and recovery

- give a detailed explanation of actions taken (includes times)

### Corrective and Preventative Measures

- itemized list of ways to prevent it from happening again
- what can we do better next time?
