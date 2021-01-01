
## Chaos Engineering


- As more companies move toward microservices and other distributed technologies, the complexity of these systems increases. You can't remove the complexity, but through Chaos Engineering you can discover vulnerabilities and prevent outages before they impact your customers.
- This practical guide shows engineers how to navigate complex systems while optimizing to meet business goals.


- Learn how Chaos Engineering enables your organization to navigate complexity
- Explore a methodology to avoid failures within your application, network, and infrastructure
- Move from theory to practice through real-world stories from industry experts at Google, Microsoft, Slack, and LinkedIn, among others
- Establish a framework for thinking about complexity within software systems
- Design a Chaos Engineering program around game days and move toward highly targeted, automated experiments
- Learn how to design continuous collaborative chaos experiments


```
I. Setting the Stage

1. Encountering Complex Systems
            Contemplating Complexity
            Encountering Complexity
            Example 1: Mismatch Between Business Logic and Application Logic
            Example 2: Customer-Induced Retry Storm
            Example 3: Holiday Code Freeze
            Confronting Complexity
            Accidental Complexity
            Essential Complexity
            Embracing Complexity
2. Navigating Complex Systems
            Dynamic Safety Model
            Economics
            Workload
            Safety
            Economic Pillars of Complexity
            State
            Relationships
            Environment
            Reversibility
            Economic Pillars of Complexity Applied to Software
            The Systemic Perspective
3. Overview of Principles
            What Chaos Engineering Is
            Experimentation Versus Testing
            Verification Versus Validation
            What Chaos Engineering Is Not
            Breaking Stuff
            Antifragility
            Advanced Principles
            Build a Hypothesis Around Steady-State Behavior
            Vary Real-World Events
            Run Experiments in Production
            Automate Experiments to Run Continuously
            Minimize Blast Radius
            The Future of “The Principles”


II. Principles in Action

4. Slack’s Disasterpiece Theater
            Retrofitting Chaos
            Design Patterns Common in Older Systems
            Design Patterns Common in Newer Systems
            Getting to Basic Fault Tolerance
            Disasterpiece Theater
            Goals
            Anti-Goals
            The Process
            Preparation
            The Exercise
            Debriefing
            How the Process Has Evolved
            Getting Management Buy-In
            Results
            Avoid Cache Inconsistency
            Try, Try Again (for Safety)
            Impossibility Result

5. Google DiRT: Disaster Recovery Testing
            Life of a DiRT Test
            The Rules of Engagement
            What to Test
            How to Test
            Gathering Results
            Scope of Tests at Google

6. Microsoft Variation and Prioritization of Experiments
            Why Is Everything So Complicated?
            An Example of Unexpected Complications
            A Simple System Is the Tip of the Iceberg
            Categories of Experiment Outcomes
            Known Events/Unexpected Consequences
            Unknown Events/Unexpected Consequences
            Prioritization of Failures
            Explore Dependencies
            Degree of Variation
            Varying Failures
            Combining Variation and Prioritization
            Expanding Variation to Dependencies
            Deploying Experiments at Scale

7. LinkedIn Being Mindful of Members
            Learning from Disaster
            Granularly Targeting Experiments
            Experimenting at Scale, Safely
            In Practice: LinkedOut
            Failure Modes
            Using LiX to Target Experiments
            Browser Extension for Rapid Experimentation
            Automated Experimentation

8. Capital One Adoption and Evolution of Chaos Engineering
            A Capital One Case Study
            Blind Resiliency Testing
            Transition to Chaos Engineering
            Chaos Experiments in CI/CD
            Things to Watch Out for While Designing the Experiment
            Tooling
            Team Structure
            Evangelism

III. Human Factors

9. Creating Foresight
            Chaos Engineering and Resilience
            Steps of the Chaos Engineering Cycle
            Designing the Experiment
            Tool Support for Chaos Experiment Design
            Effectively Partnering Internally
            Understand Operating Procedures
            Discuss Scope
            Hypothesize
            
10. Humanistic Chaos
            Humans in the System
            Putting the “Socio” in Sociotechnical Systems
            Organizations Are a System of Systems
            Engineering Adaptive Capacity
            Spotting Weak Signals
            Failure and Success, Two Sides of the Same Coin
            Putting the Principles into Practice
            Build a Hypothesis
            Vary Real-World Events
            Minimize the Blast Radius
            Case Study 1: Gaming Your Game Days
            Communication: The Network Latency of Any Organization
            Case Study 2: Connecting the Dots
            Leadership Is an Emergent Property of the System
            Case Study 3: Changing a Basic Assumption
            Safely Organizing the Chaos
            All You Need Is Altitude and a Direction
            Close the Loops
            If You’re Not Failing, You’re Not Learning
            11. People in the Loop
            The Why, How, and When of Experiments
            The Why
            The How
            The When
            Functional Allocation, or Humans-Are-Better-At/Machines-Are-Better-At
            The Substitution Myth
            
12. The Experiment Selection Problem (and a Solution)
            Choosing Experiments
            Random Search
            The Age of the Experts
            Observability: The Opportunity
            Observability for Intuition Engineering

IV. Business Factors

13. ROI of Chaos Engineering
            Ephemeral Nature of Incident Reduction
            Kirkpatrick Model
            Level 1: Reaction
            Level 2: Learning
            Level 3: Transfer
            Level 4: Results
            Alternative ROI Example
            Collateral ROI
            
14. Open Minds, Open Science, and Open Chaos
            Collaborative Mindsets
            Open Science; Open Source
            Open Chaos Experiments
            Experiment Findings, Shareable Results

15. Chaos Maturity Model
            Adoption
            Who Bought into Chaos Engineering
            How Much of the Organization Participates in Chaos Engineering
            Prerequisites
            Obstacles to Adoption
            Sophistication
            Putting It All Together

V. Evolution

16. Continuous Verification
            Where CV Comes From
            Types of CV Systems
            CV in the Wild: ChAP
            ChAP: Selecting Experiments
            ChAP: Running Experiments
            The Advanced Principles in ChAP
            ChAP as Continuous Verification
            CV Coming Soon to a System Near You
            Performance Testing
            Data Artifacts
            Correctness
17. Let’s Get Cyber-Physical
            The Rise of Cyber-Physical Systems
            Functional Safety Meets Chaos Engineering
            FMEA and Chaos Engineering
            Software in Cyber-Physical Systems
            Chaos Engineering as a Step Beyond FMEA
            Probe Effect
            Addressing the Probe Effect

18. HOP Meets Chaos Engineering
            What Is Human and Organizational Performance (HOP)?
            Key Principles of HOP
            Principle 1: Error Is Normal
            Principle 2: Blame Fixes Nothing
            Principle 3: Context Drives Behavior
            Principle 4: Learning and Improving Is Vital
            Principle 5: Intentional Response Matters
            HOP Meets Chaos Engineering
            Chaos Engineering and HOP in Practice

19. Chaos Engineering on a Database
            Why Do We Need Chaos Engineering?
            Robustness and Stability
            A Real-World Example
            Applying Chaos Engineering
            Our Way of Embracing Chaos
            Fault Injection
            Fault Injection in Applications
            Fault Injection in CPU and Memory
            Fault Injection in the Network
            Fault Injection in the Filesystem
            Detecting Failures
            Automating Chaos
            Automated Experimentation Platform: Schrodinger
            Schrodinger Workflow
            
20. The Case for Security Chaos Engineering
            A Modern Approach to Security
            Human Factors and Failure
            Remove the Low-Hanging Fruit
            Feedback Loops
            Security Chaos Engineering and Current Methods
            Problems with Red Teaming
            Problems with Purple Teaming
            Benefits of Security Chaos Engineering
            Security Game Days
            Example Security Chaos Engineering Tool: ChaoSlingr
            The Story of ChaoSlingr
