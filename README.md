# Cognitive Check-in: a research prototype

I'm Sara Hassan Omar. This is a small prototype for the question I want to spend my doctoral research on: what turns suicidal thoughts into suicidal behavior, and can we see the change early enough to ask better questions?

I know this problem from the John D. Dingell VA Medical Center, where I tested veterans and managed the REDCap database that followed them across visits. Few studies follow cognition, sleep, and life events day to day. This prototype is one thin slice of that gap.

## What it does

- **Check-in:** a 45-second symbol-matching task, plus a short daily log (sleep, stress, notable events).
- **Clinician dashboard:** each person is compared with their own baseline (the first four check-ins). If two check-ins in a row fall more than 1.5 standard deviations below that baseline, the dashboard flags it and shows what changed, by how much, and when, alongside sleep and logged events.

## What it does not do

- It does not assess suicide risk or predict anything.
- It is not a medical device and is not clinically validated.
- The dashboard uses synthetic data. Nothing you enter is stored or sent anywhere.
- It asks nothing about suicidal thoughts. A real study would need ethics approval, informed consent, and a clinical safety protocol first.

## Run it

Open `index.html` in any browser. No install, no server.

## Next steps

1. Ethics approval and a clinical safety plan.
2. Test with clinicians: can they tell what changed, why it was flagged, and what to ask next?
3. Pilot with consenting veterans.
