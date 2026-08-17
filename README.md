### Hey, I'm Gafar

Getting into cloud security. A principal engineer at my company told me to "put Prowler in front of an EKS cluster and see how it goes" — so I did, and kept going.

**Following along:** [medium.com/@gafar.cloud](https://medium.com/@gafar.cloud)

### Projects

- **[cnapp-eks](https://github.com/gafarbalogun/cnapp-eks)** — rebuilding a commercial CNAPP (Prowler, Kubescape, Falco, Trivy) on a real EKS cluster, with Terraform, to see what's actually happening under the hood of tools like Wiz and Prisma Cloud.
- **[mac-lib](https://github.com/gafarbalogun/mac-lib)** — a single CLI that unifies every package manager on macOS (brew, pipx, npm, gem, cargo, mas...) and scans all of them for known CVEs via grype, trivy, syft, and osv-scanner.
- **[secure-pipeline](https://github.com/gafarbalogun/secure-pipeline)** — my first attempt at a security-gated CI/CD pipeline, from before I knew Docker. Kept as a record of where this started.
- **[argocd-example-apps](https://github.com/gafarbalogun/argocd-example-apps)** — pointed ArgoCD at my own fork of this repo, both on a local cluster and a real one, and watched it self-heal manual changes back to what git said. GitOps clicked after that.

### Currently working on

- Wrapping up `cnapp-eks` — the build itself is basically done, just finishing the writeup and publishing as I go.
- A personal finance dashboard built on Mercury's API — real-time transaction sync into a unified calendar view. Private for now.
