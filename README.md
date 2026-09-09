# access-platform

The repo viewers clone. Becomes its own git repo when published.

Target layout (from `../planning/PLAN.md`):

```
access-platform/
├── README.md
├── access/
│   ├── teams/falcon.yaml            # who, and what role
│   └── roles/                       # what each role means per environment
├── data-products/
│   └── falcon-events.yaml           # bucket, catalog db, job, role
├── baseline/modules/account-baseline/
├── policies/
│   ├── scps/                        # incl. PassRole scoping and the DPU cap
│   ├── rcps/
│   ├── boundaries/                  # the self-referencing data boundary
│   └── declarative/
├── terraform/
│   ├── identity/
│   ├── data-platform/
│   ├── org/
│   └── baseline/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── access-request.yml
│   │   └── data-product-request.yml
│   ├── CODEOWNERS
│   └── workflows/
└── docs/
```

Nothing built yet. Build order is in `../README.md`.
