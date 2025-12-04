# CleanStart Container for JRE

Official JRE container image optimized for enterprise environments. Includes the complete JRE Development Kit (JRE) and JRE Runtime Environment (JRE) for JRE application development and deployment. Features security-hardened base image, minimal attack surface, and FIPS-compliant cryptographic modules. Supports both production deployments and development workflows with separate tagged versions. Includes JRE runtime, development tools, and essential JRE libraries.

## Key Features

- Complete JRE development environment with JRE and JRE capabilities
- Optimized for cloud-native and microservices architectures

## Common Use Cases

- Building and deploying JRE applications
- Cloud-native JRE development

## Pull Commands

Download the runtime container images
```bash
docker pull ghcr.io/cleanstart-containers/jre:latest
```
```bash
docker pull ghcr.io/cleanstart-containers/jre:latest-dev
```

## Interactive Development

Start interactive session for development
```bash
docker run --rm -it --entrypoint /bin/sh ghcr.io/cleanstart-containers/jre:latest-dev
```

## Container Start

Start the container
```bash
docker run --rm -it --name jre-dev ghcr.io/cleanstart-containers/jre:latest
```

## Best Practices

- Use specific image tags for production (avoid latest)
- Configure resource limits: memory and CPU constraints
- Enable read-only root filesystem when possible

## Architecture Support

### Multi-Platform Images
```bash
docker pull --platform linux/amd64 ghcr.io/cleanstart-containers/jre:latest
```
```bash
docker pull --platform linux/arm64 ghcr.io/cleanstart-containers/jre:latest
```

---

## Resources

- **Official Documentation:** https://docs.oracle.com/javase/8/docs/
- **Provenance / SBOM / Signature:** https://images.cleanstart.com/images/jre
- **Docker Hub:** https://hub.docker.com/r/cleanstart/jre
- **CleanStart All Images:** https://images.cleanstart.com
- **CleanStart Community Images:** https://hub.docker.com/u/cleanstart

### Vulnerability Disclaimer

CleanStart offers Docker images that include third-party open-source libraries and packages maintained by independent contributors. While CleanStart maintains these images and applies industry-standard security practices, it cannot guarantee the security or integrity of upstream components beyond its control.

Users acknowledge and agree that open-source software may contain undiscovered vulnerabilities or introduce new risks through updates. CleanStart shall not be liable for security issues originating from third-party libraries, including but not limited to zero-day exploits, supply chain attacks, or contributor-introduced risks.

Security remains a shared responsibility: CleanStart provides updated images and guidance where possible, while users are responsible for evaluating deployments and implementing appropriate controls.
