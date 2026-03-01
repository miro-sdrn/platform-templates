# Platform Templates

Design diagrams and infographics for platform engineering.

## Structure

```
platform-templates/
├── infra/
│   ├── aws-three-tier.drawio              # AWS 3-tier architecture (draw.io)
│   └── terraform-module-structure.md      # Terraform module & state diagrams (Mermaid)
├── cicd/
│   ├── github-actions-pipeline.excalidraw # CI/CD pipeline (Excalidraw)
│   └── deployment-flow.md                 # Dev → Staging → Prod flow (Mermaid)
├── kubernetes/
│   ├── eks-cluster-architecture.svg       # EKS cluster overview (SVG)
│   └── pod-lifecycle.md                   # Pod lifecycle & HPA scaling (Mermaid)
└── networking/
    ├── vpc-design.drawio                  # Multi-AZ VPC design (draw.io)
    └── service-mesh.md                    # Service mesh traffic flow (Mermaid)
```

## Formats

| Format | Tool |
|--------|------|
| `.drawio` | [draw.io](https://app.diagrams.net) / VS Code extension |
| `.excalidraw` | [Excalidraw](https://excalidraw.com) / VS Code extension |
| `.svg` | Any browser or vector editor |
| `.md` (Mermaid) | GitHub renders natively |
