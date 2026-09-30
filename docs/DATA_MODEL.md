# Shared Data Model

All contributors should use the same conceptual structure.

```js
const member = {
  id: "member-001",
  name: "山田 太郎",
  role: "Sales",

  hp: {
    current: 21,
    predicted: 57,
    max: 100
  },

  workload: {
    meetings: 8,
    tasks: 12,
    overtimeHours: 14
  },

  risks: [
    {
      type: "overload",
      level: "high",
      reason: "会議とタスクの集中"
    }
  ],

  aiAnalysis: {
    summary: "",
    causes: [],
    futureRisk: ""
  },

  recommendedActions: [],

  recovery: {
    quests: [],
    message: "",
    gift: null
  }
}
```

## Rules
- Do not rename shared keys casually.
- Changes to this model should be reviewed before merge.
- HP must never be interpreted as employee competence or performance.
