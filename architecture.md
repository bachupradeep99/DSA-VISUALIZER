🏗 System Architecture

The DSA Visualizer follows a multi-layer execution pipeline:

1️⃣ Input Layer

Receives:

Algorithm type

Input dataset

2️⃣ Code Generation Layer

Dynamically generates algorithm simulation logic.

3️⃣ Execution Layer

Runs Python simulation inside a sandbox environment.

Outputs:

Step number

Operation performed

Current state of variables

4️⃣ Trace Engine

Transforms execution output into structured state snapshots.

5️⃣ Rendering Engine

JavaScript interprets trace and animates:

Comparisons

Swaps

Insertions

Deletions

6️⃣ UI Control Layer

Controls:

Play / Pause

Step Forward / Backward

Speed Slider

This architecture separates:

Logic

Execution

Rendering

Interaction

Making the system modular and extensible.
