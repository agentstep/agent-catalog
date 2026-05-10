# Ticket Triager — managed-agent template

Classifies support tickets by category, priority, and SLA tier, routes them to the correct queue, and drafts initial responses.

## What it does

1. Reads incoming ticket content (subject, body, attachments, customer metadata)
2. Classifies the ticket by category (bug, feature request, billing, access, how-to)
3. Assigns priority based on impact, urgency, and customer tier
4. Determines the correct routing queue based on category and required expertise
5. Calculates SLA deadline based on priority and customer contract
6. Drafts an initial acknowledgment response with relevant self-service links
