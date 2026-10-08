# <img src="public/favicon.svg" width="30" alt="C365 logo"> C365

## Carbonwarp C365

**Website:** [c365.carbonwarp.com](https://c365.carbonwarp.com)

**A comprehensive resource for learning container technologies.**

C365 is an open educational resource focused on understanding containers from both a practical and architectural perspective.

The project is divided into learning tracks for people who want to **use container technology effectively**, as well as those who want to understand **how containers work underneath the surface and build them from scratch**.

C365 is a relatively new project and is continuously being expanded. Contributions, corrections, examples, and new learning material are greatly appreciated.

The current material focuses primarily on RPM-based Linux hosts and Podman containers. While the concepts are intended to be useful across Linux distributions, it is recommended to use a system configured according to the [setup guide](https://c365.carbonwarp.com/containers/setup/).

## Learning Tracks

Before starting any track, it is recommended to read [Get Started](https://c365.carbonwarp.com/get-started/).

### Work with Podman

A practical track focused on developing fluency with containers using [Podman](https://c365.carbonwarp.com/containers/).

Topics currently covered:

* Podman fundamentals
* Basic container usage and workflows
* Practical container working fluency

More material is currently being developed.

### Containers Architecture

A deeper track focused on understanding what containers are and how they are built using Linux kernel primitives.

Topics currently covered:

* Fundamental container architecture
* Understanding the components behind containers
* Creating your own container from scratch
* Working with Linux kernel primitives

More material is currently being developed.

This track moves beyond using container tools and explains the mechanisms that make containerization possible.

## Contributing & License

C365 is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. Contributions must also be provided under **CC BY 4.0**.

See the [LICENSE](LICENSE) file for the complete license terms.

Contributions are welcome. You do not need to be an expert in container technology to contribute. Improving an explanation, fixing a typo, adding an example, correcting a command, or suggesting a missing topic can all help improve C365.

### What You Can Contribute

* Fix incorrect or outdated information
* Improve explanations
* Add practical examples
* Add architecture explanations
* Add diagrams or illustrations
* Add new lessons or sections
* Improve existing exercises
* Test instructions on different Linux distributions
* Fix spelling, grammar, or formatting
* Report missing or confusing material

### How to Contribute

1. **Fork the repository.**

2. **Clone your fork:**

   ```bash
   mkdir c365
   git clone <your-fork-url> c365
   cd c365
   ```

3. **Create a branch:**

   ```bash
   git checkout -b <branch-name>
   ```

4. **Make your changes.**

   Keep changes focused and test technical instructions where possible.

5. **Check your changes locally.**

   Follow the project's development instructions and make sure the documentation builds correctly.

6. **Commit your changes:**

   ```bash
   git add .
   git commit -m "<short commit message>" -m "<detailed description>"
   ```

7. **Push your branch:**

   ```bash
   git push origin <branch-name>
   ```

8. **Open a Pull Request** against the main C365 repository.

In your pull request, describe **what you changed and why**. For technical changes, include enough information for the change to be reproduced or verified.

## Writing Guidelines

C365 aims to be practical without hiding the underlying technology.

When contributing documentation:

* Prefer clear explanations over unnecessary terminology.
* Put unfamiliar terminology in the [glossary](https://c365.carbonwarp.com/glossary/).
* Explain unfamiliar concepts before relying on them.
* Use commands that can be reproduced by the reader.
* Explain *why* something works, not only *what* command to run.
* Keep examples realistic.
* Avoid assuming that every Linux system has the same configuration.
* Clearly distinguish between Podman-specific behavior and general container concepts.
* Test technical instructions whenever possible.
* Update existing material rather than creating duplicate explanations.

For architecture material, explain the underlying Linux primitives and mechanisms instead of treating them as a black box.

## Reporting Issues

If you find a problem, open an issue with:

* The page or section affected
* What you expected
* What actually happened
* Relevant commands or output
* Your Linux distribution and container runtime version, when applicable

Documentation issues are valuable too. If something is difficult to understand, that can indicate that the explanation itself needs improvement.

## Philosophy

> **Learn to use containers, then learn how containers work.**

C365 aims to provide both practical knowledge for working with containers and the architectural knowledge needed to understand what the underlying tooling is actually doing.
