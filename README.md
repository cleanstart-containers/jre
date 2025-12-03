**CleanStart Container for jre**

Official jre container image optimized for enterprise environments. Includes the complete jre Development Kit (jre) and jre Runtime Environment (JRE) for jre application development and deployment. Features security-hardened base image, minimal attack surface, and FIPS-compliant cryptographic modules. Supports both production deployments and development workflows with separate tagged versions. Includes jre runtime, development tools, and essential jre libraries.

**Key Features**
* Complete jre development environment with jre and JRE capabilities
* Optimized for cloud-native and microservices architectures

**Common Use Cases**
* Building and deploying jre applications
* Cloud-native jre development

**Pull Commands**
Download the runtime container images

```bash
docker pull cleanstart/jre:latest
```
```bash
docker pull cleanstart/jre:latest-dev
```

**Interactive Development**
Start interactive session for development

```bash
docker run --rm -it --entrypoint /bin/sh cleanstart/jre:latest-dev
```

**Container Start**
Start the container
```bash
docker run --rm -it --name jre-dev cleanstart/jre:latest
```

**Best Practices**
* Use specific image tags for production (avoid latest)
* Configure resource limits: memory and CPU constraints
* Enable read-only root filesystem when possible

**Architecture Support**

**Multi-Platform Images**

```bash
docker pull --platform linux/amd64 cleanstart/jre:latest
```
```bash
docker pull --platform linux/arm64 cleanstart/jre:latest
```

**
### 
### Resources

- Official Documentation: https://docs.oracle.com/javase/8/docs/
- View Provenance, Specifications, SBOM, Signature at: https://images.cleanstart.com/images/jre
- Docker Hub: https://hub.docker.com/r/cleanstart/jre
- CleanStart All Images: https://images.cleanstart.com
- CleanStart All Community Images: https://hub.docker.com/u/cleanstart

---

### Vulnerability Disclaimer

CleanStart offers Docker images that include third-party open-source libraries and packages maintained by independent contributors. While CleanStart maintains these images and applies industry-standard security practices, it cannot guarantee the security or integrity of upstream components beyond its control.

Users acknowledge and agree that open-source software may contain undiscovered vulnerabilities or introduce new risks through updates. CleanStart shall not be liable for security issues originating from third-party libraries, including but not limited to zero-day exploits, supply chain attacks, or contributor-introduced risks.

Security remains a shared responsibility: CleanStart provides updated images and guidance where possible, while users are responsible for evaluating deployments and implementing appropriate controls.
