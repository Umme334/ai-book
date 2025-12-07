# Physical AI & Humanoid Robotics: A Beginner-Friendly Guide Constitution
<!-- Sync Impact Report
Version: 0.0.0 → 1.0.0
Modified: All sections (Initial creation)
Added sections: Core Principles (Accessibility, Practicality, Completeness, Brevity), Book Scope & Constraints, Governance.
Templates requiring updates:
- .specify/templates/plan-template.md (✅ updated)
- .specify/templates/spec-template.md (✅ updated)
- .specify/templates/tasks-template.md (✅ updated)
-->

## Core Principles

### I. Accessibility First
<!-- Beginner-Friendly, Simple Tone -->
The book must be intelligible to beginners with basic coding skills. Avoid academic jargon and complex mathematical theory unless absolutely necessary. The tone should be encouraging, simple, and practical. If a concept is complex, break it down or use an analogy.

### II. Practicality Over Theory
<!-- Actionable, Simulation-Focused, No Fluff -->
Every chapter must lead to a tangible result or skill. Prioritize "learning by doing" in simulation (Gazebo/Unity/Isaac). Avoid theoretical fluff; focus on the "how-to" of building a pipeline. The ultimate test is: "Can the student run this code and see a robot do something?"

### III. End-to-End Completeness
<!-- Full Pipeline Coverage -->
The book must cover the entire modern robotics pipeline: ROS 2 (Nervous System) → NVIDIA Isaac (Brain) → Gazebo/Unity (Body/World) → VLA (Vision-Language-Action) integration. Students must understand how these pieces connect to form a functional humanoid system.

### IV. Brevity & Focus
<!-- Short, Essential Concepts Only -->
Respect the reader's time. Limit the book to 6-8 focused chapters. Do not aim for an exhaustive reference manual; aim for a "vertical slice" of competence. If a topic is not critical for the final capstone robot, exclude it.

## Book Scope & Constraints

### Target Audience
Beginner developers, hobbyists, and students interested in embodied AI and robotics.

### Scope
A short, complete guide taking a user from zero to a functional humanoid robot simulation using modern tools (ROS 2, Isaac, VLA).

### Deliverables
- 6-8 concise chapters.
- Functional code examples for each stage.
- A final capstone project: A simulated humanoid performing a task using VLA.
- Necessary diagrams to explain architecture.

## Governance

### Amendment Process
Amendments to this constitution must be proposed via a Pull Request (PR) or an Architectural Decision Record (ADR). Changes must be ratified by the project lead.

### Versioning
This constitution follows Semantic Versioning (MAJOR.MINOR.PATCH):
- **MAJOR**: Backward incompatible changes to core principles or scope.
- **MINOR**: Addition of new guidelines or significant clarifications.
- **PATCH**: Typo fixes, formatting changes, or minor rewording.

### Compliance
All book content (text, code, diagrams) must adhere to these principles. Code reviews and content edits must cite these principles when requesting changes.

**Version**: 1.0.0 | **Ratified**: 2025-12-06 | **Last Amended**: 2025-12-06