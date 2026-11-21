# Observations and Conclusion – Case Study 2

*Dataset: 100 employees (E101–E112 from the case study, E113–E200 simulated).*

## Key results

| Measure | Value |
|---|---|
| Number of employees | 100 |
| Average attendance | 85.05 % |
| Total tasks completed | 3415 |
| Maximum tasks | 51 (Mythili, E197) |
| Minimum tasks | 16 (Catherine, E151) |
| Excellent / Satisfactory / Poor | 32 / 56 / 12 |
| Correlation (attendance vs tasks) | 0.71 |

## Department-wise summary

| Department | Employees | Avg Attendance % | Total Tasks | Avg Tasks | Rank |
|---|---|---|---|---|---|
| Development | 40 | 86.2 | 1543 | 38.58 | 1 |
| Testing | 35 | 84.3 | 1212 | 34.63 | 2 |
| HR | 25 | 84.2 | 660 | 26.40 | 3 |

## Part E – Interpretation

1. **Highest productivity department:** Development (38.6 tasks per employee on average).
2. **Maximum tasks completed by:** Mythili (E197) with 51 tasks and 100% attendance.
3. **Employees with poor attendance (<75%):** 12 (12% of employees). Lowest attendance: Gayathri (67%), Gokul (68%), Rajesh (68%), Ilango (71%), Logesh (71%).
4. **Does higher attendance necessarily mean higher productivity?** No. The correlation is strong (r ≈ 0.71) so they usually rise together, but Karthik (90% attendance) completed only 26 tasks, while Vimal (78% attendance) completed 36. Correlation is not causation, and task count ignores task difficulty and quality.
5. **Measures to improve productivity:**
   - Counselling and flexible-hours support for the 12 employees below 75% attendance.
   - Mentoring: pair top performers (Mythili, Indhu, Evelyn) with low-output employees.
   - Review workload and task definitions in HR, which has the lowest average output.
   - Set monthly task targets and track them on a dashboard.
   - Skill-based training, recognition and incentives for consistent performers.

## Other observations
- Employees with *Excellent* attendance average 40.3 tasks, while those with *Poor* attendance average 22.5.
- 32 of 100 employees (32%) have attendance of 90% or more.
- Department with best average attendance: Development (86.2%); lowest: HR (84.2%).

## Conclusion
The analysis shows Development as the most productive department and HR as the least, and identifies 12 employees who need attendance support. Attendance has a strong positive relationship with tasks completed, so improving attendance is likely to help productivity, but it should be combined with mentoring, realistic targets and training. The spreadsheet is formula-driven, so the HR team can add employees and the summary, classification and charts update automatically.

