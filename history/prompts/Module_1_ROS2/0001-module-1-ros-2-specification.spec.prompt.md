---
id: 0001
title: Module 1 ROS 2 Specification
stage: spec
date: 2025-12-06
surface: agent
model: claude-sonnet-4-5-20250929
feature: Module_1_ROS2
branch: 001-intro-physical-ai
user: unknown
command: /sp.specify
labels: ["textbook", "ros2", "specification"]
links:
  spec: specs/Module_1_ROS2/spec.md
  ticket: null
  adr: null
  pr: null
files:
  - specs/Module_1_ROS2/spec.md
tests:
  -
---

## Prompt

```text
/sp.specify

Chapter: Module 1 — The Robotic Nervous System (ROS 2)
Placement: Chapter 2 of the textbook

Goal:
Teach the foundational concepts of ROS 2 as the middleware and "nervous system" of humanoid robots. Students should understand how messages flow, how nodes communicate, how robot hardware is abstracted, and how Python Agents connect to ROS controllers.

Target audience:
- Students with basic programming experience (Python)
- Learners who have never used ROS 2 before
- Robotics beginners who need a practical, hands-on introduction

Focus areas:
- ROS 2 architecture
- Nodes, topics, services, actions
- ROS 2 communication graph
- Writing simple ROS 2 nodes in Python
- rclpy fundamentals
- Launch files and parameters
- URDF basics for humanoid robots
- Connecting Python Agents to ROS controllers

Success criteria:
- Student can explain how ROS 2 works and why it is essential for humanoid robots
- Student can write, run, and test basic ROS 2 nodes
- Student understands topics, publishers/subscribers, services, and actions
- Student can create minimal launch files and parameter configs
- Student understands URDF enough to read and modify humanoid robot descriptions
- Chapter is structured for RAG: clean sections, short paragraphs, consistent terminology

Required content:
- ROS 2 overview and history
- ROS graph: nodes, topics, edges, QoS
- Practical examples of publishers/subscribers
- rclpy code samples
- Sample launch files
- URDF explanation with humanoid-specific elements (links, joints, sensors)
- Mini-labs:
  - Build first ROS 2 package
  - Create a publisher/subscriber
  - Launch file with parameters
- 5–7 review questions
- At least 3 authoritative citations (ROS docs, research papers, etc.)


Constraints:
- Length: 2,000–3,000 words
- Format: Markdown (Docusaurus)
- Include diagrams described textually (for future image generation)
- Code examples must be executable on ROS 2 Humble (Ubuntu 22.04)
- Writing level: Flesch-Kincaid grade 10–12
- Avoid complex math (focus on conceptual + practical)

Not building:
- Deep DDS (Data Distribution Service) transport-level details
- Real robot hardware integration (covered in later modules)
- Simulation in Gazebo/Unity (covered in Module 2)

Timeline: Generate within 1–2 writing cycles.
```

## Response snapshot

Generated the specification for Module 1 - ROS 2, and wrote it to `specs/Module_1_ROS2/spec.md`.

## Outcome

- ✅ Impact: The specification for Module 1 - ROS 2 has been created.
- 🧪 Tests: No automated tests were run for this specification generation.
- 📁 Files: `specs/Module_1_ROS2/spec.md` was created.
- 🔁 Next prompts: Review the generated specification for Module 1 - ROS 2.
- 🧠 Reflection: The specification was generated based on the provided requirements and constraints, including Docusaurus Markdown format, content outline, and non-goals.

## Evaluation notes (flywheel)

- Failure modes observed: None observed.
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): N/A