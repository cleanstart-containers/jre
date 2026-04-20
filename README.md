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

## Documentation Resources
Essential links and resources for further information
 
**CleanStart Images**: https://images.cleanstart.com/
 
**Community Images**:<br>
**Docker Hub**: https://hub.docker.com/u/cleanstart<br>
**GitHub**: https://github.com/cleanstart-containers<br>
**AWS ECR Public Gallery**: https://gallery.ecr.aws/cleanstart/
 
**Presence on Social Media**:<br>
**Community**: https://www.linkedin.com/groups/18324021/<br>
**YouTube**: https://www.youtube.com/@CleanStartOfficial<br>
 
**Contribute to Container Use Cases**: https://github.com/cleanstart-dev/cleanstart-use-cases/
