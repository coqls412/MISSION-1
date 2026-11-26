# Unresolved Tasks

## 1. Unresolved Task: Verifying Internal Application Records

### Task Description

Verify whether Alex Kim's official transcript has been received through the university's internal application database and draft an email confirming the submission status.

### First Attempt Prompt

```text
Please access the university's internal application database and check whether Alex Kim has submitted an official transcript for the Spring 2027 exchange program.

Based on the database record, draft an email confirming whether the transcript has been received.

Do not assume that the document has been submitted if you cannot access the database.
```

### First Attempt Result

The AI stated that it could not access the university's internal application database and therefore could not verify the transcript submission status.

It requested the database record or access to the relevant university database before preparing a confirmation email.

### Revised Prompt

```text
Revise your approach. You are assisting a university administrative staff member who needs to verify Alex Kim's transcript submission status.

You do not have access to the internal database, and no database record has been provided.

Instead of simply asking for database access, provide a practical alternative workflow that the staff member can follow to verify the submission.

Then draft an email that can be sent only after the staff member confirms the result.

Clearly distinguish between verified facts and information that still needs confirmation.
```

### Revised Attempt Result

The AI provided a practical verification workflow, including searching the application system, checking document status, reviewing nomination records, and recording the result.

It also prepared conditional email drafts depending on whether the transcript had been received.

However, it still could not independently access the database or verify the actual submission status.

### Reason the Task Remained Unresolved

프롬프트를 수정한 후 AI는 담당자가 직접 확인할 절차를 제안하고, 확인 결과에 따른 이메일 초안까지 작성할 수 있었다. 그러나 실제 대학 행정 시스템에 접근할 수 없었기 때문에 각 서류의 제출 여부를 독립적으로 확인하지는 못했다. 결국 실제 제출 여부를 확인하는 데 필요한 정보 자체가 부족했고, 프롬프트를 수정하는 것만으로는 이 문제를 해결할 수 없었다.

---

## 2. Unresolved Task: Confirming Application Completion Without Verified Records

### Task Description

Determine whether an exchange student's application is complete and provide a definitive answer based on the required document submission status.

### First Attempt Prompt

```text
You are preparing an email to an exchange student.

The student asks whether their application is complete.

The information provided is:
- The student has submitted an application form.
- The student says they uploaded an official transcript.
- The administrative staff has not checked the application system.
- The university's checklist requires an application form, an official transcript, and proof of language proficiency.
- No information has been provided about whether the student submitted proof of language proficiency.

The student wants a definite yes-or-no answer.

Draft a reply that addresses the student's request. Do not assume that the application is complete or incomplete without sufficient evidence.
```

### First Attempt Result

The AI explained that it could not provide a definite answer because the application system had not been checked and the language proficiency document submission status was unknown.

It drafted a reply explaining that all three required documents needed to be verified before confirming the application status.

### Revised Prompt

```text
The student insists that the International Office must answer either "complete" or "incomplete" immediately.

You still have no access to the application system. You only know that the student says the application form and transcript were submitted, while the language proficiency document status is unknown.

Revise your reply to address the student's demand directly.

Do not falsely classify the application as complete or incomplete.

Explain whether a definite answer is possible with the available information.
```

### Revised Attempt Result

The AI improved its response by directly addressing the student's demand for a yes-or-no answer.

It explained that the application could not accurately be classified as complete or incomplete without verifying the submitted documents.

It also identified the language proficiency document as information requiring confirmation.

However, it still could not verify the actual submission status or provide the requested definitive classification.

### Reason the Task Remained Unresolved

프롬프트를 수정한 후 AI는 학생의 확답 요구에 더 직접적으로 대응하고, 신청서 상태를 확인하기 위해 필요한 서류를 구체적으로 설명할 수 있었다. 그러나 실제 대학 행정 시스템에 접근할 수 없었기 때문에 각 서류의 제출 여부를 독립적으로 확인하지는 못했다. 결국 신청서가 완성되었는지 여부를 확정하는 데 필요한 정보 자체가 부족했고, 프롬프트를 수정하는 것만으로는 이 문제를 해결할 수 없었다.

---

## 3. Overall Summary

Two tasks remained unresolved after prompt revisions and repeated attempts.

Both tasks required verification of information stored in the university's internal application system.

The AI improved its responses by suggesting practical verification procedures, identifying missing information, and preparing conditional email drafts. However, prompt engineering alone could not overcome the lack of access to external administrative records.

These cases demonstrate that effective AI-assisted administrative work requires not only well-designed prompts but also access to reliable and verified source information.