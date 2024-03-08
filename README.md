# {BR&SRI} Humanoid Robotics Working Group

Mission: The Humanoid Robotics Working Group's mission is to to build the architecture of humanoid robotics build that is

{{Scope: the types of topics, tools, libraries, applications, documents, etc, that this working group focuses on. }}

### Subproject List

* BR&SRI Humanoid Robot Intelligence Control System Framework
  * Description: ROS/ROS2 Humanoid Robotics Framework
  * Repositories
    * https://github.com/Robotics-Sensors/humanoid_robot_intelligence_control_system_framework

* BR&SRI Humanoid Robot Intelligence Control System Module
  * Description: ROS/ROS2 Humanoid Robotics Module
  * Repositories
    * https://github.com/Robotics-Sensors/humanoid_robot_intelligence_control_system_module

* BR&SRI Humanoid Robot Intelligence Control System Utility
  * Description: ROS/ROS2 Humanoid Robotics Utility
  * Repositories
    * https://github.com/Robotics-Sensors/humanoid_robot_intelligence_control_system_utility

* BR&SRI Humanoid Robot Intelligence Control System Messages
  * Description: ROS/ROS2 Humanoid Robotics Messages
  * Repositories
    * https://github.com/Robotics-Sensors/humanoid_robot_intelligence_control_system_messages

* BR&SRI Humanoid Robot Intelligence Control System Tools
  * Description: ROS/ROS2 Humanoid Robotics Tools
  * Repositories
    * https://github.com/Robotics-Sensors/humanoid_robot_intelligence_control_system_tools

* BR&SRI Humanoid Robot Intelligence Control System Demos
  * Description: ROS/ROS2 Humanoid Robotics Demos
  * Repositories
    * https://github.com/Robotics-Sensors/humanoid_robot_intelligence_control_system_demos


### Standards for subprojects

Subprojects must meet the following criteria (and the WG agrees to maintain them upon adoption).

* Build passes against ROS 2 master
* The ROS 2 standard linter set is enabled and adhered to
* If packages are part of nightly builds on the ROS build farm, there are no reported warnings or test failures
* Quality builds are green (address sanitizer, thread sanitizer, clang thread safety analysis)
* Test suite passes
* Code coverage is measured, and non-decreasing level is enforced in PRs
* Issues and pull requests receive prompt responses
* Releases go out regularly when bugfixes or new features are introduced
* The backlog is maintained, avoiding longstanding stale issues

### Adding new subprojects

To request introduction of a new subproject, add a list item to the "Subprojects" section and open a Pull Request to this repository, following the default Pull Request Template to populate the text of the PR.

PR will be merged on unanimous approval from Approvers.

### Subproject changes

Modify the relevant list item in the "Subprojects" section and open a Pull Request to this repository, following the default Pull Request Template to populate the text of the PR.

PR will be merged on unanimous approval from Approvers.

### Deprecating subprojects

Projects cease to be useful, or the WG can decide it is no longer in their interest to maintain.
We do not commit to maintaining every subproject in perpetuity.

To suggest removal of a subproject, remove the relevant list item in the "Subprojects" section and open a Pull Request in this repository, following instructions in the Pull Request Template to populate the text of the PR.

PR will be merged on unanimous approval from Approvers.

If the repositories of the subproject are under the WG's GitHub organization, they will be transferred out of the organization or deleted at this time.

## Governance
- Ronaldson Bellande

### Meetings

* Regular WG Meeting: {{time schedule for meetings}}
  * {{when and where will meetings be announced}}
  * {{what artifacts will be posted after the meetings, e.g. Minutes, Recordings}}

### Communication Channels
- Email: ronaldsonbellande@gmail.com
- 

### Backlog Management

{{Is any project management software/site used to track work for this Working Group? How can new members discover the highest impact tasks they could take on? GitHub Projects, ZenHub, etc.}}

### Membership, Roles and Organization Management

Working Group members may act in one or more of the following roles:

* **Member**
  * Ronaldson Bellande
  * Responsible for triaging issues
* **Reviewer**
  * Ronaldson Bellande
  * Prerequisite: Proven track record of high-quality reviews to WG Subprojects
  * Responsible for reviewing pull requests
* **Approver**
  * Ronaldson Bellande
  * Prerequisite: Proven track record of high-quality contributions and reviews to WG Subprojects
  * Responsible for approving and merging pull requests
  * Responsible for vetting and accepting new projects into the Working Group
* **Lead**
  * Ronaldson Bellande
  * Responsible for organizing and moderating working group meetings
  * Responsible for posting meeting materials (minutes, recordings, etc.)
  * Responsible for breaking ties

To become a member or change role, create an issue in this repository using the appropriate issue template.
Such applications are accepted upon unanimous agreement from Approvers, and are typically based on the applicant's history with the subprojects of the Working Group.
The Lead role cannot be applied for, as it is an appointee of the ROS 2 TSC.

### Modifying this governance document

Changes to this document will be made via Pull Request.
The PR will be merged on unanimous agreement from Approvers.
