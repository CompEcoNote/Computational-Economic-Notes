---
layout: default
title: Computational Economic Notes
---

# Computational Economic Notes

Simple, open peer-reviewed computational economics papers.

## 🚀 Quick Start

### For Authors:
[Submit a Paper](https://github.com/CompEcoNote/Computational-Economic-Notes/issues/new?template=submit-paper.md){: .btn .btn-primary }

### For Reviewers:
[Review Checklist](REVIEW_CHECKLIST.md){: .btn .btn-secondary }

## 📚 Recent Papers

{% assign papers = site.papers | sort: 'date' | reverse %}
{% for paper in papers limit:5 %}
- **[Paper {{ paper.paper_id }}]({{ paper.url }})** – {{ paper.title }} *({{ paper.date | date: "%B %d, %Y" }})*
{% endfor %}

[View all papers](/papers/){: .btn }

## 🔄 How It Works

```mermaid
graph LR
    A[Submit Issue] --> B[Assign 2 Reviewers]
    B --> C[Discuss in Comments]
    C --> D{2 Approvals?}
    D -->|Yes| E[Auto-Publish PDF]
    D -->|No| C
    E --> F[Paper Available Online]
