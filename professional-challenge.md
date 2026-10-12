# Professional Challenge — Accountancy Firm (Design Only)

The firm wants morning sorting and data capture, not automatic replies.

**Classification categories:** appointment_request, document_submission, general_tax_question, billing_issue, other_or_unclear. Safety or security threats should be flagged for manual review separately.

**Extraction fields:** sender_name, contact, requested_action, appointment_date_text, appointment_time_text, document_types_mentioned, tax_topic, urgency_signals, missing_fields. Missing or ambiguous values remain null/empty; no invented deadlines, tax advice, or appointment confirmations.

**Human boundary:** classify and extract only. Never answer a tax question, confirm an appointment, file documents, or send messages. Ambiguous messages go to human_review.

**Client reliability sentence:** “Your team gets a consistent first-pass inbox sort, with uncertain messages flagged for a person to check instead of being silently guessed.”

Status: conceptual response to the book's Professional Challenge; not a deployed or tested workflow.
