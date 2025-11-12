---
title: "Activity"
layout: default
randomized: false
questions:
  - type: "multiple-choice"
    question: "True or False, Pittsburgh is West of Philadelphia"
    items:
      - choice: True
        correct: true
      - choice: False
        correct: false
    followup: |
      The answer is True! Pittsburgh is 304.9 miles West of Philadelphia, or approximately a car ride of 4 hours and 52 minutes. Buckle up!

---
Content for your interactive activity.

{% if page.questions %}
  <h2>{{ page.title }}</h2>

  {% for q in page.questions %}
    <div class="question">
      <p><strong>{{ q.question }}</strong></p>
      <ul>
        {% for item in q.items %}
          <li>{{ item.choice }}</li>
        {% endfor %}
      </ul>
      <p><em>{{ q.followup }}</em></p>
    </div>
  {% endfor %}
{% endif %}

[← Back to Main Case Study](/ethics_fall2025/casestudy/)