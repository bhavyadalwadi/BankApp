# BankApp Graph Relationships

       ## Service Dependency Graph
       BankApp
-> primary application under `_image`
-> Queues/Events: not present
-> Deployment: No standardized deployment command is documented; treat this as a local/manual project.

       ## Runtime Dependency Graph
       BankApp
-> Runtime: HTML
-> Runtime: CSS
-> Runtime: JavaScript
-> Runtime: Bootstrap
-> Runtime: jQuery

       ## Database Relationship Graph
       BankApp
-> no dedicated database visible

       ## API Consumer / Provider Graph
       BankApp
-> no formal API contract visible

       ## Queue Publisher / Consumer Graph
       BankApp
-> no broker or queue layer visible

       ## Shared Package Dependency Graph
       BankApp
-> no notable shared package layer beyond app-local dependencies

       ## Deployment Relationship Graph
       BankApp
       - No standardized deployment command is documented; treat this as a local/manual project.

       ## Cross-Repo Relationship Graph
       BankApp
-> no runtime dependency on sibling repos by default
