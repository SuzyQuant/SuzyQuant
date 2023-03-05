
```mermaid
flowchart TD
    A[complete_eb2_docs] --> B[complete_prong_1]
    A[complete_eb2_docs] --> C[complete_prong_2]
    A[complete_eb2_docs] --> D[complete_prong_3]

    B --> E[complete_DROID_project]

    C --> F[gather_credentials]
    C --> G[complete_timeline_narrative]

    D --> H[complete_gokart_narrative]
    D --> I[complete_pamiva_narrative]
    D --> J[complete_tangub_narrative]

    E --> K[research_DROID]

    G --> L[complete_long_resume]

```