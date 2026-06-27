# QA Lesson Learned - Requirement Gathering Reveals More Than Bugs

## Scenario

During requirement gathering sessions, users shared various operational challenges encountered while using the system.

Rather than reporting only technical defects, users also highlighted areas where the application could better support their daily workflows.

The objective was to understand the underlying business problems and identify opportunities for system improvement.

---

## Observation

Many of the findings collected during discussions were not traditional software bugs.

Instead, they fell into several categories:

* Missing or incomplete functionality.
* Workflow inefficiencies that required unnecessary manual work.
* Reporting limitations.
* Performance concerns when processing larger datasets.
* Data consistency issues across different modules.
* Missing information at critical stages of the business process.
* Requests for additional master data management capabilities.

These findings demonstrated that users often describe business pain points rather than technical problems.

---

## Why This Matters

### User Impact

* Users may spend additional time completing manual tasks.
* Important information may not be available when needed.
* Daily operations become less efficient.

### System Impact

* The system may technically function as designed while still failing to meet business needs.
* Missing functionality can increase dependency on manual processes.

### Data Impact

* Data inconsistencies may reduce user confidence.
* Manual work increases the risk of human error.

### Business Impact

* Operational efficiency may decrease.
* Reporting and decision-making become more difficult.
* Improvement opportunities may be overlooked if every finding is treated solely as a bug.

---

## QA Learning

Requirement gathering requires understanding the business problem before identifying the technical solution.

### Validation Points

* Understand the user's current workflow.
* Identify the business objective behind each request.
* Verify whether the issue is caused by incorrect system behavior or by missing functionality.
* Determine whether the request impacts multiple modules or business processes.

### Edge Cases

* Large datasets affecting performance.
* Cross-module data consistency.
* Manual workarounds performed by users.
* Missing information during specific business processes.

### Business Rules

* System behavior should support established business workflows.
* Business requirements should be validated before defining technical solutions.
* Similar workflows should provide a consistent user experience.

### System Behavior Expectations

* The application should minimize unnecessary manual work.
* Required business information should be available at the appropriate stage of the workflow.
* Related modules should present consistent and reliable data.

---

## UX / System Consideration

Potential improvements include:

* Simplifying workflows to reduce manual effort.
* Improving report accessibility and performance.
* Making critical business information more visible.
* Enhancing master data management to support operational needs.
* Designing features based on business objectives rather than individual user requests.

---

## Key Takeaway

Requirement gathering is not only about identifying software bugs—it is about understanding the business problems users are trying to solve.

Effective QA requires looking beyond technical defects to identify workflow improvements, usability concerns, and opportunities to better align the system with business processes.
