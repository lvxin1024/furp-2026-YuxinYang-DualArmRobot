# Week 1 — 2026-06-08

**Attended this week's meeting:** Yes

**Progress this week**
- Initialized the repository from the FURP template and established the base project structure.
- Attended the project kickoff meeting and clarified the main research direction: whole-body coordinated control for a mobile dual-arm platform (MoveIt -> QP -> RL).
- Built understanding of the overall project background and phased goals, with focus on base-arm coupling, redundancy, and constrained control.
- Studied ROS 2 fundamentals (nodes, topics, services, TF, and basic communication workflow) to prepare for later MoveIt and control module development.
- Studied manipulator control theory fundamentals, including forward/inverse kinematics, Jacobians, redundancy, and constrained optimization (QP) concepts.

**Challenges & blockers**
- I am not yet fully familiar with the software stack details on the real hardware platform (URDF/MoveIt configuration, control interfaces, and existing launch workflow).
- Theory study has started, but the engineering path from equations to runnable control code still needs to be refined.
- A complete dual-arm MoveIt configuration and end-to-end example are not finished yet and need to be prioritized in the short term.

**Next steps**
- Complete robot model and kinematic-chain review: read URDF/TF and confirm dual-arm joint and end-effector definitions.
- Bring up model visualization and TF inspection in RViz, and set up a basic MoveIt runtime environment.
- Start with basic trajectory planning and execution for a single arm, then progress to independent dual-arm planning.
- Write the first MoveIt API control script (Python/C++) and create reproducible experiment records.
- Continue improving notes on ROS 2 and manipulator control theory to support upcoming QP-based whole-body control implementation.

**Hours spent (optional):**

30

**Links (optional):**
- ROS 2 Documentation: https://docs.ros.org/
- MoveIt Documentation: https://moveit.picknik.ai/