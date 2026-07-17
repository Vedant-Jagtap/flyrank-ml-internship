# Week 2 - Prompt Ladder

## Baseline Prompt (Weak)

Help me build a machine learning model.

### Output (Excerpt)

The AI gave a very generic explanation about Machine Learning and listed common algorithms without understanding my project.

### Notes

- What changed: Baseline prompt only.
- What improved: None.
- What still failed: No context, too generic, not useful.
- Next step: Add a clear goal.

---

# Version 1 - Clear Goal

## Prompt

Help me frame a Machine Learning task for predicting which webpages require a content refresh.

### Output (Excerpt)

The AI correctly identified the problem as a classification task.

### Notes

- Change made: Added a clear goal.
- Output improved: The response focused on my actual problem instead of general ML.
- Still failed: It didn't know my internship context.
- Next step: Add context.

---

# Version 2 - Add Context

## Prompt

I am completing the FlyRank Machine Learning Internship. Help me frame a Machine Learning task for predicting which webpages require a content refresh using the internship dataset.

### Output (Excerpt)

The AI suggested using webpage features and explained why classification fits this task.

### Notes

- Change made: Added project context.
- Output improved: The suggestions became much more relevant.
- Still failed: The answer was too long.
- Next step: Specify output format.

---

# Version 3 - Output Format

## Prompt

I am completing the FlyRank Machine Learning Internship.

Help me frame a Machine Learning task for predicting which webpages require a content refresh.

Return the answer using these headings:

- Task Type
- Target
- Success Metric
- Why ML

### Output (Excerpt)

The AI returned a structured answer using the requested headings.

### Notes

- Change made: Added output format.
- Output improved: Easier to copy into my notebook.
- Still failed: Some explanations were generic.
- Next step: Add quality criteria.

---

# Version 4 - Quality Criteria

## Prompt

I am completing the FlyRank Machine Learning Internship.

Help me frame a Machine Learning task for predicting which webpages require a content refresh.

Return the answer using these headings:

- Task Type
- Target
- Success Metric
- Why ML

Use simple language suitable for an internship notebook. Avoid buzzwords and unsupported claims.

### Output (Excerpt)

The response became much clearer and more practical.

### Notes

- Change made: Added quality criteria.
- Output improved: Better wording and fewer generic phrases.
- Still failed: It still assumed some details.
- Next step: Ask it to verify assumptions.

---

# Version 5 - Verification

## Prompt

I am completing the FlyRank Machine Learning Internship.

Help me frame a Machine Learning task for predicting which webpages require a content refresh.

Return the answer using these headings:

- Task Type
- Target
- Success Metric
- Why ML

Use simple language suitable for an internship notebook.

If information is missing, clearly state your assumptions instead of inventing facts.

### Output (Excerpt)

The AI explicitly separated confirmed information from assumptions, producing a more reliable answer.

### Notes

- Change made: Added verification requirement.
- Output improved: The response became more trustworthy.
- Still failed: None significant.
- Next step: This is the version I would reuse.

---

# Final Reusable Prompt

I am completing a Machine Learning internship project on predicting which webpages require a content refresh.

Help me frame the ML task.

Return the answer using these headings:

- Task Type
- Target
- Success Metric
- Why ML

Use simple language suitable for an internship notebook.

Avoid buzzwords.

If information is missing, clearly state assumptions instead of inventing facts.
