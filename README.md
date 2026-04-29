flowchart LR
    A[💻 Developer<br>Write Code] --> B[🔧 Git<br>Version Control]

    B -->|Commit / Push| C[🌐 GitHub Repository]

    C -->|Triggers Workflow| D[⚙️ GitHub Actions<br>CI/CD Pipeline]

    subgraph CI[Continuous Integration]
        D1[🔍 Lint & Code Quality Checks]
        D2[🧪 Run Unit & Integration Tests]
        D3[📦 Build Artifacts]
    end

    D --> CI

    subgraph CD[Continuous Deployment]
        E1[🚀 Deploy to Dev Environment]
        E2[🔄 Automated Tests / QA]
        E3[⬆️ Promote to Staging]
        E4[🌐 Deploy to Production]
    end

    CI --> CD

    E4 --> F[📊 Monitoring & Logging<br>Observability Tools]

    F -->|Feedback Loop| A
