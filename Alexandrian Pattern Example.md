# ADR 001: process to documented Architectural Decisions

## STATUS
Active

## PROLOGUE
Determine the process for documenting the vendor selection, enterprise, architectural, and design decisions of this project.

## CONTEXT:
The team has gather 9 months of research and now requires a streamlined process to narrow down the selection of key processes and technologies to move forward. Organizational practices require a base level of documentation to move forward.

Additional concerns around team members not being aligned on the technologies or processes being leveraged, in-consistent communication throughout the tech and business teams, and the need for referenceable documentation on technologies, requires the creation of the ADRs


## DECISION:
Our recommendation is Light Weight Architectural Design Records. This pattern is documented in the Nov 2016 ThoughtWorks Tech Radar as an adopt. We have found that agile based projects benefit from documentation that can keep pace. ADR's can achieve this by being small and providing one specific decision per record.

The consequences on this decision are focused to the storage and review of the document. Today, teams spend months writing documentation that is not referenced later in the project. ADRs are stored with the code at the design level and within the organizations WIKI for enterprise, architectural, and vendor selections.

The recommended format is based on the Alexandrian Pattern as seen in this very document. A working template can be found in the WIKI at [add http://]

The Format is --
1. **Title**
     - A simple title that is focused on the point of the ADR.
     - e.g. Deployment on Ruby on Rails
     - e.g. Data Platform Selection

2. **Status**
     - Active, Pending, or Deprecated status.

3. **Prologue**
     - One Sentence focusing on the purpose of the ADR

4. **Context**
     - Explain the forces that are at play {technical, social, political, project specific}
     - Focus on the facts of the problem we are looking to solve

5. **Decision**
     - Explain "How We Will .." solve the problem
     - Why was this solution selected
     - Describe the facts of the solution

6. **Consequences**
     - Are there any short or long term consequences to be aware of? We will still be making this decision with the understanding that this may be a problem to readdress in the future.


## CONSEQUENCES
- Failure to document any of the decisions will lead to confusion and a failure of the overall project.
- Too much documentation and the teams will be focused on the wrong deliverables -- Documentation of delivery.
