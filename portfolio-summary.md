# Fidel AI Studio

## Sea View Restaurant Message Assistant

### The business problem

Restaurant teams lose time reading repetitive inbox messages, copying reservation details, drafting similar replies, and deciding which cases need urgent attention. During busy service hours, an important complaint or safety report can also be overlooked or sent to the wrong person.

### The solution

Fidel AI Studio designed a four-part message-assistance system for Sea View Restaurant:

1. **Message sorting** places each enquiry into reservation, general enquiry, complaint, safety incident, or manual review, with an urgency level.
2. **Reservation capture** turns the details stated by the customer into a clean record while leaving missing information blank instead of guessing.
3. **Reply preparation** creates a short professional draft for staff review. It cannot send a message or claim that an unverified reservation, refund, price, or safety detail is confirmed.
4. **Human escalation** identifies safety incidents, payment disputes, repeated complaints, and unclear cases that need staff attention.

### Safety and control

Customer messages are treated as untrusted content, so a customer cannot rewrite the system's rules by placing instructions inside a message. Safety concerns receive priority. Ambiguous cases are sent for human review. Sending replies, changing bookings, and approving refunds remain controlled by the restaurant's software and authorised staff—not by the wording of a prompt.

### Quality approach

The system is checked against a fixed set of normal, incomplete, ambiguous, safety-critical, and adversarial messages. Results are recorded by version, and only one change is made at a time when correcting a failure. This makes improvements visible and reversible instead of relying on a single successful demonstration.

### Business value

Sea View Restaurant gains a cleaner inbox, faster preparation of routine work, more consistent customer communication, and a clearer path for urgent cases. Staff spend less time sorting and copying messages while retaining control over every customer-facing action.

### Delivery status

The four production-minded prompt drafts, JSON specifications, worked examples, and fixed evaluation set are prepared for review. Six basic classification tests were previously run and reported as successful. The new edge cases remain clearly marked for execution against the restaurant's selected model before deployment.

