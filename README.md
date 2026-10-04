# MPB Framework: Mind, Paper, Building

A structured method for taking a project from idea to working system without skipping the thinking. MPB splits every project into three stages, each ending with a gate that must be passed before the next stage begins. It was written with automation and AI workflow projects in mind, and the examples use n8n.

## The Three Stages

| Stage | Question it answers | Gate to pass |
| --- | --- | --- |
| Mind | Do I fully understand the problem and the end-to-end logic? | A two-line goal, the audience and value, and a complete start-to-finish logic with no gaps |
| Paper | Is the plan sound before anything is built? | A diagram or outline, a tool stack with a validated proof of concept, and key risks mitigated |
| Building | Can it be built, monitored and reversed safely? | The build matches the plan, monitoring and rollback are ready, and no unknowns remain open |

## What Is in This Repository

| Path | Contents |
| --- | --- |
| `docs/QUICK_REFERENCE.md` | One-page summary of the three stages and their gates |
| `library/MPB_Mental_Model_Library.md` | 21 mental models organised by stage. Each has a purpose and a ready-to-use prompt. Examples: First Principles Thinking and Inversion (Mind), Critical Path and Red Team (Paper), Premortem and OODA (Building) |
| `library/MPB_Starter_Macros.md` | Copy-and-paste prompts that start each stage quickly |
| `library/MPB_Cheatsheet.png` | Visual cheat sheet |
| `examples/End_to_End_Client_Acquisition_And_Onboarding_Automation.md` | Worked example: automating discovery call booking, CRM entry and client onboarding for coaches and consultants |
| `examples/N8N_Example_Automated_New_Leads_Notification_System.md` | Worked example: an n8n workflow that notifies a team about new leads |
| `CHANGELOG.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md` | Project governance |

## How to Use It

1. Read `docs/QUICK_REFERENCE.md`.
2. Start with the Mind starter macro from `library/MPB_Starter_Macros.md`. Replace the placeholders with your project and run it with an AI assistant or work through it by hand.
3. Do not move to Paper until the Mind gate is met. Repeat for Paper and Building.
4. Pick extra models from the library whenever a stage needs more rigour, for example Inversion when you are worried about failure modes.
5. Study the two examples to see the stages applied to real automation projects.

## Contributing

Suggestions for new models, examples and improvements are welcome. Read `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md` first.

## Author

Aderemi Moses Timileyin ([@mosesaderemi](https://github.com/mosesaderemi))

## License

Released under the MIT License. See `LICENSE`.
