# Athanor: Containerized Elixir Environments

## Introduction

Athanor is a foundational toolset designed to bootstrap containerized environments for Elixir and Phoenix-based projects. This project is forked from [docker-phoenix](https://github.com/nicbet/docker-phoenix), which served as inspiration and initial foundation for containerized development tailored to Elixir and Phoenix workflows.

### What are Elixir and Phoenix?

- **Elixir**: Elixir is a functional, concurrent programming language built on the Erlang Virtual Machine (BEAM). It is designed for building scalable, maintainable applications with a focus on performance and fault tolerance.

- **Phoenix**: Phoenix is a modern web development framework written in Elixir, known for its speed, scalability, and real-time capabilities. It simplifies building highly performant web applications and APIs.

#### Learn More
Here is a short video introducing Elixir and very briefly Phoenix:

<br>
<div align="center">
  <a href="https://www.youtube.com/watch?v=R7t7zca8SyM&list=PLi4CU1p4A8FcJwCYi3YHSmI4-Tx-gXile">
    <img src="https://img.youtube.com/vi/R7t7zca8SyM/0.jpg" alt="Introduction to Elixir and Phoenix">
  </a>
</div>
<br>

By modularizing and targeting specific use cases, Athanor aims to provide developers with tools and extensions directly within their VSCode projects, accessible through devcontainers. Inspired by alchemical principles, Athanor emphasizes iteration, experimentation, and refinement as key to achieving development excellence.

## Why Containerize Elixir Applications?

Although Elixir runs on the Erlang Virtual Machine (BEAM), containerizing Elixir applications offers several benefits:

- **Environment Standardization**: Ensures consistent runtime environments across development, staging, and production.
- **Dependency Isolation**: Avoids conflicts by isolating specific versions of Elixir, Erlang/OTP, and other dependencies.
- **Simplified Deployment**: Packages the application and its dependencies, making deployment processes more predictable.
- **Scalability and Orchestration**: Integrates seamlessly with tools like Kubernetes for managing distributed and scalable systems.
- **CI/CD Integration**: Enables consistent testing and deployment pipelines using containerized environments.

## Core Philosophy: "Let It Crash"

Adopting the philosophy of "let it crash," Athanor embraces the symbolic Negredo, where development begins in chaos and emerges with clarity and purpose. Each failure is an opportunity to refine and better understand the needs of the project, fostering resilience and adaptability. This ethos is woven into the roadmap and release strategy, allowing for innovation through trial and error.

## Repository Structure

- **Main Branch**: Houses all documentation and centralized codebase for reference and development.
- **Version Branches**: Contain targeted, stable releases tailored to specific development use cases. Releases will be named to reflect their alchemical, esoteric, astrological, or divine inspiration, aligning with the purpose they aim to serve.

  Examples:

| Release Name         | Description                                                                |
|----------------------|----------------------------------------------------------------------------|
| `v1.0-Prima_Materia` | Foundational release for Elixir and Phoenix projects.                      |
| `v1.1-Sol_Unitas`    | Includes Docker Dev Container images for centralized remote collaboration. |
| `v2.0-Ordo_Ab_Chao`  | Provides standardized configurations for distributed teams.                |
| `v3.0-Ignis_Ardens`  | Adds tools and configurations for scalable cloud deployments.              |

## Planning Releases

### Agile Roadmap

Releases are iterative and follow an agile methodology to encourage rapid prototyping and feedback. Each release cycle incorporates:

1. **Discovery**: Define the problem or use case.
2. **Implementation**: Build and test solutions within a controlled branch.
3. **Review**: Gather community feedback.
4. **Stabilization**: Finalize and merge to the version branch.

### Release Schedule

- **Initial MVP (v1.0)**

  - Base Docker configuration for Elixir and Phoenix.
  - Minimal VSCode devcontainer setup.
  - Basic documentation for integration.

- **v1.1: Collaboration Enhancements**

  - Add support for centralized Docker Dev Container images.
  - Include tooling for remote debugging and collaboration.

- **v2.0: Standardized Development**

  - Provide standardized VSCode devcontainers.
  - Expand documentation to support diverse use cases.

- **Future Milestones**

  - Integrate additional languages and frameworks.
  - Explore non-BEAM-based use cases.
  - Enable automated environment provisioning via CI/CD pipelines.

## Contributions

We welcome contributions that align with Athanor's philosophy. Contributors are encouraged to:

- Share insights gained from failed attempts or unmet edge cases.
- Propose enhancements and features through issues and pull requests.
- Participate in roadmap discussions to shape future releases.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/VitriolumCode/Athanor.git
   ```
2. Check out the main branch for documentation or switch to a version branch for targeted development:
   ```bash
   git checkout main
   ```
3. Follow the setup instructions in the README file within the desired version branch.

---

Athanor is an evolving project with the ultimate goal of simplifying and enriching the development experience. Together, we can transform chaos into order and build a toolkit worthy of the Great Work.
