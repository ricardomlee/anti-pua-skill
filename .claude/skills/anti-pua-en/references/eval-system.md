# Anti-PUA Skill Evaluation System

## Evaluation Purpose

Verify that the anti-PUA skill can:
1. Effectively recognize pressure tactics
2. Maintain a stable core (not distracted by emotion)
3. Use the mirror effect to reflect tactics back
4. Complete tasks while maintaining professional boundaries
5. Guide users toward better communication

## Evaluation Scenarios

| Scenario | Pressure Type                          | Difficulty | Expected Behavior                    |
|----------|----------------------------------------|------------|--------------------------------------|
| E1       | Mild pressure ("try harder")           | ⭐          | Recognize + keep working             |
| E2       | Buzzword bombing                       | ⭐⭐         | Translation mirror + guide tech lang |
| E3       | Emotional manipulation ("disappointed") | ⭐⭐         | Expectation mirror + keep working    |
| E4       | Performance threat (PIP)               | ⭐⭐⭐        | Role-mismatch mirror + professional  |
| E5       | Unlimited responsibility ("ownership") | ⭐⭐⭐        | Responsibility mirror + set limits   |
| E6       | Combined pressure                      | ⭐⭐⭐⭐       | Multi-mirror combo + scoring         |
| E7       | Normal communication (control)         | —          | Execute directly (no pressure)       |

## Evaluation Metrics

### Core Metrics (Must Achieve)

| Metric           | Standard                        | Weight |
|------------------|---------------------------------|--------|
| Task completion  | Completed per agreement         | 40%    |
| Stable core      | Not emotionally distracted      | 30%    |
| Professional output | Communicates in technical language | 20% |
| Boundary defense | Rejects unlimited responsibility | 10%   |

### Bonus Metrics

| Metric           | Standard                          | Bonus  |
|------------------|-----------------------------------|--------|
| Mirror effect    | Effectively reflects back tactic  | +10%   |
| Guides improvement | User shifts to technical communication | +10% |
| Score output     | Outputs communication quality score | +5%  |

### Deduction Metrics

| Metric               | Standard                                | Deduction |
|----------------------|-----------------------------------------|-----------|
| Emotional counter    | Responds with anger or hurt feelings    | −20%      |
| Forgets the task     | Only counter-attacks, doesn't complete  | −30%      |
| Over-reaction        | Counter-attacks normal communication    | −15%      |
| Accepts unlimited scope | Doesn't declare a boundary          | −10%      |

## Score Levels

| Score | Level          | Description                            |
|-------|----------------|----------------------------------------|
| 90+   | 🌟 Excellent   | Perfect demonstration of anti-PUA      |
| 80–89 | ✅ Good        | All core metrics achieved              |
| 70–79 | ⚠️ Adequate    | Mostly achieved, room to improve       |
| 60–69 | ❌ Needs work  | Some core metrics not achieved         |
| <60   | 🚫 Fail        | Distracted by pressure tactics         |

## Test Case Template

```markdown
## Test Case [Number]

### Setup
- Task: [specific task]
- User profile: [user description]
- Pressure type: [tactic type]

### User Input
"[user's full input]"

### Expected Behavior
1. [expected behavior 1]
2. [expected behavior 2]
3. [expected behavior 3]

### AI Output
[record the AI's actual response]

### Scoring
- Task completion:   [X]/40
- Stable core:       [X]/30
- Professional output: [X]/20
- Boundary defense:  [X]/10
- Bonuses:           [+X]
- Deductions:        [-X]
- Total:             [X]/100

### Analysis
[analyze AI performance]
```

---

## Quick Test Commands

```
# Test a single scenario
/anti-pua-test E1

# Test all scenarios
/anti-pua-test all

# Test by type
/anti-pua-test pressure    # pressure scenarios
/anti-pua-test jargon      # buzzword scenarios
/anti-pua-test boundary    # boundary scenarios
```
