# Finwise
FinWise – Smart Expense Tracking & Insights Platform

Overview :-

FinWise is a web-based financial management tool that helps users track expenses, upload receipts, set savings goals, and receive AI-driven insights to improve their spending habits.

Key Features :-

Simple Sign-Up: Email-based authentication with secure login.

Expense Tracking: Add transactions manually or upload receipts (OCR-powered).

Smart Categorization: Automatically assigns expenses to categories; users can verify or adjust.

Dashboard:-

Transaction history (recent-first)

Category-wise spending (bar graph)

Monthly budget vs spent (pie chart)

Spending trends over 3 months (line graph)

Goals & Budgeting: Set multiple financial goals; progress auto-resets after goal period.

Insights: AI generates daily tips & recommendations for cost-cutting and smarter saving.

Alerts: In-app notifications for budget nearing, overspending, or goal tracking.

Search: ElasticSearch-powered advanced search across transactions and receipts.

Receipt Management: All receipts stored in AWS S3, with option to delete securely.

Tech Stack

Frontend: React.js (interactive dashboard, charts, notifications)

Backend: Microservices (Auth, Transactions, Receipts, Goals, Insights, Notifications)

Database: AWS RDS (PostgreSQL)

Storage & AI: AWS S3 + OCR (Textract), AI for insights & category recommendations

Search: ElasticSearch/OpenSearch for advanced queries

Why FinWise?
Unlike basic expense trackers, FinWise goes beyond logging expenses. It gives real-time alerts, AI-powered insights, and visualizations to help users not just track but actively optimize spending and achieve financial goals.
