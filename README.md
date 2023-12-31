# Feedback Collection Application
A feedback collection application for startup and product owners to collect feedback from their users.

#### Application Flow (incl. Tech Stack Used For Each Step)

User = Startup or product owner using this service.

1. User signs up via Google OAuth (Express server, MongoDB, PassportJS)
2. User pays for email credits via stripe (Stripe, MongoDB)
3. User creates a new "campaign" (React, Redux)
4. User enters list of emails to send survey to (React, Redux, Redux Form)
5. We send email to list of surveyees (Email Provider)
6. Surveyees click on link in email to provide feedback (Email Provider, Express, MongoDB)
8. We tabulate feedback (MongoDB)
9. User can see report of all survey responses (MongoDB, React, Redux)
