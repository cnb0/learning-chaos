
### learning chaos

Most companies work hard to avoid costly failures, but in complex systems a better approach is to embrace and learn from them. Through chaos engineering, you can proactively hunt for evidence of system weaknesses before they trigger a crisis. This practical book shows software developers and system administrators how to plan and run successful chaos engineering experiments.

System weaknesses go beyond your infrastructure, platforms, and applications to include policies, practices, playbooks, and people. Author Russ Miles explains why, when, and how to test systems, processes, and team responses using simulated failures on Game Days. You’ll also learn how to work toward continuous chaos through automation with features you can share across your team and organization.

- Learn to think like a chaos engineer
- Build a hypothesis backlog to determine what could go wrong in your system
- Develop your hypotheses into chaos engineering experiment Game Days
- Write, run, and learn from automated chaos experiments using the open source Chaos Toolkit
- Turn chaos experiments into tests to confirm that you’ve overcome the weaknesses you discovered
-  Observe and control your automated chaos experiments while they are running

```

I. Chaos Engineering Fundamentals

1. Chaos Engineering Distilled
                    Chaos Engineering Defined
                            Chaos Engineering Addresses the Whole Sociotechnical System
                            Locations of Dark Debt
                    The Process of Chaos Engineering
                    The Practices of Chaos Engineering
                            Sandbox/Staging or Production?
                    Chaos Engineering and Observability
                    Is There a “Chaos Engineer”?

2. Building a Hypothesis Backlog
                    Start with Experiments?
                    Gathering Hypotheses
                            Incident Analysis
                            Sketching Your System
                            Capturing “What Could Possibly Go Wrong?”
                    Introducing Likelihood and Impact
                            Building a Likelihood-Impact Map
                            Adding What You Care About
                    Creating Your Hypothesis Backlog

3. Planning and Running a Manual Game Day
                    What Is a Game Day?
                    Planning Your Game Day
                            Pick a Hypothesis
                            Pick a Style of Game Day
                            Decide Who Participates and Who Observes
                            Decide Where
                            Decide When and For How Long
                            Describe Your Game Day Experiment
                            Get Approval!
                    Running the Game Day
                            Consider a “Safety Monitor”

II. Chaos Engineering Automation

4. Getting Tooled Up for Automated Chaos Engineering
                    Installing Python 3
                    Installing the Chaos Toolkit CLI

5. Writing and Running Your First Automated Chaos Experiment
                    Setting Up the Sample Target System
                            A Quick Tour of the Sample System
                    Exploring and Discovering Evidence of Weaknesses
                            Running Your Experiment
                            Under the Skin of chaos run
                            Steady-State Deviation Might Indicate “Opportunity for Improvement”
                    Improving the System
                    Validating the Improvement

6. Chaos Engineering from Beginning to End
                    The Target System
                            The Platform: A Three-Node Kubernetes Cluster
                            The Application: A Single Service, Replicated Three Times
                            The People: Application Team and Cluster Administrators
                    Hunting for a Weakness
                            Naming Your Experiment
                            Defining Your Steady-State Hypothesis
                            Injecting Turbulent Conditions in an Experiment’s Method
                            Using the Kubernetes Driver from Your Method
                    Being a Good Citizen with Rollbacks
                    Bringing It All Together and Running Your Experiment
                            Overcoming a Weakness: Applying a Disruption Budget

7. Collaborative Chaos
                    Sharing Experiment Definitions
                            Moving Values into Configuration
                            Specifying Configuration Properties as Environment Variables
                            Externalizing Secrets
                            Scoping Secrets
                    Specifying a Contribution Model
                            Creating and Sharing Human-Readable Chaos Experiment Reports
                            Creating a Single-Experiment Execution Report
                    Creating and Sharing a Multiple Experiment Execution Report

8. Creating Custom Chaos Drivers
                    Creating Your Own Custom Driver with No Custom Code
                            Implementing Probes and Actions with HTTP Calls
                            Implementing Probes and Actions Through Process Calls
                    Creating Your Own Custom Chaos Driver in Python
                            Creating a New Python Module for Your Chaos Toolkit Extension Project
                            Adding the Probe

III. Chaos Engineering Operations

9. Chaos and Operations
                    Experiment “Controls”
                    Enabling Controls
                            Enabling a Control Inline in an Experiment
                            Enabling a Control Globally

10. Implementing Chaos Engineering Observability
                    Adding Logging to Your Chaos Experiments
                    Centralized Chaos Logging in Action
                    Tracing Your Chaos Experiments
                    Introducing OpenTracing
                    Applying the OpenTracing Control

11. Human Intervention in Chaos Experiment Automation
                    Creating a New Chaos Toolkit Extension for Your Controls
                    Adding Your (Very) Simple Human Interaction Control
                    Skipping or Executing an Experiment’s Activity

12. Continuous Chaos
                    What Is Continuous Chaos?
                    Scheduling Continuous Chaos Using cron
                            Creating a Script to Execute Your Chaos Tests
                            Adding Your Chaos Tests Script to cron
                    Scheduling Continuous Chaos with Jenkins
                            Grabbing a Copy of Jenkins
                            Adding Your Chaos Tests to a Jenkins Build
                            Scheduling Your Chaos Tests in Jenkins with Build Triggers

A. Chaos Toolkit Reference
                    The Default Chaos Commands
                            Discovering What’s Possible with the chaos discover Command
                            Authoring a New Experiment with the chaos init Command
                            Checking Your Experiment with the chaos validate Command
                    Extending the Chaos Commands with Plug-ins

B. The Chaos Toolkit Community Playground

